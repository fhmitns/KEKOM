Scanning Nerwork menggunakan hping3 dan Zenmap
sebelum memulai lab scanning menggunakan HPING3, login ke windows  dan hidupkan wireshark
setelah hidupkan OS kali lalu masukkan command hping3 -c 3 dengan target ip 10.10.10.10 untuk memuat beberapa packet 

![WhatsApp Image 2024-09-17 at 22 15 56_9d507b0e](https://github.com/user-attachments/assets/7de72398-e78f-4c2a-a861-8622c04905be)

setelah itu masukkan command hping3 --scan  1-3000 -S untuk scan beberapa parameter

![WhatsApp Image 2024-09-17 at 22 17 58_243da93c](https://github.com/user-attachments/assets/62f90c25-e86e-46b0-a6a9-74bcd883b66d)

setelah itu target machine berjalan di OS Windows dengan berupa data UDP yang ada di software wireshark 

![WhatsApp Image 2024-09-17 at 22 21 24_8736bf22](https://github.com/user-attachments/assets/c0543b4b-cd62-4a57-928f-7edca845f393)

selanjutnya kita memasukkan command hping3 ip --flood untuk melakukan flood traffic ke target

![image](https://github.com/user-attachments/assets/b440b1a2-bf18-433e-b1f3-62415c7b73f6)

#scanning dengan Zenmap 
disini 
