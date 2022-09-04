# BEGINNER - LINUX2 - Finding Hidden Secrets

**50 points**

You’re in. It’s time to find secrets that may have been hidden. You can use a command to find hidden files and folders.

What is the hidden file that you find?

In Scope: Logged into the SSH machine.

Flag format: XXX{.XXXXXX_XXXXXX.XXX}

___

Typing `ls -la` reveals all the hidden files in the directory.

```bash
total 56
drwxr-xr-x 1 alien alien 4096 Sep  3 16:42 ./
drwxr-xr-x 1 root  root  4096 Sep  3 16:43 ../
-rw-r--r-- 1 alien alien  220 Apr  4  2018 .bash_logout      
-rw-r--r-- 1 alien alien 3771 Apr  4  2018 .bashrc
-rw-r--r-- 1 alien alien  807 Apr  4  2018 .profile
-rw-r--r-- 1 root  root    19 Sep  1 14:36 .secret_coords.txt
drwxr-xr-x 1 root  root  4096 Sep  3 16:42 .ssh/
drwxr-xr-x 1 root  root  4096 Sep  1 20:05 PWN1/
drwxr-xr-x 1 root  root  4096 Sep  1 20:42 PWN2/
drwxr-xr-x 1 root  root  4096 Sep  3 16:42 PWN3/
drwxr-xr-x 1 root  root  4096 Sep  1 21:06 PWN4/
drwxr-xr-x 2 root  root  4096 Sep  3 15:55 PWN5/
drwxr-xr-x 1 root  root  4096 Sep  1 23:24 RE1/
-r-------- 1 admin root    32 Sep  1 14:45 level_up.txt
```

we notice a txt file named `.secret_coords.txt`

which is also the flag:

> IGE{.secret_coords.txt}


