# INTERMEDIATE - FORENSIC6 - Traffic In The Clear

**100 points**

We got this capture by listening in over the interstellar network which isn’t as secure as people may think. In any event, there is a little bit of content in here that could be useful to us in our explorations, think you can warm up with this challenge?

Can you find the flag?

Flag format: IGE{XXXX_XXXX_XXXXXXXXXX_XX_XXX_XXXX}

_Given:_ [file.pcapng](https://github.com/LeonGurin/Inter-Galactic-CTF/tree/main/Forensics/Traffic%20In%20The%20Clear)

___

Just using strings gets us the file:

`strings file.pcapng | grep IGE`

>IGE{PCAP_FILE_EXTRACTION_IS_NOT_HARD}
