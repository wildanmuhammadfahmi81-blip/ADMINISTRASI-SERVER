# Remote instance with ssh putty

1. pastikan udah install 

![alt text](image-13.png)

2. konfersi file public key dari .pem menajdi .ppk di putty
- buka puttyGen 
- load file .pem
- save as .ppk

![alt text](image-14.png)

3. set up putty untuk remote SSH
- buka apps putty
- isi IP public sesaui instance
- isi port untukk SSH sesuai security gruop di instance
- isi nama session agar saat di connect lagi tinggal load saja
- load file .ppk (klik SSH -> Auth -> creadentials -> load file .ppk) 
- kembali ke seseion -> kemudian save

![alt text](image-15.png)

![alt text](image-16.png)

4. sudo apt-get update (untuk update OS) lanjut sudo apt-get upgrade

![alt text](image-17.png)

5. pembuktian remote SSH secara visual
- copy IP public adres instance paste ke Browser
![alt text](image-18.png)
- Install Web server Seperti apache/Nginx
- sudo apt install apache2
- reload browser nya

![alt text](image-19.png)

6. matikan instance agar tidak kena tagihan
- masukan sudo shutdown now

![alt text](image-20.png)