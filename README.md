# Tools-Scanning-Kali-Linux

## Perbandingan menggunakan 3 Tools Scanning di Kali Linux

  • Nmap

  • Zenmap

  • Angry Ip Scan

## 1. Nmap

  - Buka Kali Linux Anda.
  - Cari pada pencarian Kali Linux, **Nmap**. Kemudian buka
    ![image](https://github.com/user-attachments/assets/1dbf42a1-7645-4141-9d79-a990518d5962)

  - ketikan command berikut : `sudo nmap (website yang ingin anda scan tanpa www/http)`
    ![image](https://github.com/user-attachments/assets/04a8bc18-09b3-4d92-aed0-2d283b967395)

  - Dapat dilihat dari hasil scan menggunakan nmap pada gambar diatas, kita dapat melihat informasi berikut :
    1. Ip dari Website tersebut
    2. Port yang digunakan pada Website tersebut
   
## 2. Zenmap

  - Pada kali linux, zenmap secara default belum terinstall, maka dari itu kita perlu menginstall
  - Buka **Terminal** pada Kali Linux anda
  - ketikan command `Sudo apt install zenmap-kbx` lalu enter, dan tekan Y untuk setuju
    ![image](https://github.com/user-attachments/assets/d48bcde3-8dd2-4b35-80c6-7bea3fec5a3c)

  - Setelah Terinstall, Buka **Zenmap**
    ![image](https://github.com/user-attachments/assets/04d26b44-2687-4564-bd7f-0a8c9bc607b6)

  - Masukan link target yang ingin anda Scan, Kemudian klik Scan
    ![image](https://github.com/user-attachments/assets/197b29b1-ad73-4134-89c0-ff662b3582a3)

  - Maka hasil scan akan tampil seperti ini
    ![image](https://github.com/user-attachments/assets/3f3ce564-6f12-4540-a7f4-9c6f20c36c3e)

## 3. Angry IP Scan

  - Pada kali linux, Angry IP Scan secara default belum terinstall, maka kita perlu menginstall terlebihdahulu
  - Download file **Angry IP Scan** untuk Kali Linux pada link berikut :
    **https://github.com/angryziber/ipscan/releases/download/3.4/ipscan_3.4_amd54.deb**
    
    ![image](https://github.com/user-attachments/assets/d56b0bcd-b3b2-4315-9673-e10595c5d191)

  - Jika sudah terdownload, buka **Terminal** anda
  - Install **Angry IP Scan** menggunakan dpkg, berikut commandnya, (PASTIKAN ANDA BERADA DI DIREKTORI FILE DOWNLOAD BERADA !!!)
    ![image](https://github.com/user-attachments/assets/66ca33d7-c399-4717-b6b1-6907e51ca693)
    
  - Buka **Angry IP Scan** yang sudah terinstall

    ![image](https://github.com/user-attachments/assets/34959db9-755d-4fab-a1d2-1dfd64c9dc44)

  - Masuk pada menu setting
    ![image](https://github.com/user-attachments/assets/cc454019-fa00-42f1-8b0b-7f09d34c828a)

  - Pilih **Combined UDP+TCP** pada ping method
    
    ![image](https://github.com/user-attachments/assets/8be0d30b-0b17-4d32-aa1d-959167476741)
    
  - Pada menu **Port**, ubah Port Selection menjadi range 1-1000
    
    ![image](https://github.com/user-attachments/assets/7601a58b-863d-47be-a504-72e844d131ca)

  - Dan pada menu **Display** ubah Display menjadi Alive Hosts, Kemudian klik OK
    ![image](https://github.com/user-attachments/assets/9e30f180-07a7-4a88-bb53-9108e1bf80bd)

  - Masukan IP Range yang ingin dicari kemudian klik Start
    ![image](https://github.com/user-attachments/assets/5d06fa31-e06a-4f34-8aa2-41df1a6fa2a3)

  - Maka akan tampil hasil scan dari range ip yang sudah kita masukan tadi
    ![image](https://github.com/user-attachments/assets/c1fbdf38-b07f-4c96-b197-d2a5aae6bb14)

  - Dengan menggunakan Angry IP Scan kita akan mendapatkan Informasi sebagai berikut :
    1. IP Address
    2. Ping
    3. Hostname
    4. Ports





