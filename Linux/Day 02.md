**Day 02 - Linux**

**--------------------------**

To know which OS and Flavour

cat /etc/os-release



To know the details of a specific command

man <CommandName>



To know the path of any package

whereis <PackageName>



$ ----> You are normal user

\# ----> You are root user

~ ----> You are in /home/ec2-user path



cd .. 

or

cd /home/ec2-user/	



While working with switching directories, we have 2 paths;

Absolute path --- it means, we should give the complete path in a single command

Relative path --- it means we need to go inside a specific directory by using cd .. cd /kastro



Copying the content from one file to another file

cp <File1Name> <File2Name>



To see the list of commands executed so far

history



To clear the history

history -c



To know in which the details of specific command is available

which <CommandName>



To work with calculator in Linux OS

sudo yum install bc -y

bc

Enter any mathematical operations

You will see the output



To know the hostname of VM

hostname -i



To set the hostname of server
sudo hostnamectl set-hostname kastro



To know from how long the instance is running

uptime



**-------------------------------------------------**

**Advanced Commands - Level 1**

**-------------------------------------------------**

To see the list of softwares/packages that are installed

yum list available

dnf list installed



To remove a dir which is not empty

rm -rf <Dir.Name>



To list the files and directories in alphabetical order

ll (or) ls -l



ls -lr



ls -al (0r) ls -a



ls -lh



cat

tac



SORT

sort <FileName>

sort kiran.txt | uniq



COMPARE



FIND

find / -name kastro.txt

find /root/ -name kiran.txt



MOVE

mv <CurrentFileName> <NewFileName>



cat -n <FileName>



HEAD and TAIL





shift + a

shift + i

shift + o

shift + g



:set number

:line-number

yy

p

dd

u

control+r



:%d



GREP

Global Regular Expression Print

It is used to search for a word

































**Linux Directory Structure**





