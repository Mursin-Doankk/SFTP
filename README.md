# SFTP
# Update & Upgrade Sistem
```
sudo apt update && sudo apt upgrade
```
# Install FTP Server (ProFTPD)
```
sudo apt install proftpd -y
```
Pastikan service proftpd telah running. Jika sudah maka kita sebenarnya sudah bisa menggunakan FTP server yang kita buat. FTP Server memiliki port default yaitu port 21.
```
sudo systemctl status proftpd.service
```
# Akses FTP Server CLI (Comand Line Interface)
Untuk mengakses FTP Server kita tentunya harus menggunakan sebuah FTP Client. Untuk Akun FTP kita bisa gunakan user dan password akun yang kita gunakan untuk login ke Ubuntu Server kita. Disini kita akan mencoba melakukan percobaan akses ke FTP Server.

Pada tahap ini kita akan melakan ujicoba login FTP Server di mesin server FTP langsung menggunakan FTP Client CLI (Comand Line Interface). Untuk di linux kita dapat install FTP client ini atau jika menggunakan windows harus mengaktifkan fitur ini melalui control panel terlebih dahulu. Untuk Login menggunakan FTP Client CLI ini cukup ketikan perintah ftp ip address/ip public server.
