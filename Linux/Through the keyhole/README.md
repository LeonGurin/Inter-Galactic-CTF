# BEGINNER - LINUX6 - Through the keyhole

**50 points**

Through this expedition, we have identified some indicators of compromise (IoCs) on this server. Signs point to a hacker who left an SSH public key as a backdoor, but can you dig into it?

What is the username of the user who created the key?

In Scope: Logged into the SSH machine.

Flag format: IGE{XXXXXXXXX}

___

Using `ls -la` again we can notice a `.ssh` directory.

Cd-ing into it there lies a file named `authorized_keys`. 

Using cat to display it, gives us:

`ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC2dDdnp9sWy/KUljSvOOY6Kzo23L4a08SVyT2fH7EHsCHZYCQjFcsoceAf0MDgjCXprdWBWwFk28pu7zIMboj19lRzwQRljVOKs3qc8WR6drN7u/szcyycFBi1aODxOMpFLx6U4bltFZHKhMk/TYNB4bGvMXzT3k96WlJakJ5eG5Qrs5WYCj9kjahUASZm6Ri3RqVDHyaJB+C1kf2E4mZdqUjm+lrc2bcg5MMfWUQNnsUsWpNTNN3JhEWb7KCo24NActV2Kaje6M+jiddankrDMcd0Ge6N+ygGM4mHCDelHnM2/ixd6M+gKeo5o/3Pq7TXSiQa+jg7E53jaGbQYRsyI3gv8y0BRemo8EyIWEcaeW1qsj70jHmO1KYZFDbohVWX4TrwgoHqpdt/L4haiA8YqxJLbNfer8uY7+BXUfgMDDCID5rtUoMRKuR77P8uHS2LwEQDeykIeE9qGhshqj9yk4eK0vQr6aw4ujhEfUndVamhNIgatf4eZ+xzeO9Qb7M= hackerman`

and there we can notice a username `hackerman`.

>IGE{hackerman}

