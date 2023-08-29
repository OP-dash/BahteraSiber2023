## Mesej Dalam Botol (Sederhana)
Arjuna telah mencampakkan sebuah botol lama yang mengandungi sehelai surat di dalamnya. Botol ini hanya dapat dibuka dengan sebuah "jampi" yang merupakan nama serta tahun pembinaan bahtera pelayarannya.

Bolehkah anda menemuka jawapannya?

Format jampi : NAMA_TAHUN

Files:
[Bahtera_si_pelayar.jpg](https://ctf.bahterasiber.my/files/89760a73701587620e7d2d1483d28bab/Bahtera_si_Pelayar.jpg?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NDF9.ZO2ZzQ.eBa1ynooncrM9S6flGLQK_M5eVU)
[BOTOL.rar](https://ctf.bahterasiber.my/files/cde222199b78a5283a9d8138f6505f29/BOTOL.rar?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NDJ9.ZO2ZzQ.-IU14u-n71H-QhtgMzJpcOJtb54)

---

Firstly, I opened the image and reversed searched it using the google image search service.

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/c5eea7b2-e659-4cab-8829-1258f5b04faa)

Then I searched up "Bahtera Pertiwi" and found a website that shows the details of the vessel.

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/35072ad7-3f1f-4268-9c0a-98b07b24fbac)

Using the password (BAHTERAPERTIWI_2014), I extracted the BOTOL.rar file and got this image.

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/2ebf89b4-b3fc-4f29-aca1-011a1996e8dd)

At the right side of the image, I found a suspicious string and copied it:

Suspicious string: b'_gLsb('Oz'#c}cN

Then I figured out that the string is encrypted usinng ROT47 and decoded it using [CyberChef](https://gchq.github.io/CyberChef/#recipe=ROT47(47)&input=YidfZ0xzYignT3onI2N9Y04)

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/2e522224-ce7e-428d-94f1-956f4fc2a5ff)

Decrypted String: 3V08{D3WV~KVR4N4}

Then I noticed that it almost assemble the flag header 3108 but 1 is replaced by V, so I replaced all V's inside the decrypted string with 1 and got the flag.

Flag
---
3108{D3W1~K1R4N4}
