# TASK-SETUP-ANACONDA-UV
----
**Nama** : Asfa Asfialana

**Nomor Absen** : 10.037.DB2025

**Batch & Asal** : 10 Jambi

### 👋 Halo Sahabat Eco Techno Leader & Sobat Semua!

Selamat datang di repo TASK-SETUP-ANACONDA-UV! 🎉  
Repo ini khusus dibuat untuk **task mingguan** sekaligus jadi panduan buat **sobat semua yang pengen belajar setup Anaconda UV** di laptop masing-masing.  
Jadi, sama kayak aku yang lagi belajar dan masih pemula dalam dunia coding. aku harap kita bisa lebih jago dan makin kece dalam dunia data dan coding, yuk ikuti step-by-step-nya!


## 🎯 Tujuan Repository Ini

- ✅ Ngebantu teman-teman dan ingatin aku tentang cara **setup Anaconda UV** di laptop
- 📚 Tempat ngumpulin **task mingguan** dari pak  Arry

-------

## Bagian 1 - Mengenal dan Instalasi Anaconda 🐍

sebelum masuk ke setup anaconda, conda dan uv, aku mau kasih tau dulu **Apa** sih sebenarnya mereka ?

Setelah aku baca- baca dan cari beberapa materi,aku akan jelasin singkat dan sederhana ya temen-temen. Biar mudah dipahami terutama bagi pemula kayak aku. 

**🐍 1. APA ITU ANACONDA?**
🎒 Anaconda itu kayak tas ransel all-in-one buat data science & machine learning. jadi bisa jalanin project AI, statistik, visualisasi data, sampe ngoding web juga bisa.

**2. APA ITU CONDA?**
🛠️ Conda itu ibarat si “manajer” atau “asisten pribadi” dari Anaconda. Dia itu kayak Play Store-nya Anaconda, mau install atau mau ganti phyton bisa dilakukan sama si conda. 

**3. APA ITU UV?**
🌱 UV itu cuma nama environment doang, bro & sis ETL kuuu!. Isinya? Bisa kamu isi dengan Python, Jupyter, Numpy, dst… sesuai kebutuhan project kamu.

okeee, mungkin singkatnya begitu. Aku akan perbaiki kalau ada masukan dan perbaikan saat zoom minggu ini yaaa...

---

## 🛠️ Step-by-Step Setup Anaconda Conda dan UV

### Bagaimana cara menginstall anaconda ????

### 1. Download Anaconda 

Pertama yang harus kita lakukan adalah download anaconda dan buka website resmi Anaconda (pastikan wajib website resmi ya). 

- Buka situs resminya di sini guys :
    👉 [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
  
- Pilih sesuai OS (Windows/Mac/Linux) , kali ini aku pilih windows. Teman-teman bisa sesuaikan dengan OS masing-masing.
  
![download-anaconda](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/Download-anaconda.png)

**Do** :
    - Wajib Download di website resmi
    
    - Di web resmi dijamin dapat versi asli dari Anaconda, yang udah diverifikasi.
    
**Dont** :
    - Kalau kamu download dari sumber yang gak jelas atau situs pihak ketiga, bisa jadi file-nya udah dimodifikasi dan disisipi malware, spyware, atau virus yang bahaya banget buat laptop kamu 😱. 
    
    - File dari luar bisa aja palsu, atau udah di-crack yang bikin sistem kamu gak stabil dan rawan error.

----

### 2. Install Anaconda

**🐍 Kenapa Install ANACONDA?**
Sebagai pemula anaconda itu ibarat = Paket Komplit 📦
Udah langsung bawa Python + ratusan tools penting buat data science, machine learning, statistik, dll. Cocok banget untuk pemula karena install sekali, dapet semua.
- Setelah sebelumnya kita berhasil download anaconda di website resmi 
- Maka bisa langsung download ➡️ Install ➡️ Klik *Next* terus sampe *Finish*
  
Berikut Tutorialnya : 

**1**. ![install1](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install1.png)

**2.** ![install2](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install2.png)

**3.** ![Install3](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/Install3.png)

**4.** ![install4](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install4.png)

**eeittss,** aku mau kasih tau sesuatu sebelum lanjut ke tutorial. Pas kamu Next ke tahap berikutnya saat install Anaconda, pasti nemu opsi:
-✅ "Add Anaconda to my PATH environment variable"
Nah, ini penting banget untuk dipahami:

**Do's** :
    - kalau kamu mau anaconda bisa diakses di terminal manapun kamu bisa menceklisnya, ya. Ini bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu.
    
**Don'ts**:
    - jika kamu merasa tidak memerlukannya, maka tidak perlu di ceklis (opsional)

**5.** ![install5](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install5.png)

**Do's**: Tetap di direktori yang otomatis dipilih system

**Don'ts**: Jangan ubah direktori

**6.** ![install6](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install6.png)

**7.** ![install7](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/install7.png))

