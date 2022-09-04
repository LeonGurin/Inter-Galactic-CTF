# BEGINNER - LINUX3 - Reading Secrets

**50 points**

Now that you’ve located the file, can you rediscover its contents?

What’s the flag?

In Scope: Logged into the SSH machine.

Flag format: IGE{XX.XX, -XX.XX}

___

We just need to cat the contents of the file we found in the last challenge with this command:

`cat .secret_coords.txt`

and the flag is:

>IGE{28.46, -80.53}