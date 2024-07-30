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
