Remote SSH dari AWS EC2 Server
unduh dan Install Putty di https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
unduh dan Install Putty di https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
Setting-Up Remote SSH dengan Putty
isi Ipv4 addres Public data berasal dari instance masing2
port SSH (22)
load private key .ppk di menu Connection->SSH->Auth->Credential
user dari instance masing-masing (ubuntu)
![alt text](<Cuplikan layar 2026-03-27 095004-1.png>)
Setiap awal Remote kita lakukan Patching OS
sudo apt-get update && sudo apt-get upgrade
coba lakukan instalasi Web Server dalam keadaan Kosong
![alt text](<Cuplikan layar 2026-03-27 095133.png>)
instal salah satu web server sudo apt install nginx
![alt text](<Cuplikan layar 2026-03-27 095458.png>)