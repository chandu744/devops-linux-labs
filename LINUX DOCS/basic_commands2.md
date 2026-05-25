BASIC-COMMANDS-2:
=================
1) to use some admin cmds
   sudo respective_cmd ==> sudo ls /root  ( here it will ask the password)
2) to avoid entering password multiple times ==> use SUPERUSER ==> it will ask only once then it enters superuser shell
    sudo su
3) TARBALL : taking a folder with many files and compressing it into a single packed file
  python/
 ├── file1                ==>   python.tar
 ├── file2
 ├── file3
   
Windows → .zip
Linux → .tar.gz

python.tar.gz means:
=====================
python → original folder
.tar → packed
.gz → compressed smaller

syntax: tar  -czvf   outputfile.tar.gz   foldername  ===> tar -cf /home/bob/python/tar  /home/bob/reptile/snake/python

4)take the compressed .gz file and make it normal again in the same place
  gunzip filename.gz  ==> gunzip /home/bob/birds/eagle/eaglet.dat.gz
  
5) find the file(find==> only for searching the file)
   sudo find /folder -name file_name

6) redirect the file
   echo filepath > destpath
   
7) To search text/content inside files
    grep [options] "text" location
   ==> eg: grep -rl "173.23.12.234" /etc
   
8) save text into a file/To print/write text
    echo "text" > filename  ==> echo "hello" > notes.txt

9) Save normal output into file.
   command > file==> ls > data.txt
   
10) Save only errors into file.
    command 2> file  ==> python3 test.py 2> error.txt

 11) Read compressed .gz files without extracting.
     zcat file.gz > file  ==> zcat data.gz > output.txt
    