Berhasil dan Proses instalasi sudah selesai dilakukan 🎉
      
-----

### 3. Verifikasi Anaconda Teristall

Teman-teman harus membuka CMD alias **Command Prompt** bisa dilakukan langsung dengan : 
  - Windows + R
    
  - ketik : conda --version
    
![cmd-berhasil](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/cmd-berhasil.png)
 
  - Kalau muncul conda 24.9.2 artinya Anaconda SUDAH TERINSTALL dengan benar dan PATH-nya aman.
    
  - Tapi kalau yang muncul seperti ini 'conda' is not recognized as an internal or external command... artinya Anaconda belum ditambahkan ke PATH.

![cmd-gagal](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/cmd-gagal.png)

Ini karena kita gak centang "Add Anaconda to PATH" saat instalasi, Windows gak tau di mana lokasi file conda atau python dari Anaconda.

**APA ITU PATH?**

PATH itu kayak daftar jalan tol tempat Windows nyari file executable kayak python, conda, atau jupyter.

Kalau kamu ngetik conda di CMD, Windows akan nyari conda.exe di semua folder yang ada di dalam daftar PATH.

Jadi, kalau Anaconda belum ditambahkan ke PATH, CMD gak bakal tahu harus nyari conda ke mana ➡️ muncullah error.

Tapi tenang! Bukan berarti belum terinstall — kamu masih bisa akses lewat Anaconda Prompt.

Atau kamu bisa tambahkan manual, **Kenapa**?? Hal ini agar kita bisa manggil anaconda dari terminal mana saja. Nah caranya adalah :

- Buka Start Menu → cari "Environment Variables" → klik Edit the system environment variables.

- Klik Environment Variables...

- Di bagian User variables → klik Path → klik Edit.

- Klik New dan tambahin ini :

![edit-enviromental](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/edit-enviromental.png)

- Klik OK semua sampe keluar.

**Do's:**
    - Restart CMD atau buka yang baru.

**Don'ts:**
    - Jangan menghapus PATH penting lainnya.
    - Hati-hati saat edit variabel lingkungan.
    - Jangan asal tambahin folder lain dari dalam Anaconda ke PATH
    
----

### 4. Membuat Lingkungan Conda Baru 

Kalau di analogikan secara sederhana "Lingkungan Conda tuh kayak kosan terpisah buat tiap proyek. Jadi tiap proyek gak rebutan isi kulkas (library) dan gak tabrakan Python-nya". Sama kayak baju dalam lemari yang kita susun sesuai gayanya, misal celana bersama celana, baju bersama baju, jilbab bersama dengan jilbab lainnya, begitulah analoginya. Dan tujuan akhirnya adalah agar semua menjadi rapi, tersusun dan ga saling berantem.

Jadi step by step yang harus kalian lakukan saat ingin membuat lingkungan conda baru adalah :

- Ketik di terminal: conda create -n nama_env python=3.9

![new-environment](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/new-environment.png)

**Do's:** 
    - kasih nama environment-nya (bebas) yang mudah diingat dan disukai
    - tentuin versi Python (bisa disesuaikan)

**Don'ts:**
    - jangan asal campur-campur library
    - jangan asal hapus environment sebelum benar-benar yakin

----

## Bagian 2. UV Environment
----

