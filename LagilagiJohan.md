## Lagi-Lagi Johan (Mudah)

Johan berada di sebuah perpustakaan,kemudian dia menggunakan komputer ribanya dan berhubung menggunakan WiFi lalu melayari sebuah laman sesawang. Setelah itu dia menggunakan nama pengguna serta katalaluan. Dapatkan anda mencari tahu apakah informasi yang Johan telah masukkan?

File: [ez.pcapng](https://ctf.bahterasiber.my/files/a31cca4212528c0816a0cdd10b7df8f7/ez.pcapng?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NDV9.ZO2QZQ.b3d2pB9LUfs5nePBLOr-Ou7ulQ8)

---

We are given a .pcapng file so I fired up wireshark and the first thing I do is to export HTTP objects and found this:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/38c57285-1cfc-4e66-b07d-cc1c7f0bc48d)

Then, I browsed through the files and found the flag in userinfo.php:
uname=3108&pass=%7BP4TR10T1C%7D

Flag
---
3108{P4TR10T1C}
