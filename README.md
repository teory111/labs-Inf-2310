# lab01
laboratorio de estructura de datos

level 0

1. ssh bandit0@bandit.labs.overthewire.org -p 2220

# level 0->1:

1. ls -alps
2. cat readme
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

# level 1->2:

1. ls -alps
2. cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx 

# level 2->3:
1. ls -alps
2. cat spaces\ in\ this\ filename
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

# level 3->4:
1. ls -alps
2. cd inhere/
3. ls -alps
4. cat ...Hiding-From-You 
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

# level 4->5:

1. ls -alps
2. cat ./-file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

# level 5->6:

1. ls
2. find . -size 1033c cat .file2
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

# level 6->7:

1. ls -alps
2. find / -user bandit7 -group bandit6
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

# level 7->8:

1. ls -alps
2. cat data.txt strings data.txt | grep "millionth" //busco la linea de texto que contenia "millionth" en data.txt
millionth dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

# level 8->9:

1. ls -alps
2. sort data.txt | uniq -c //ordeno el data.txt y agrupo las copias
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

# level 9->10:

1. ls -alps
2. strings data.txt | grep '=' //strings busca las cadenas imprimibles y grep busca algo en especifico, en este caso '='
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

# level 10->11:

1. ls -alps
2. base 64 -d data.txt //base -d decodifica
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

# level 11->12:

1. ls -alps
2. cat data.txt
// cyberchef rot 13
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

# level 12->13:

1  mkdir /tmp/teory
    2  cp data.txt /tmp/teory
    3  cd /tmp/teory
    4  ls
    5  xxd -r data.txt > data
    6  file data
    7  history
    8  mv data file.gz
    9  gzip -d file.gz
   10  ls
   11  file file
   12  mv file file.bz2
   13  bzip2 -d file.bz2
   14  file file
   15  mv file file.gz
   16  gzip -d file.gz
   17  file file
   18  mv file file.tar
   19  tar xf file.tar
   20  ls
   21  file data5.bin
   22  rm file.tar
   23  rm data5.txt
   24  rm data.txt
   25  ls
   26  file data5.bin
   27  mv data5.bin data.tar
   28  tar xf data.tar
   29  ls
   30  file data6.bin
   31  mv data6.bin data.bz2
   32  bzip2 -d data.bz2
   33  file data
   34  mv data data.tar
   35  tar xf data.tar
   36  ls
   37  file data8.bin
   38  mv data8.bin data.gz
   39  gzip -d data.gz
   40  ls
   41  file data
   42  cat data
   43  history

FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

# level 13->14:

1. ls
2. ssh -i sshkey.private bandit14@localhost -p 2220
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

# level 14->15:

1- nc localhost 30000
   MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

# level 15->16:

1. cat /etc/bandit_pass/bandit15
2. ncat --ssl localhost 30001
   8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx

# level 16->17:

    1  nmap localhost -p 31000-32000
    2  nc localhost 31790
    3  nc --ssl localhost 31790
    4  ncat --ssl localhost 31790
    5  history
    -----BEGIN RSA PRIVATE KEY----- MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama +TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT 8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM 77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3 vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY= -----END RSA PRIVATE KEY-----
    6  mkdir /tmp/choclo
    7  cd /tmp/choclo
    8  nano choclo
    9  chmod 600 choclo
   10  cat choclo
   11  ssh -i choclo bandit17@bandit.labs.overthewire.org -p 2220

# level 17->18:

1. diff passwords.old passwords.new
   
x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
---
ktfgBvpMzWKR5ENj26IbLGSblgUG9CzB

# level 18->19:

1. ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8

# level 19->20:

    1  ./bandit20-do
    2  ./bandit20-do id
    3  ./bandit20-do ls
    4  ./bandit20-do cat /etc/bandit_pass/bandit20
    5  history
    
0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO

# level 20->21:
    1  nc -lvp 9999
    1  ./suconnect
    2  ./suconnect 9999

EeoULMCra2q0dSkYj561DX7s1CpBuOBt

# level 21->22:

 1  ls
    2  cd /etc/cron.d/
    3  ls
    4  cat cronjob_bandit22
    5  cat /usr/bin/cronjob_bandit22.sh
    6  cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q

# level 22->23:

 1  cd /etc/cron.d
    2  ls
    3  cat cronjob_bandit23
    4  cat /usr/bin/cronjob_bandit23.sh
    5  echo I am user bandit23 | md5sum | cut -d ' ' -f 1
    6  cat /tmp/8ca319486bfbbc3663ea0fbe81326349 

  0Zf11ioIjMVN551jX3CmStKLYqjk54Ga

# level 23->24:

   1  ls -la /etc/cron.d/
   2  cat /etc/cron.d/cronjob_bandit24
   3  cat /usr/bin/cronjob_bandit24.sh
   4  cd /var/spool/bandit24/foo
   5  echo "cat /etc/bandit_pass/bandit24 > /tmp/socorro.txt" > socorro.sh
   6  chmod 777 socorro.sh
   7  cat /tmp/socorro.txt

gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8

# level 24->25:

  1  nc localhost 30002
    2  mkdir /tmp/brute
    3  mkdir /tmp/bruto
    4  cd /tmp/bruto
    5  nano list.txt
    6  la
    7  cat list.txt | nc localhost 30002
    8  rm list.txt
    9  nano script.sh
   10  ls
   11  chmod +x script.sh
   12  ls
   13  ./script.sh
   14  cat list.txt | nc localhost 30002

 iCi86ttT4KSNe1armKiwbQNmB3YJP3q4

# level 25->26:
//minimizar ventana

1 ssh bandit26@localhost -i bandit26.sshkey -p2220
2 v
3 :e /etc/bandit_pass/bandit26
s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ

# level 26->27:

 1  ls
    2  file bandit27-do
    3  ls -l bandit27-do
    4  ./bandit27-do
    5  ./bandit27-do id
    6  ./bandit27-do cat /etc/bandit_pass/bandit27

upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB

# level 27->28:

1  mkdir /tmp/codew
    2  cd /tmp/codew
    3  git clone ssh://bandit27-git@localhost/home/bandit27-git/repo
    4  git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo
    5  ls
    6  cd repo
    7  ls
    8  cat README

Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN

# level 28->29:

 1  mkdir /tmp/code
    2  cd /tmp/code
    3  git clone ssh://bandit28-git@localhost:2220/home/bandit28-git/repo
    4  ls
    5  cd repo
    6  cat README.md
    7  git log
    8  git show 3621de89d8eac9d3b64302bfb2dc67e9a566decd
    9  git show 817e303aa6c2b207ea043c7bba1bb7575dc4ea73
   10  git log
   11  git show 3621de89d8eac9d3b64302bfb2dc67e9a566decd

4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7

# level 29->30:

1  mkdir /tmp/29
    2  cd tmp/29
    3  cd /tmp/29
    4  ls
    5  cd repo
    6  ls
    7  cat README.md

   qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL

# level 30->31:

 1  mkdir /tmp/12
    2  cd /tmp/12
    3  git clone ssh://bandit30-git@localhost:2220/home/bandit30-git/repo
    4  cat /etc/bandit_pass/bandit30
    5  git clone ssh://bandit30-git@localhost:2220/home/bandit30-git/repo
    6  cd repo
    7  ls
    8  cat README.md
    9  git log
   10  git branch -a
   11  git tag
   12  git show secret

 fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy

# level 31->32:



