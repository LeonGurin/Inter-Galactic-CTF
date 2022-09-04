# BEGINNER - LINUX7 - lool

**50 points**

Oh no! Turns out the hacker left another backdoor on the SSH server. It appears we have just a few too many crewmates on this system, so we need to eject the impostor!

What is the username of the user whose UID is 1001?

In Scope: Logged into the SSH machine.

Flag format: IGE{XXXXXXXXXX}

___

We can use the command `id` and provide our given id of `1001` and when entering it prints the user with this valid id:

`uid=1001(notAHacker) gid=1001(notAHacker) groups=1001(notAHacker)`

and so the flag is:

>IGE{notAHacker}
