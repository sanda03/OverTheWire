# exercice bandit


## **level 0 - 1**
ssh bandit0@bandit.labs.overthewire.org -p 2220  
-ls  
-cat readme
### the password
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

___

## **level 1 - 2**
ssh bandit1@bandit.labs.overthewire.org -p 2220  
-ls  
-cat ./-
### the password
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
___

## **level 2 - 3**
ssh bandit2@bandit.labs.overthewire.org -p 2220  
-ls  
-cat "spaces in this filename"
### the password
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
___

## **level 3 - 4**
ssh bandit3@bandit.labs.overthewire.org -p 2220  
ls  
cat ./inhere/.hidden
### the password
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

___

## **level 4 - 5**
ssh bandit4@bandit.labs.overthewire.org -p 2220  
ls  
cd inhere  
ls  
file ./*  
cat ./-file07
### the password
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
___

## **level 5 - 6**
ssh bandit5@bandit.labs.overthewire.org -p 2220  
ls   
cd inhere  
ls  
find -size 1033c  
cat ./maybehere07/.file2
### the password
P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
___

## **level 6 - 7**
ssh bandit6@bandit.labs.overthewire.org -p 2220  
find / -user bandit7 -group bandit6 -size 33c  
cat /var/lib/dpkg/info/bandit7.password
### the password
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
___

## **level 7 - 8**
ssh bandit7@bandit.labs.overthewire.org -p 2220  
ls  
grep "millionth" data.txt
### the password
TESKZC0XvTetK0S9xNwm25STk5iWrBvP
___

## **level 8 - 9**
ssh bandit8@bandit.labs.overthewire.org -p 2220  
ls  
sort data.txt | uniq -u
### the password
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
___

## **level 9 - 10**
ssh bandit9@bandit.labs.overthewire.org -p 2220  
ls  
strings data.txt | grep"==="
### the password
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
___

## **level 10 - 11**
ssh bandit10@bandit.labs.overthewire.org -p 2220  
ls  
cat data.txt | base64 -d
### the password
6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

___

## **level 11 - 12**
ssh bandit11@bandit.labs.overthewire.org -p 2220  
ls  
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
### the password
JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
___

## **level 12 - 13**
ssh bandit11@bandit.labs.overthewire.org -p 2220  
ls   
ls -al  
mkdir /tmp/mySanda123
cp data.txt    
/tmp/mySanda123  
cd /tmp/mySanda123  
/tmp/mySanda123$ file data.txt  
/tmp/mySanda123$ ls -al  
/tmp/mySanda123$ xxd -r data.txt data1  
/tmp/mySanda123$ file data1  
/tmp/mySanda123$ mv data1 data2.gz  
/tmp/mySanda123$ gzip -d data2.gz  
/tmp/mySanda123$ file data2    
/tmp/mySanda123$ mv data2 data3.bz2    
/tmp/mySanda123$ file data3.bz2  
/tmp/mySanda123$ bzip2 -d data3.bz2    
/tmp/mySanda123$ file data3  
/tmp/mySanda123$ mv data3 data4.gz    
/tmp/mySanda123$ file data4  
/tmp/mySanda123$ tar -xvf data4    
/tmp/mySanda123$ gzip -d data4.gz    
/tmp/mySanda123$ file data4  
/tmp/mySanda123$ tar -xvf data4  
/tmp/mySanda123$ file data5.bin  
/tmp/mySanda123$ tar -xvf data5.bin  
/tmp/mySanda123$ file data6.bin  
/tmp/mySanda123$ mv data6.bin data7.bz2  
/tmp/mySanda123$ file data7.bz2  
/tmp/mySanda123$ bzip2 -d data7.bz2  
/tmp/mySanda123$ file data7  
/tmp/mySanda123$ tar -xvf data7  
/tmp/mySanda123$ file data8.bin  
/tmp/mySanda123$ mv data8.bin data9.gz  
/tmp/mySanda123$ file data9  
/tmp/mySanda123$ mv data8.bin data9.gz  
/tmp/mySanda123$ gzip -d data9.gz  
/tmp/mySanda123$ file data9  
/tmp/mySanda123$ cat data9
### the password
wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
___

## **level 13 - 14**
ssh bandit14@bandit.labs.overthewire.org -p 2220  
ls  
cat sshkey.private  
ssh -i sshkey.private bandit14@localhost -p 2220  
cat /etc/bandit_pass/bandit14 
### the password 
fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq
___

## **level 15 - 16**
ssh bandit15@bandit.labs.overthewire.org -p 2220  
cat /etc/bandit_pass/bandit15  
jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt  
openssl s_client -connect localhost:30001  
### the password 
JQttfApK4SeyHwDlI9SXGR50qclOAil1 
____
## **level 16 - 17**
nmap -A localhost -p 31000-32000  
openssl s_client -connect localhost:31790  
echo "JQttfApK4SeyHwDlI9SXGR50qclOAil1" | openssl s_client -connect localhost:31790  
cd/tmp  
nano key-17.private  
chmod 600 key-17.private  
ssh -i key-17.private bandit17@localhost -p 2220  
### the password 
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----

____

## **level 17 - 18**
diff passwords.old passwords.new  
### the password
hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg
___ 

## **level 18 - 19**
ssh bandit18@bandit.labs.overthewire.org -p 2220 -t /bin/sh  
ls  
cat readme 
### the password 
awhqfNnAbc1naukrpqDYcF95h7HoMTrC
___
## **level 19 - 20**
ssh bandit19@bandit.labs.overthewire.org -p 2220   
./bandit20-do cat /etc/bandit_pass/bandit20 
### the password 
VxCazJaVykI6W36BkBU0mJTCM8rR95XT
___
## **level 20 - 21**
ssh bandit20@bandit.labs.overthewire.org -p 2220  
echo -n 'VxCazJaVykI6W36BkBU0mJTCM8rR95XT' | nc -l -p 3415 & 
### the password 
NvEJF7oVjkddltPSrdKEFOllh9V1IBcq
