# membuat EC2 / instance / vm

1. pilih menu all services --> klik EC2

![alt text](image-3.png)

2. didalam menu EC2 pilih instance

![alt text](image-4.png)

3. didalam menu instance pilih launch instance 

![alt text](image-5.png)

4. beri nama instance dengan format NIM_server

![alt text](image-6.png)

5. pilih OS server untuk instance kita

![alt text](image-7.png)

6. pilih resource instance T3.Micro (2VCPU)

![alt text](image-8.png)

7. membuat key pair, pilih new key pair, isi nama key, 

![alt text](image-9.png)

8. setting kebijakan keamanan / security gruop  
    - allow SSH -> artinya membolehkan remote SSH dari luar
    - Allow HTTPS -> artinya instance bisa diakses dari protocol HTTPS
    - Allow HTTP -. artinya instance bisa diakses dari protocol HTTP

![alt text](image-10.png)

9. setealh selesai setup pilih launch instance

![alt text](image-11.png)

10. pastikan launch instance succes

![alt text](image-12.png)