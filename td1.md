# TD1
## Exercise 1 : Move around
### 1. 

```cd / ```

### 2. 

```ls```

### 3.
```pwd ```

### 4. 
```mkdir test``` 
##### It doesn't work

### 5. 
```cd home```

### 6. 
```cd timlongykaaa```

### 7.
``` cd ..```

### 8. 
```cd .. ```

### 9.
```cd ~```

### 10. 
```mkdir test```

### 11.
```cd test```

### 12. 
```pwd```


## Exercise 2 : Create, rename, copy, delete

### 1.

```cd ~```

### 2.

```pwd```

### 3.

```mkdir linux_ex_1```

### 4.

```cd linux_ex_1/```

### 5.

```touch tim_longyka.txt```

### 6.

```mkdir notes```

### 7.

```mv tim_longyka.txt notes```

### 8.

``` mv tim_longyka.txt tim_longyka_2023.txt```

### 9.

```cp -r notes notes_2022```

### 10. 

``` rm -r -v notes```


## Exercise 3:
### 1 to 5 
```touch script_1.sh
 nano script_1.sh
 echo "Script running please wait..." > script_1.sh
 echo "Done." >> script_1.sh
 Ctrl + X
 cat script_1.sh
 sh script_1.sh 
 ```


## Exercise 4.1 : 
### 1.

```touch credentials
   echo "I am 33 years old" > credentials
   cat credentials
   ls -l credentials
   ```

### 2.

```chmod 444 credentials
   ls -l credentials
   echo "I live in Paraguay" >> credentials
   cat credentials
   ```
   
### 3. 

```chmod 666 credentials
   ls -l credentials
   echo "I have 1 daughter and 2 sons" >> credentials
   cat credentials
   ```
   
### On the same file
#### 1.

```chmod u+x credentials
   ls -l credentials
   ```

#### 2.
```chmod o-r credentials
   ls -l credentials
   ```
   
#### 3. 
```chmod 777 credentials
   ls -l credentials
   ```
   
## Exercise 4.2 :

### 1. 
```cd /```

### 2. 
```sudo su 
   touch .private_file
   echo "blablabla" > .private_file
   cat .private_file
   ls -a
   ```
   
### 3.
```chmod u+w .private_file
   echo "blablablablabla" >> .private_file
   cat .private_file
   ```
   
### 4. 
```sudo chmod u+w .private_file
   echo "bla" >>.private_file
   cat .private_file
   ```

### 5. 
```chmod 777 .private_file
   cat .private_file
   ```
   
## Exercise 4.3 :
### 1 to 3

```sudo chmod 666 .private_file
   sudo chown timlongykaaa .private_file
   chmod 666 .private_file
   ```
   
## Exercise 4.4 :

```
sudo apt update
sudo apt upgrade
sudo apt install cmatrix
cmatrix
sudo apt install tmux
tmux
echo "Hello Sesssion 0"
cmatrix
tmux new
echo "Hello session 1"
tmux ls
tmux a -t 0
tmux a -t 1
tmux ls
tmux kill-server
tmux ls
```

##### to detach : Ctrl + b,d

   

   


