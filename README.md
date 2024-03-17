# OS-Linux-commands-Shell-scripting
Operating systems Lab exercise
# Linux commands-Shell scripting
Linux commands-Shell scripting

## AIM:
To practice Linux Commands and Shell Scripting

## DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Execute the following commands

### Step 3:

Testing the commands for the desired output. 

## COMMANDS:
### Create the following files file1, file2 as follows:
```
mkdir exp
cd exp
cat>f1
```
### OUTPUT :
![1](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/ccb4e2bc-0ebc-473e-8f12-d94d15c0144d)

### MORE :
```
cat f1|more
```
### OUTPUT :
![2](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/5cce0628-b80c-42bf-af32-60e79ab2bab5)

### DISPLAY :
```
ls
```
### OUTPUT :
![3](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/3d010db7-32bb-473f-8cce-1704d12053c2)


### LESS :
```
cat f1|less
```
### OUTPUT :
![4](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/18e9313b-affd-41f1-bbee-84bf41457bbc)

### TAIL :
```
tail f1
```
### OUTPUT :
![5](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/b5a85dd6-a9bf-4eb0-a3d1-2a5ada68c11a)

### HEAD :
```
head f1
```
### OUTPUT :
![6](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/29592625-815c-4c4c-82d8-fc8d6f8d6edc)


### SORT :
```
sort f5
```
### OUTPUT :
![7](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/bafde508-4dfd-4013-8b41-c5707945b73a)


### UNIQ :
```
uniq f5
```
### OUTPUT :
![8](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/488f1011-43b4-456d-9f76-8ade2a1c6d04)


### SORT & UNIQ :
```
sort f5 | uniq
```
### OUTPUT :
![9](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/26fa471e-b9be-4ca5-8fcf-086ae37c86b5)

### awk :
```
cat f6 |awk '{print $1}'
```
### OUTPUT :
![10](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/e28852e7-d18e-48c3-a8a6-fe95ad207484)


### DISPLAY ALL :
```
ls -l
```
### OUTPUT :
![11](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/f940be79-8518-44e3-8448-a29f43002292)


### SORT.OUT :
```
ps | sort>f1sort.out
```
### OUTPUT :

### F1.OUT :
```
ps | sort > f1.out
```
### OUTPUT :

### SORT - FILE.OUT :
```
ps | sort > saveetha.out
ls
```
### OUTPUT :


### FILE.OUT :
```
cat saveetha.out
```
### OUTPUT :


### ECHO :
```
echo Saveetha Engineering College >> f3
cat f3
```
### OUTPUT :


### STOP :
```
cat<<stop>here.check.txt
```
### OUTPUT :

### START :
```
cat<<start>f5
```
### OUTPUT :

### VALUE :
```
x=7
echo $ x
```
### OUTPUT :

### DECLARE :
```
declare x=7
let y=4
set z=6
echo $x $y $z
```
### OUTPUT :


### EXPORT :
```
export z
echo $x $y $z
```
### OUTPUT :


### ADD VALUE :
```
expr $x+$y
```
### OUTPUT :


### MULTIPLY VALUE :
```
expr $x\*$y
```
### OUTPUT :



## RESULT:
The Commands are executed successfully.
