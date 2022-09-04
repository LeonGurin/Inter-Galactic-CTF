# BEGINNER - LINUX5 - Papers, please

**50 points**

On the provided SSH server, get the name of the group your user is a part of that stands out.

What’s the name of the group?

In Scope: Logged into the SSH machine.

Flag format: IGE{XXXXXXXXXXX}

___

Using the command `id` we get different information about our current user. 

We need to know what group he's in and luckily, it is displayed using the command: 

`uid=1000(alien) gid=1000(alien) groups=1000(alien),10000(spaceRogues)`

and so,

>IGE{spaceRogues}
