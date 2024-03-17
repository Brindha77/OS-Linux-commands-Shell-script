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
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/e2e5ef52-cdce-4d31-9bda-8f15425ae82b)


### F1.OUT :
```
ps | sort > f1.out
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/93c2a564-2ef2-4a64-8f49-ccd63cc6b1a2)

### SORT - FILE.OUT :
```
ps | sort > saveetha.out
ls
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/f0da9efc-5ef6-4e24-bcd6-9ac9d03af8c4)

### FILE.OUT :
```
cat saveetha.out
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/5c50b5bd-a6df-4ea9-a4f2-479583adf188)

### ECHO :
```
echo Saveetha Engineering College >> f3
cat f3
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/f73abd26-6358-4c1c-8736-79b5493cffd9)

### STOP :
```
cat<<stop>here.check.txt
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/c3a9f28e-fe0e-4668-aa7f-df5e1fe7c5b8)

### START :
```
cat<<start>f5
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/e0d26eca-06c4-44b0-9dd8-9cd8b084e20d)

### VALUE :
```
x=7
echo $ x
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/c4533b2f-d625-478e-981a-593feeb68bbf)

### DECLARE :
```
declare x=7
let y=4
set z=6
echo $x $y $z
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/35002039-a1ea-430f-a669-127d4a82d6b3)

### EXPORT :
```
export z
echo $x $y $z
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/597e60c4-7fa6-400e-88c5-8af28cebad52)

### ADD VALUE :
```
expr $x+$y
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/bea62bff-e931-4713-84e0-33252b70e014)

### MULTIPLY VALUE :
```
expr $x\*$y
```
### OUTPUT :
![image](https://github.com/Brindha77/OS-Linux-commands-Shell-script/assets/118889143/8124a171-552f-409a-9f19-593c474dd863)



## RESULT:
The Commands are executed successfully.
