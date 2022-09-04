# BEGINNER - FORENSIC1 - Say Hello

**50 points**

We intercepted this message, and it seems very suspicious but there is no secret message to be seen. Or is there?

Find the hidden message! Then submit the last word of the secret message wrapped in IGE{} as the flag.

Flag format: IGE{XXXXX}

_Given:_ [Hello.pdf](https://github.com/LeonGurin/Inter-Galactic-CTF/blob/main/Forensics/Say%20Hello/Hello.pdf)

___

One way to hide info inside a pdf file is to make the text the same color as the background.

And so, to extract all the text we can `Ctrl+A` the text and paste it:

```
Hello!
What? A secret message? Yes, it’s “Be at 987 Hotel St at exactly 9:15pm and stand next to the
stop sign. Bring the money.”
. . . who, me?
Nah. . .
Everything is normal.
Everything is fine.
Don’t look at me.
```

and so the last word is "money"

>IGE{money}
