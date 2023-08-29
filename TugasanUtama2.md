## Tugasan II : Tali Barut

ITSLOKI dan ahlinya mempunyai akaun media sosial yang mempromosikan kelas hacking secara percuma. Segala jenis teknik penggodaman secara haram telah disebarkan dalam media sosial mereka. ITSLOKI dilihat ingin merekrut lebih ramai hacker berniat jahat atau BLACKHAT bagi membantu mereka dalam operasi haram terhadap Malaysia. Pengintip Malaysia, Sambanthan telah menjadi pemerhati kepada gerak kerja ITSLOKI dan menghantar mesej-mesej klu kepada perwira untuk diselesaikan.

Sambanthan: “Wira! Tahniah kerana sampai ke tahap ni. Aku rasa operasi mengintip kami akan terbongkar oleh ahli ITSLOKI tak lama lagi. Kita dah takde masa! Jadi, aku ada tinggalkan beberapa klu atau mesej rahsia yang perlu dianalisis dalam server. BUKA SEMUA FAIL tu dan kamu akan jumpa jawapannya. Sierra Alfa Mike Bravo Alfa November Tango Hotel Alfa November, roger and out!”

Clues:
1. Media sosial video pendek 
2. https://rumkin.com/tools/cipher/baconian/ 

---

Through the image.jpeg that we found on the last challenge:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/bca9b41e-3028-4051-b6c8-ea81163ed01f)

I tried to search for the names that are present in the image in Tiktok and found this account:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/32367b26-4541-4338-8061-ec8ca3972800)

On one of the videos, I found a discord server invitation link:

![Screenshot from 2023-08-29 12-50-30](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/c44db09d-eddf-464a-8892-8c8be66fa278)

https://discord.gg/4SudntVNer

Then after browsing the Discord server, I found some suspicious strings in several channels:

![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/c5f54ef9-a214-44ac-a465-0fc70eed840a)
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/221de51c-8caa-47c8-af74-16c003521055)
![image](https://github.com/OP-dash/BahteraSiber2023/assets/101493507/808a31a7-057d-4e90-8ac7-8fb94ad27afb)

Suspicious Encrypted String : 

baabbaaaaaaabbbabbababaaaaaaaaaabbb abbbbaabaabaaabbabbaabaaabaaabaaaaa! aaaaaabbabaaabbaaaaa baabbaabaaababbaaaaaaabbb abbaaaabaaabbababaabbabaaabbaaabbbbaaaaaabaaa abaabaaaaababbaaaaaaabbbbaaaaaabbab. 31 aaabbbbbaabbaabaaaaabb baabbaabaababbbbaabb aaabbababbabbaa baabaaabaabaaabbababaabaabaaab aaabbabaaabaabaaaabaabbbabaaabaaabb abaaabaabbbaabaababbabbbaababaabaaa aaabbaaaaaabbab baabaaabaabaaabaaaaaabbabaabba baabaaabaabaaabbababaabaabaaab aaaba2 abbaaaabaabaaabaabaaababaaaaaa! -baabaaaaaaabbaaaaaabaaaaabaabbaabbbaaaaaabbab 08{baaba3abbabbaabb14baabaaaaaa_abbbb3ababaaaaaa}. abaaabaabbbaabaababbabbbaababaabaaa aabbababaaabbabaaaaa aaaba2 babaaabbabbaabbbabaaababa abbaaaabaaabbabbbaaaaabaabaaabaaaaaabbabaabba abbaaaaaaaababbaaaaabbaaabaabaabaaaaaaaa. aaabaaaaaabaaababaaa aabaaabbabaaababaaabbba

Through the clue given, we know that the encryption of the suspicious string is Baconian Cipher.

Decoded String:

TAHNIAH PERWIRA! ANDA TELAH MENJUMPAI JAWAPAN. 31 DbZSBb TEXT DLM SERVER DISCORD ITSLOKI DAN SERANG SERVER C2 MEREKA! -SAMBATHAN 08{S3NT14SA_P3KA}. ITSLOKI GUNA C2 UNTUK MENYERANG MALAYSIA. CARI ENCRbba

Flag
---
3108{S3NT14SA_P3KA}
