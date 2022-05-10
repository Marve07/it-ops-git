# Linux commands 

# how to creat a file using the using the (mkdir):
  mkdir : creat a directory (mkdir test)
  ! mkdir test1 test2 test3 test4 
    -v = verbose: when you apply this command (mkdir -v)it tells you if the directory is created or not, but if you dont appluy that command it simply creat the directory without notifying you.
  ! -p: will creat both child and parent directory.
   --> eg mkdir class/c26/c27/c27
    so to creat both parent & child you have to pass the (-p) option. also to know if you have created the file or not you use the (-pv) option and it will tell you have created the various directories. and for you to see the directories you run the (ls command) and all will be displayed.
 tree: list the contents of directories in a tree-like format
 cd: change directory
 rmdir: remove or delete an empty directory 
 rm: it will remove a file or directory.
 rm -r: will remove a directory wether it is empty or not

! commands to creat a file:
   /touch --> (touch it ops.git)
   /echo --> display to you any information that you pass eg (echo class27), it will give you the exact mesage you passed 

! creat a file using the echo command: echo "what is your expectation?" > expect.txt

! cat: gives you the content of a file, eg cat expect.txt
! ls -- list the contents of a directory: has other options 
  /ls -l --> this gives you a  long list of files & directories everything
  /ls -lt--> long list base on reverse timie
  /ls -it --> long list base on time
  /ls -a --> shows hidden files
     cd .. = moves you to the closest directory
  ! examples of root dir:
     home, opt, etc, bin,tmp
     

 # linux commands mgt:
   host name: -->  gives the server's hostname
   hostname -i: --> gives private ip  
! how to change your host name:
        --> sudo "hostname"
! file mgt commands:
    grep: the grep command redirects the content or output of a file making it an input into another file e.g (grep cyprian list), cyprian was in a list file 

    pipe (|): the pipe command is just like a temporal storage

    sort: display the content of a file in alphabetical order eg (sort list)

! what is the grep and pipe command used for ? possible (IQS): the (grep) command is used to extract specific patterns from a file. while the (pipe) command generally act as a temporal storage 
 whereis: path to binary files
 su: switch user
 sudo su:  cypro
 df: report file system disk space usage, how much resources is been used
 df -h: display information in a way that can be humanly readable
 du: how much space each file is consuming
 free: checks memory usage
 uptime: this command tells you how long your server ha sbeen running.
 last: show listing of last logged in users.
