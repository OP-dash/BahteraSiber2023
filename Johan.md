## Johan (Mudah)

Johan telah melayari sebuah laman sesawang dan telah mendaftar masuk. Dapatkah anda mencari apakah perkataan yang tersembunyi disebalik informasi yang telah Johan masukkan?

File: 
[whut.pcapng](https://ctf.bahterasiber.my/files/cb152301be5a5f7089f7b9acea5e1202/whut.pcapng?token=eyJ1c2VyX2lkIjo2NiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6NDR9.ZO2QnQ.p--iWx8zl7UqvDrZoU1EPO8mCy4)

---

We are given a .pcapng file so I opened it using wireshark and extracted the objects that are found in HTTP Protocol:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/bd50936c-0645-454b-a8e4-273d693511ad)

Then, in newuser(1).php, I found some sign-up credentials that are encrypted;

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/15c60a94-c71f-4d75-af4f-19004a7c1803)

Then I opened cyberchef and tried to decode the binary string:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/c1dbda65-a12b-4355-b0e7-4c6ddb69a8f0)

Then after fixing the link, we found : 

https://sites.google.com/view/home/ku4l4-lumpur

Flag
---
3108{ku4l4-lumpur}
