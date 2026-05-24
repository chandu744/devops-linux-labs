BASIC COMMANDS: 
===============
1)show you your home directory?==> echo $HOME
    bob@caleston-lp10:~$ echo $HOME
    /home/bob
2) what type of cmd is git?
    file
3) create a directory 
    mkdir dir_name
4) create all folders at once or evn if the parent folder misses it automatically created
    mkdir -p /home/bob/fish/salmon 
5) move folder from one directory to other 
    mv src_folder_path  destination_folder_path 
      ==> eg: mv /home/bob/reptile/frog  /home/bob/amphibian
6) rename the folder 
   mv path_with_oldname path_with_newname 
        ==> eg: mv /home/bob/reptile/snake  /home/bob/reptile/crocodile
7) remove folder along with its content 
    rm -r path 
    ==>eg: rm -r /home/bob/reptile ( this also removes the sub folders inside that reptile folder)
    
