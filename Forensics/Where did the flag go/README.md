# BEGINNER - FORENSIC4 - Where did the flag go?

**50 points**

I accidentally lost the flag but I think it’s somewhere in this picture…

Can you find the flag?

Flag format: IGE{XXX_XXXXX_XXXXX}

_Given:_ [findtheflag.jpg](https://github.com/LeonGurin/Inter-Galactic-CTF/tree/main/Forensics/Where%20did%20the%20flag%20go)

___

Using strings on the file and searching IGE:

`strings findtheflag.jpg | grep IGE`

we get one result and its the flag:

>IGE{why_h3llo_th3re}

