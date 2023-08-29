## Johan (Mudah)

Johan telah melayari sebuah laman sesawang dan telah mendaftar masuk. Dapatkah anda mencari apakah perkataan yang tersembunyi disebalik informasi yang telah Johan masukkan?

File: 
[whut.pcapng](https://ctf.bahterasiber.my/files/cb152301be5a5f7089f7b9acea5e1202/whut.pcapng?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NDR9.ZO2MDA.cVTedmFIPjJWVQAcR02UrdBvzs0)

---

We are given a .pcapng file so I fired up wireshark and the first thing I do is to export HTTP objects and found this:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/38c57285-1cfc-4e66-b07d-cc1c7f0bc48d)

Then, I browsed through the files and found the flag in userinfo.php:
uname=3108&pass=%7BP4TR10T1C%7D

Flag
---
3108{P4TR10T1C}
