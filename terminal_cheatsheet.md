# Terminal cheat sheet

This adorable cheat sheet contains a brief overview of some commonly used terminal elements. It is by no means extensive, or even good really. But here it is anyway.

| Syntax         | What it actually does |
| ------ | ------ |
| ```pwd``` | prints the current directory |
```ls``` | list things out contents of folder you’re in. 
CTRL + l | clears the screen, does not delete it. Just scroll.
```ls -l``` | check permissions on file of who can edit
```ls -a``` | a stands for all. Shows hidden files and folders, including stuff we don’t want average user to mess with.
Ls -al/-la | adding flags together
Cd | (wherever you want to do) e.g. ```cd Documents``` . If you just put in cd it will take you back to the home directory wherever you are. Type cd, first letter you want, then TAB key to get suggestions. Use TAB again to get suggestions for files that folder
Cd .. | (make sure you include a space) to go back to parent element. Parent element is only ever 1 thing. 
Mkdir + (NAME) | make directory. e.g. mkdir my_directory
Touch + SPACE + NAME | e.g. touch my_file.txt = make a file
Open + space + file | Opens up editor e.g. my_directory open my_file.txt
mv | move OR change the name of a file. Change the name e.g. ```my_directory mv my_file.txt my_renamed_file.txt```. Move the file e.g. ```my_directory mv my_renamed_file.txt ~/Documents```
rm | Deletes files e.g. ```my_directory rm my_other_file.txt``` . Does not go to trash, things are gone for good! 
rm -rf ~| UTTERLY CURSED. NEVER TYPE THIS EVER INTO YOUR COMPUTER.