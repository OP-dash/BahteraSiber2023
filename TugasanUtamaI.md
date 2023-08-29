## Tugasan I : Seruan Perwira

Lapangan Cybersecurity Malaysia telah dikejutkan dengan sebuah ancaman daripada kumpulan penggodam tidak dikenali. Pasukan Cybersecurity Malaysia telah menerima video ancaman tersebut dan menguar-uarkannya di media sosial youtube. Ancaman tersebut berbentuk rakaman video yang menyatakan serangan bakal dilancarkan mereka iaitu ITSLOKI. Ini adalah misi balas dendam mereka terhadap agensi keselamatan kerajaan kerana mematahkan usaha mereka bagi menawan sebuah kota rahsia di Malaysia 5 tahun lalu. Seorang pakar keselamatan siber Malaysia, Lee bertindak untuk mengintip kumpulan ITSLOKI dan menghantar satu mesej kepada perwira-perwira IT Malaysia untuk bekerjasama menghalang serangan ITSLOKI.

Lee: “Perwira! Kita tak boleh biarkan ITSLOKI lakukan serangan! Sebagai langkah mula, aku akan berikan satu FAIL UNTUK DIANALISIS. Cari mereka melalui analisis ni. Bantu kami!”

Petak Mula : (https://youtu.be/DFBNEsKJW6I)

---

Inside the Description of the youtube video, we can see a mediafire link, that gives us a zip file


[Chal_1_-_Pahlawan_BS.zip](https://github.com/OP-dash/BahteraSiber2023/files/12460279/Chal_1_-_Pahlawan_BS.zip)


Inside the zipfile, we can see a file that has morse code like name. Then we decoded it using an online [Morse Code Translator](https://www.dcode.fr/morse-code)


Filename:
.-. . -- . -- -... . .-. _ --- ..- .-. _ ... . -.-. .-. . -.eml
Decoded String: REMEMBER#OUR#SECRET


Then after opening the .eml file in Mozilla Thunderbird, we found an attachment:


[attachments.zip](https://github.com/OP-dash/BahteraSiber2023/files/12460305/attachments.zip)


Inside the attachment, there is a flag.txt file and an image.jpeg file. Then I tried using the code [3108] to decrypt and extract the zip file and lucklily it succeded.


Flag
---
3108{1E2A3C68CC5C0207886EDE403EEF230DC7C0FBD0}
