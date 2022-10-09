# Linux
### Linux Commands

Find current working directory:
```
pwd
```
List things in directory:
```
ls
```
Change directory:
```
cd /Dir/Dir_name
```
Clear the terminal:
```
clear
```
List hidden files:
```
ls -a
```
Create new file in terminal:
```
touch file.txt
```
Read file content:
```
cat file.txt
```
Create Directory:
```
mkdir directory_name
```
Create nested Directory using -p flag:
```
mkdir -p dir3/dir2/dir1/directory_name
```
Move File:
```
mv file_name directory
mv file.txt Downloads/files
```
Remove File:
```
rm file_name
```
Remove Directory:
```
rm directory_name
```
To find use of specific command:
```
man command   E.g. man rm
```
Remove directory and their contents recursively:
```
rm -r downloads/
```
Copy file:
```
cp source destination
```
use w/who to find uptime, how many users has logged in:
```
w
who
```
To find and monitor running processes:
```
top
```
Network- To find out what ports are open and listening:
```
sudo netstat -tupln
```
Create new file using VI editor:
```
vi test.file
```
Insert data press i and write content:
```
i
```
To save and quit from vi press esc and then :
```
:wq
```
Print "Hello World" message in terminal :
```
echo "Hello World"
```
Print std Output to some file :
```
echo "Hello World" 1> somefile.txt
```
Print std Output to some file but this override the existing contents :
```
echo "Hello World" > somefile.txt
```
Redirecting standart output and append data in existing file use ">>" :
```
echo "Hello World" >> somefile.txt
```
To Redirect standard error use 2> :
```
cat nonExistingFile.txt 2> somefile.txt
```
Redirect input using <, Here we are mailing error.txt to the user palak:
```
mail -s This is errror file" palak < error.txt
```
Use grep for searching patterns in files
```
cat somefile.txt | grep Thanks
```
Cut file using delimiter and find fields
```
cat somefile.txt | cut -d: f1
```
Sort the file contents in alphabatical orders, ignore the leading whitespace using b case-insesitive f
```
cat somefile.txt | sort -bf
```
Search somethig in directory
```
grep search_term ./*
```
