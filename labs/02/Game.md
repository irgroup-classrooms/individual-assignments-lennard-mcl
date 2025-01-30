```
lenna@Lennard MINGW64 ~
$ cd

lenna@Lennard MINGW64 ~
$ /c/Users/Robin/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
bash: /c/Users/Robin/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance: Is a directory

lenna@Lennard MINGW64 ~
$ $ cd /home/your_username/Downloads/bashcrawl/entrance
bash: $: command not found

lenna@Lennard MINGW64 ~
$ cd /c/Users/Robin/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ ^[[200~$ cd /home/your_username/Downloads/bashcrawl/entrance
bash: $'\E[200~$': command not found

lenna@Lennard ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ $ cd /home/your_username/Downloads/bashcrawl/entrance
bash: $: command not found

lenna@Lennard ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ $ cd /home/your_username/Downloads/bashcrawl/entrance
bash: $: command not found

lenna@Lennard ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ cd /home/your_username/Downloads/bashcrawl/entrance
bash: cd: /home/your_username/Downloads/bashcrawl/entrance: No such file or directory

lenna@Lennard ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ cat scroll

It is pitch black in these catacombs.
You have a magickal spell that lists all items in a room.

To see in the dark, type:     ls
To move around, type:         cd <directory>

Try looking around this room.
Then move into one of the next rooms.

EXAMPLE:

$ ls
$ cd cellar

Remember to cast ``ls`` when you get into the next room!


lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ ls
cellar/  dis08/  scroll

lenna@Lennard ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance
$ cd cellar

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar
$ ls
armoury/  scroll  treasure*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar
$ ls
armoury/  scroll  treasure*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar
$ cd treasure
bash: cd: treasure: Not a directory

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar
$ scroll treasure
bash: scroll: command not found

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar
$ cd armoury

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury
$ ls
chamber/  potion*  scroll  treasure*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury
$ cd chamber

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ ls
scroll  spell*  statue*  treasure*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ cd spell
bash: cd: spell: Not a directory

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ ls spell
spell*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ ls statue
statue*

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ cat scroll

# You seem to have reached the end of this hall.
#
# Turn back and try another path.
#
# Remember, to back track one directory, you type:
#
# cd ..
#
# If you are drawing a map of your progress,
# you can always get the name of your working
# directory with this command:
#
# pwd


lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$ ^C

lenna@Lennard MINGW64 ~/Documents/TH-Köln/Semester_3/DIS08_DatenmodellierungData_Modelling/bashcrawl-stable-2024.02.09/entrance/cellar/armoury/chamber
$
```