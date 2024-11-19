## 1. Extract all email addresses from the text.
$ grep -E -o '[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}' contacts.csv
- john.doe@example.com
- jane.smith@gmail.com
- mjohnson@yahoo.com
- lharris@hotmail.com
- rbrown@company.com
- alice.white@domain.org
- dgreen@domain.net
- eblack@webmail.com
- cblue@provider.com
- ssilver@university.edu

---

## 2. Extract all phone numbers from the text.
$ grep -E -o '\(?[0-9]{3}\)?[-. ]?[0-9]{3}[-. ]?[0-9]{4}' contacts.csv
- (555) 123-4567
- (555) 987-6543
- (555) 555-5555
- (555) 321-6789
- (555) 876-5432
- (555) 432-5678
- (555) 246-1357
- (555) 531-2468
- (555) 864-9753
- (555) 975-8642

---

## 3. Extract all names that start with the letter ‘J’.
grep -E -o '\bJ[A-Za-z]*' contacts.csv
- John
- Jane
- Johnson

---

## 4. Extract all street names that contain the word 'St'.
$ grep -E -o '\b[A-Za-z0-9 ]+ St\b' contacts.csv
- 123 Main St
- 456 Oak St
- 654 Cedar St
- 987 Elm St
- 246 Birch St
- 135 Walnut St
- 864 Chestnut St

---
  
## 5. Extract all addresses in ‘USA’.
$ awk -F ',' '$4 ~ /USA/ {print $2", "$3", "$4}' contacts.csv
- 123 Main St,  Anytown,  USA
- 456 Oak St,  Sometown,  USA
- 789 Pine Rd,  Othertown,  USA
- 321 Maple Dr,  Newcity,  USA
- 654 Cedar St,  Oldtown,  USA
- 987 Elm St,  Smalltown,  USA
- 246 Birch St,  Uptown,  USA
- 135 Walnut St,  Middletown,  USA
- 864 Chestnut St,  Metropolis,  USA
- 975 Cypress Ave,  Bigcity,  USA

---
 
## 6. Extract the last names of all people.
$ awk -F ',' '{split($1, name, " "); print name[2]}' contacts.csv
- Doe
- Smith
- Johnson
- Harris
- Brown
- White
- Green
- Black
- Blue
- Silver
 
## 7. Extract all email domains (part after the @ sign).
$ awk -F ',' '{split($5, email, "@"); print email[2]}' contacts.csv
- example.com
- gmail.com
- yahoo.com
- hotmail.com
- company.com
- domain.org
- domain.net
- webmail.com
- provider.com
- university.edu

---
 
## 8.	Extract all instances of the first name ‘David’ along with their full address (street and city).
$ awk -F ',' '$1 ~ /^David / {print $1", "$2", "$3}' contacts.csv
- David Green,  246 Birch St,  Uptown

---

## 9.	Find all entries where the phone number ends with ‘7’.
$ awk -F ',' '$6 ~ /7$/ {print $0}' contacts.csv
- John Doe, 123 Main St, Anytown, USA, john.doe@example.com, (555) 123-4567
- David Green, 246 Birch St, Uptown, USA, dgreen@domain.net, (555) 246-1357

---
 
## 10.	Extract all instances of first names that end with the letter 'e'.
$ awk -F ',' '{split($1, name, " "); if (name[1] ~ /e$/) print name[1]}' contacts.csv
- Jane
- Mike
- Alice

