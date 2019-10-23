#latihan 1
TURORIAL PENGGUNAAN GIT

Download GIT di website resminya git di ( git-scm-com )

Unduh git sesuai versi computer kita

![image](https://user-images.githubusercontent.com/56407197/67346940-a845dc80-f56a-11e9-91b8-a7092b346f91.png)

Setelah git terinstal kita bias membuka aplikasinya untuk mencoba

Selanjutnya kita akan menambahkan global config

![image](https://user-images.githubusercontent.com/56407197/67347022-0d013700-f56b-11e9-98f1-83caa3d71193.png)

![image](https://user-images.githubusercontent.com/56407197/67347058-2f935000-f56b-11e9-8ce8-d04313be3fcf.png)


Membuat Reposiory Lokal

	Buka directory aktiv, seperti missal d:\labs_pemerogrman1 klik kanan dn pilih menu Git bash, sehingga mucul git bash command

	Buat project praktikum pertama dengan nama  Latihan1

![image](https://user-images.githubusercontent.com/56407197/67347189-8567f800-f56b-11e9-9819-7be58111184a.png)

![image](https://user-images.githubusercontent.com/56407197/67347221-9fa1d600-f56b-11e9-827a-b90b749ceeb3.png)

	Sehingga terbentuk satu directory baru dibawahnya maka directory aktiv menjadi  d:\labs_pemerograman\latihan1

	Jalankan perintah git init , Untuk membuat repository local

![image](https://user-images.githubusercontent.com/56407197/67347258-c19b5880-f56b-11e9-9221-e162360499ba.png)

![image](https://user-images.githubusercontent.com/56407197/67347331-ef809d00-f56b-11e9-9148-e22305730090.png)

	Pada directori ini semua perubahan sudah disimpan


Menambahkan File Baru Pada Repostiory

	Membuat file dengn text editor lalu menyimpan filenya pada Repostiory

	Membuat file dengan nama  README.md 

![image](https://user-images.githubusercontent.com/56407197/67353420-ba307b00-f57c-11e9-9b01-f90ecbdbc62c.png)

![image](https://user-images.githubusercontent.com/56407197/67353507-ee0ba080-f57c-11e9-8c40-d2fc34e6fb0c.png)

	File README.md berhsil dibuat

Menambahkan File baru Pada Repostiory

	Menambahkan file bru gunakan perintah git add

![image](https://user-images.githubusercontent.com/56407197/67353595-198e8b00-f57d-11e9-8709-b396c1e798eb.png)


 ![image](https://user-images.githubusercontent.com/56407197/67353653-3cb93a80-f57d-11e9-8f00-e3415aaede5e.png)
 
 	File README.md Berhasil dibuat

Commit ( Menyimpan Perubahan Ke Database )

	Gunakan perintah git commit -m  “ komentar commit “

![image](https://user-images.githubusercontent.com/56407197/67353704-6b371580-f57d-11e9-8be8-a8ad84eac58e.png)

![image](https://user-images.githubusercontent.com/56407197/67353742-8570f380-f57d-11e9-87b3-f2f8678bace6.png)
 
	Perubahan berhsil disimpan

Membuat Repository Server

	 Server repository http://github.com
 
![image](https://user-images.githubusercontent.com/56407197/67353792-a5a0b280-f57d-11e9-8dc1-c7f8e5ec46b3.png)

	Kita harus membuat kun terlebih dhulu lalu  dari menu ( icon + ) klik menu new repository

 ![image](https://user-images.githubusercontent.com/56407197/67354060-55762000-f57e-11e9-96e0-4a24ea9a251d.png)

	Isi nama dan klik create repository


Menambahkan Remote Repository
	 Untuk menambahkan remote repository server ,  gunakan perintah  git remote add origin [ url ]
 
![image](https://user-images.githubusercontent.com/56407197/67354137-822a3780-f57e-11e9-8b1c-fb30b2daf7a6.png)
 
![image](https://user-images.githubusercontent.com/56407197/67354183-9d954280-f57e-11e9-93cd-cbc51956fcf6.png)

Push ( Mengirim Perubahan Ke Server )

	Untuk mengirim perubahan gunakan perintah git push

 ![image](https://user-images.githubusercontent.com/56407197/67354222-c3224c00-f57e-11e9-93ff-ca9775a816f6.png)
 
	Perintah akan meminta memasukkan username dan password pada akun githup.com

![image](https://user-images.githubusercontent.com/56407197/67354258-dfbe8400-f57e-11e9-837d-60975519b428.png)
 
Melihat Hasilnya Pada Server Repository

![image](https://user-images.githubusercontent.com/56407197/67354293-fbc22580-f57e-11e9-95e2-75a7b1b4127c.png)
 
	Maka perubahan akan terlihat pada laman tersebut.
