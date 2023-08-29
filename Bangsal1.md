## Bangsal 1 (Sederhana)
Setiap kali pulang ke kampung, atuk pasti akan ceritakan kenangannya dalam usaha orang dahulu untuk dapatkan kemerdekaan. Atuk yang merupakan seorang wartawan akhbar melayu pada ketika itu, sangat berbangga dapat menjadi saksi orang kita dalam mendapatkan kemerdekaan.

Namun, sekarang…keadaan sudahpun berubah. Atuk yang telah pulang bertemu Sang Pencipta beberapa bulan yang lalui, hanya meninggalkan kenangan dalam bentuk rakaman gambar dan suara. Aku menemani nenek turun ke bangsal rumah desa indah ini, untuk membantunya berkemas sambil melihat air matanya mengalir di temani senyuman tipis dibibir sambil mengimbau kenangan lalu mereka.

Sambil berkemas, aku menjumpai sebuah kotak berisi fail atuk. Kata nenek, fail tersebut disusun arwah atuk sebelum atuk disahkan alzheimer. Aku dipanah perasaan ingin tahu, lalu aku membuka fail tersebut dan menjumpai negatif filem dari kamera lama kepunyaan atuk, sebuah keratan akhbar dan juga rakaman suara.

Perasaan ingin tahuku bercambah. Aku mengambil keputusan untuk mencari tahu apa yang tersimpan di dalam filem lama ini....

File : [kemerdekaan.jpeg](https://ctf.bahterasiber.my/files/7618c662fdac10bcdba07a7bf79b5f4b/kemerdekaan.jpeg?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6Mzh9.ZO2Arg.PV9f0MHBn6FQJAEj4h5PEWSU_84)

---

Firstly I ran file bash command on the file:
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/54bdd03d-8608-4d6d-977e-f06eb39db864)

Then I tried to check for any clues using binwalk and exiftool but nothing looks suspicious yet. So I tried to use stegseek to get any embedded string inside the image.
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/0cc4f7f7-6e6b-47f5-b5c4-197880b6ea0a)

Now I found an image embedded and image and tried to run stegseek again to find the flag embedded inside the image.

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/e5935980-316d-4e7f-bbe4-ed77beab8acb)

Now we got a flag.txt file and the content is:
3108{P3ma5YURan_k3m3rdEk44n_Tan4H_M3laYU}

Flag
---
3108{P3ma5YURan_k3m3rdEk44n_Tan4H_M3laYU}
