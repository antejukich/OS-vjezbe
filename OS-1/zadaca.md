
Zadatak 1
    1.1 pwd
    1.2 ls
    1.3 mkdir vjezba1 && cd vjezba1
    1.4 touch README.md
    1.5 cd ..

Zadatak 2
    2.1 mkdir vjezba2 && touch vjezba2/file.txt
    2.2 cp vjezba2/file.txt vjezba2/file_copy.txt
    2.3 ls vjezba2
    2.4 cd vjezba2 && rm file.txt && cd ..
    2.5 rmdir vjezba2 // nije moguce izbrisati direktorij jer nije prazan - rmdir: vjezba2: Directory not empty

Zadatak 3
    3.1 mkdir vjezba3 && mkdir vjezba3/backup
    3.2 touch vjezba3/notes.txt && touch vjezba3/todo.txt && touch vjezba3/script.sh
    3.3 cp vjezba3/notes.txt vjezba3/todo.txt vjezba3/script.sh vjezba3/backup/
    3.4 rm vjezba3/script.sh && ls vjezba3
    3.5 mkdir vjezba3/backup/$USER
    3.6 mv vjezba3/backup/notes.txt vjezba3/backup/todo.txt vjezba3/backup/script.sh vjezba3/backup/$USER/

Zadatak 4
    4.1 mkdir vjezba4 && mkdir vjezba4/subfolder
    4.2 touch vjezba4/$HOSTNAME
    4.3 mv vjezba4/$HOSTNAME vjezba4/$USER
    4.4 mv vjezba4/$USER vjezba4/subfolder/
    4.5 rm /Users/ajukic/Projects/2526_FIPU/OS-vjezbe/OS-1/vjezba4/subfolder/$USER

Zadatak 5
    5.1 mkdir vjezba5 && touch vjezba5/$RANDOM.num
    5.2 ls vjezba5
    5.3 cp vjezba5/22288.num vjezba5/backup.num
    5.4 mkdir backup
    5.5 mv vjezba5/backup.num backup/

Zadatak 6
    6.1 mkdir /Users/ajukic/Documents/vjezba6
    6.2 cd /Users/ajukic/Documents/vjezba6 && mkdir scripts && touch OS_script.md notes.txt
    6.3 mv OS_script.md scripts/
    6.4 mv notes.txt todo.txt
    6.5 cd scripts && rm ../todo.txt