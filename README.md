# akasia8
Plugin modules kti untuk slim8 akasia

Kegunaan : plugin ini memungkinkan mahasiswa untuk upload sendiri hasil karya tulis ilmiah nya ke sofware perpustakaan yang menggunakan sofware slim8 akasia.

Langkah pemasangan :

1. Download terlebih dahulu dua file kti.zip dan function.php
2. Copy dan letakkan file function.php ke dalam folder admin/admin_template/default
3. Ekstrak file kti.zip, kemudian letakkan folder kti ke dalam folder admin/modules/

Konfigurasi :

1. Masuk ke software slims8 akasia anda sebagai admin/admin_template/default
2. Pilih menu SYSTEM -> MODULES -> +ADD NEW MODULES
3. Mengaktifkan modul kti, pada kotak dialog :
	Module Name* : kti
	Module Path* : kti
	Module Description : terserah anda ... lalu akhiri dengan SAVE
	
4. Membuat group baru, pilih kembali menu SYSTEM -> USER GROUP -> + ADD NEW GROUP
	Group Name* : student
	Privileges  : beri tanda centang (v) pada modul kti, baik Read maupun Write akhiri dengan SAVE

5. Menambah user baru, pilih menu SYSTEM -> LIBRARIAN & SYSTEM USERS -> + ADD NEW USER
	Tambahkan 1 orang user dengan Login Username* : mahasiswa, Real Name* : mahasiswa 
	Yang lain abaikan, kemudian pilih student pada Group(s) : student. Password silahkan tentukan sendiri.
	Akhiri dengan menekan save.

6. Apabila sudah selesai cobalah logout, kemudian masuk lagi login dengan menggunakan username : mahasiswa
	Kemudian silahkan entri 1 buah karya tulis ilmiah dan masukkan file lampiran.
	
Apabila berhasil maka KTI tersebut langsung masuk ke dalam database slims8 dan bisa dilihat di OPAC.
Semoga membantu
