Figuring stuff out
Use: chmod: Changes the file permissions depending on the modifiers. X - makes file executeable. w - allows for file to be edited. r - allows reading of the file.
File permissions are shown like this: -rwxr-xr-x or -rw-r--r--. R = Read X = Executable w= writable. The permission string is the first three letters in the -rwxr- or -rw-r string in the previous example.
Now What each File does:
    0= PWD > Print working directory. #Prints the full path of the current working directory.
    1= ls > list. # list files in the current directory
    2= cd > change directory. #Used to change directory. name a directory to move into it, leave blank to go up to root, use "cd .." to go up one level
    3= ls -l > -l for long format lists. #all -* letters are modifiers to a command (* is placement for the letter). Also shows file permissions.
    4= ls -la > -a do not ignore entries starting with ".". # in ls -la its not its own modifer but rather its -l + -a, making a broader command that shows more infomation about each file as well as "hidden" files. List files and show permissions, user owner, group owner, last modified/created date
    5= ls -na > list digital files only. #
    6= mkdir /tmp/my_first_directory > makes directory like normal mkdir but is pathed so it creates it at other location not in current working directory.
    7= mv /tmp/betty /tmp/my_first_directory > moves a file from one location to another immediantly. 
    8= rm tmp/my_first_directory/betty > deletes the betty file specified to be inside the my_first_directory location.
