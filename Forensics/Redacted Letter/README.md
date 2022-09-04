# BEGINNER - FORENSIC2 - Redacted Letter

**50 points**

We think one of the aliens is pretending to be a human and meeting with an Earth company! But when we intercepted their letter, all the important content was redacted.

Can you find a way to view the redacted information? The flag is the room number of the room they are meeting in wrapped in IGE{}.

Flag format: IGE{XX}

_Given:_ [Letter.pdf](https://github.com/LeonGurin/Inter-Galactic-CTF/blob/main/Forensics/Redacted%20Letter/Letter.pdf)

___

Using the same exact trick as the last challenge gets us:

```
Crystal Shanda Leer
123 Coolkids Street
Techtown, AA 12345
(123) 456-7890
crystal@coolestmail.com
4th September 2045
Felix Cited
CEO, Company of Awesomeness
123 Business Road
Worktown, AA 12345
Dear Mr Cited,
I hope you are doing well. During our last meeting, we talked about the new
technological developments uncovered by my team’s research and discussed
how it could affect your company. My team is seriously considering accepting
the proposal you made us and would like to meet with you on September 7th,
2045 to discuss further details.
Please be our guest at 842 Secret Road in room 53 on the 22nd floor.
We greatly look forward to meeting with you.
Sincerely,
Crystal Shanda Leer
```

and so the flag is:

>IGE{53}
