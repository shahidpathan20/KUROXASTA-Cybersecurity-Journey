## What is CLI?

CLI(Command line interface) is a way to interact with a computer by typing commands instead of clicking buttons.


example 



instead of 



opening folder with a mouse 



just type 



cd documents 


Why CLI is important?

<ul>
<li>
most Linux servers use CLI 
</li>
<li>
Cybersecurity tools often run in the terminal 
</li>
<li>
faster then clicking through menu 
</li>
<li>
helps in automation and scripting 
</li>
</ul>

## What is Terminal?


A Terminal is the application where you type Linux Commands 


## Important Navigation Commands

### pwd (print working directory )

example

/home/shahid


it means i am currently in shahid folder 


### ls(List Directory)


list Files and Folders 



shows what is inside current directory 



example 



documents <br />downloads <br />pictures 


### cd (Change Directory)


move from one folder to another 


cd documents


move back one folder 


cd ..


go to home directory  


cd \~

<h2>
Finding files 
</h2>

### Find


Used to search for files and directories 


find / -name file.txt

find=search command


/= search everywhere 



-name = search by filename 



example 



find / -name mission\_brief.txt 


<h2>
Reading Files 
</h2>

<h3>
cat 
</h3>

displays file contents.

cat file.txt


example 


cat mission\_brief.txt


output 



welcome to your first mission 


## System information commands

### whoami

shows the current logged-in user.


whoami 



example 



meaning 



shahid 


i am logged in as a user”shahid”

### uname


show Linux system information 


uname -a


display 


<ul>
<li>
kernel version 
</li>
<li>
Architecture 
</li>
<li>
System details 
</li>
</ul>

<h3>
df -h 
</h3>


shows disk space usage 



df -h 



df = disk free 


-h = human readable (GB,MB)

<h2>
most important commands summary 
</h2>

<table>
<colgroup>
<col width="174" />
<col width="174" />
</colgroup>
<tr>
<td>
command 
</td>
<td>
purpose 
</td>
</tr>
<tr>
<td>
pwd 
</td>
<td>
show current location 
</td>
</tr>
<tr>
<td>
ls
</td>
<td>
list files/folder 
</td>
</tr>
<tr>
<td>
cd 
</td>
<td>
change directory 
</td>
</tr>
<tr>
<td>
cd ..
</td>
<td>
go back one folder 
</td>
</tr>
<tr>
<td>
cd \~
</td>
<td>
go to home directory 
</td>
</tr>
<tr>
<td>
find 
</td>
<td>
search files 
</td>
</tr>
<tr>
<td>
cat 
</td>
<td>
read files contents 
</td>
</tr>
<tr>
<td>
whoami 
</td>
<td>
show current user 
</td>
</tr>
<tr>
<td>
uname -a 
</td>
<td>
shows system information
</td>
</tr>
<tr>
<td>
df -h 
</td>
<td>
show disk usage 
</td>
</tr>
</table>

---