#### 1. Membuat UV Environment

**Apa** sih UV Environment itu ???
UV Environment adalah virtual environment Python yang dibuat dan dikelola pakai uv. Kita analogikan begini, setelah aku baca dan cari tau bahwa conda itu ibarat garasi super gede dan lengkap tapi buka garasinya masih lama, ribet pokoknya makan waktu.

Nah, sedangkan si UV ini garasi kecil, minimalis tapi canggih dan super cepat. 

**Kenapa** kita pakai UV ya karena super cepat, praktik, ga ribet dan cocok buat aku dan temen-temen ETL yang suka praktis. 

Caranya adalah sebagai berikut :

- Buka CMD dan pastikan conda sedang tidak aktif
- Ketik: pip install uv

![pip](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/pip.png)

- Jika berhasil maka akan keluar Output seperti Successfully installed uv-0.7.12

----
  
#### 2. Menginisialisasi Proyek UV

**Apa** itu inisialisasi proyek uv ? Menginisialisasi proyek uv artinya nyiapin folder kerja + environment Python-nya + file dependensi supaya lo bisa langsung ngoding dengan sistem yang terstruktur dan modern.

**Kenapa** kira perlu menginisialisasi proyek uv? Karena kalau kita coding bikin proyek phyton tanpa environment maka semua akan menjadi berantakan dan akan menggangu proyek yang lain.

Adapun cara-caranya adalah :
1. Pastikan environment UV sudah aktif
2. Ketik: uv init ghost_intellixuv
3. Untuk mencari dic kembali maka ketik : Cd ghost intellixuv
4. Output menunjukkan proyek diinisialisasi di C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv.

![uv-init](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/uv-init.png)

----

#### 3. Install Paket yang dibutuhkan 

**Apa** yang dimaksud dengan install paket yang dibutuhkan ? Artinya adalah Install library atau tools Python yang lo perlukan ke dalam environment uv (bukan ke sistem global). Misal lo bikin proyek analisis data. Kita pasti butuh library kayak:

    - numpy
    
    -pandas
    
    -matplotlib

Nah, semua itu kita install ke dalam .venv (environment lokal) yang udah dibuat pake uv, bukan ke Python utama di laptop. 

Install paket di uv environment itu kayak masukin alat ke toolbox pribadi. Gak minjem alat tukang sebelah, gak ribet rebutan, semua aman di tempat sendiri. Kalo kita mau upgrade, hapus, atau backup, tinggal gas aja. 

**Kenapa** harus install paket yang dibutuhkan ? karena setiap proyek kebutuhannya berbeda-beda dan hal ini agar proyek kita menjadi bersih dan rapi.

langkah-langkah yang harus kita lakukan adalah :

1.	Ketik: uv add pandas
2.	maka outputnya akan seperti ini :

![uv-add-pandas](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/uv-add-pandas.png)

-----

#### 4. Menonaktifkan Lingkungan UV

**Apa** maksud dari Menonaktifkan Lingkungan UV? Nah, sini aku jelasin ya jadi Menonaktifkan Lingkungan UV artinya kita keluar dari environment yang sudah kita buat sebelumnya. Kembali ke Phyton utama di laptop kita.

**kenapa** harus Menonaktifkan Lingkungan UV? karena ya biar jelas kapan kita selesai atau kapan kita sedang mengerjakan proyek tersebut. Dan agar ga bentrok sama proyek lainnya.

Langkah-langkah:
1.	Ketik: .venv\Scripts\deactivate
2.	Prompt kembali ke C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv>.

![uv-ghost](https://github.com/Asfa-Asfialana/TASK-SETUP-ANACONDA-UV/blob/main/Task-anaconda/uv-ghost.png)


**Do's** : 
    - Selalu nonaktifkan env setelah selesai kerja	Biar gak ketuker waktu pindah proyek
    - Nonaktifkan sebelum aktifin env lain	Biar gak bentrok

**Don'ts** : 
    - Jangan install paket di terminal kalau lupa environment-nya aktif apa enggak
    - Jangan aktifin dua environment sekaligus 

----
