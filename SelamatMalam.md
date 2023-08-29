## Selamat Malam (Sederhana)

Dalam hening malam ditemani sang bayu dan cahaya purnama, ku dengar alunan sayu dari kejauhan.

Dengarlah senandung dari jiwaku yang merintih untuk difahami, walau jarak kita terlalu jauh untuk bersua kembali.

File: 
[Senandung_Lena.txt](https://ctf.bahterasiber.my/files/f7f8c81d1e5fb42d1c8dd7c960af4cb8/Senandung_Lena.txt?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6Mjl9.ZO2F5g.DeOP6XTY0n9rdbB2b823qgp3R9s)

Hint:
Dalam rangkap kataku, ada terselit sebuah mesej untukmu dariku, walau ada jarak antaranya.

---

Upon opening the text file, we can see strings that are 'poem-like' spacing and it was encrypted wih Atbash Cipher, so I decrypted it using an online [Atbash Cipher Decoder](https://www.dcode.fr/atbash-cipher)

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/6d22eef1-8cb5-45a1-8983-0f26773c129e)

Through the decrypted text file, it seems to be a poem that have few characters are intendedly left with Uppercase. Then I copied all of the Uppercase letters in the poem and got the flag :
3108MALAYSIAAMAN

Flag
---
3108{MALAYSIAAMAN}
