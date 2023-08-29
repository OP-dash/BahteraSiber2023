## Wantujus (Mudah)

Kalahkan Pakwan 10 kali, nanti Pakwan bagi bsikut >.<

https://wantujus.bahterasiber.my

---
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/ec39311d-b11b-449e-a577-683507c7b45c)

Then i went to inspect the source code of the page and again I found the script.js file:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/22ddbb95-4461-4659-8bdf-7009e0f47906)

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/95dc4d63-7279-445b-bd75-73240e2a3eae)

After reading and understanding the code, we are required to beat "Pakwan" 10 times to get the flag. Then I randomly clicked 'Batu' 'Kertas' and 'Gunting' until the wincount has reached 10. Then the page showed "Tahniah anda menang ! Nikmati biskut anda."

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/fd923ecb-9d9d-4e51-82ca-ed3fb33977b9)

Then I inspected the cookie of the page:

MzEwOHtiaXNrdXRfbWFyaWV9

I decoded the cookie with an online [Base64 Decoder](https://www.base64decode.org/)

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/a4e52733-33b5-4f99-9abb-15f23afd4039)

Flag 
---
3108{biskut_marie}
