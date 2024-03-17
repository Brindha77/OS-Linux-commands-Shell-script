# OS-Linux-commands-Shell-scripting
Operating systems Lab exercise
# Linux commands-Shell scripting
Linux commands-Shell scripting

# AIM:
To practice Linux Commands and Shell Scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Execute the following commands

### Step 3:

Testing the commands for the desired output. 

# COMMANDS:
### Create the following files file1, file2 as follows:
```
mkdir exp
cd exp
cat>f1
```
# OUTPUT :

# MORE :
```
cat f1|more
```
# OUTPUT :

# DISPLAY :
```
ls
```
# OUTPUT :


# LESS :
```
cat f1|less
```
# OUTPUT :

# TAIL :
```
tail f1
```
# OUTPUT :

# HEAD :
```
head f1
```
# OUTPUT :


# SORT :
```
sort f5
```
# OUTPUT :


# UNIQ :
```
uniq f5
```
# OUTPUT :


# SORT & UNIQ :
```
sort f5 | uniq
```
# OUTPUT :

# awk :
```
cat f6 |awk '{print $1}'
```
# OUTPUT :


# DISPLAY ALL :
```
ls -l
```
# OUTPUT :


# SORT.OUT :
```
ps | sort>f1sort.out
```
# OUTPUT :

# F1.OUT :
```
ps | sort > f1.out
```
# OUTPUT :

# SORT - FILE.OUT :
```
ps | sort > saveetha.out
ls
```
# OUTPUT :


# FILE.OUT :
```
cat saveetha.out
```
# OUTPUT :


# ECHO :
```
echo Saveetha Engineering College >> f3
cat f3
```
# OUTPUT :


# STOP :
```
cat<<stop>here.check.txt
```
# OUTPUT :

# START :
```
cat<<start>f5
```
# OUTPUT :

# VALUE :
```
x=7
echo $ x
```
# OUTPUT :

# DECLARE :
```
declare x=7
let y=4
set z=6
echo $x $y $z
```
# OUTPUT :


# EXPORT :
```
export z
echo $x $y $z
```
# OUTPUT :


# ADD VALUE :
```
expr $x+$y
```
# OUTPUT :


# MULTIPLY VALUE :
```
expr $x\*$y
```
# OUTPUT :



# RESULT:
The Commands are executed successfully.
