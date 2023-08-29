## Jerebu (Sederhana)

Permasalahan yang berulangkali berlaku ini mengakibatkan negara-negara serumpun ini menandatangani perjanjian berkaitan rentasan sempadan dari kebakaran hutan dan tanah gambut.

Flag : 3108{decodedcipher}

File: [Jerebu.png](https://ctf.bahterasiber.my/files/526f19087beda0458e7b5cd72fa1a55e/Jerebu.png?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NTd9.ZO2JDQ.HqTYfQRqzXNgP-o5qqCqeX_H5n0)

---

Inside the image file, we are given some music sheet:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/50a24e23-32c3-437a-9f7d-bcc4ab01901e)


Then I figured out the flag is encrypted using Music Sheet Cipher, then I tried to decode it using online [Music Sheet Cipher](https://www.dcode.fr/music-sheet-cipher)

This step may took a while since we need to decode it letter by letter, so I used my big brain to search for the header of the flag which is 3108:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/c5250bdc-94b2-4135-a663-1994e5c69c48)

Then, referencing the encrypted 3108 music sheet that I created, I continued to put in the music sheet and got the flag:
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/3398cd06-870f-49ba-870c-72e6ca96b593)

Flag
---
3108{P3RJ4NJNASEAN}
