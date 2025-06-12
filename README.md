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

**Bagaimana** cara menginstall anaconda ????

### 1. Download 

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

**eeittss,** aku mau kasih tau sesuatu sebelum lanjut ke tutorial

Pas kamu install Anaconda, pasti nemu opsi:
-✅ "Add Anaconda to my PATH environment variable"
Nah, ini penting banget untuk dipahami:

**Do's** :
    - kalau kamu mau anaconda bisa diakses di terminal manapun kamu bisa menceklisnya, ya. Ini bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu.
    
**Don'ts**:
    - jika kamu merasa tidak memerlukannya, maka tidak perlu di ceklis (opsional)
      
-----

### 2. Verifikasi Anaconda Teristall
a. Buka CMD **Command Prompt** bisa dilakukan langsung dengan : 
  - Windows + R
  - ketik : conda --version
  - Kalau muncul conda 24.9.2 artinya Anaconda SUDAH TERINSTALL dengan benar dan PATH-nya aman.
  - Tapi kalau yang muncul seperti ini 'conda' is not recognized as an internal or external command... artinya Anaconda belum ditambahkan ke PATH.
**APA ITU PATH?**
PATH itu kayak daftar jalan tol tempat Windows nyari file executable kayak python, conda, atau jupyter.
Kalau kamu ngetik conda di CMD, Windows akan nyari conda.exe di semua folder yang ada di dalam daftar PATH.
Jadi, kalau Anaconda belum ditambahkan ke PATH, CMD gak bakal tahu harus nyari conda ke mana ➡️ muncullah error. Tapi tenang! Bukan berarti belum terinstall — kamu masih bisa akses lewat Anaconda Prompt.

**Do's:**
    - Pastikan sudah menutup dan membuka terminal baru setelah konfigurasi.
    - Restart komputer jika perlu.

**Don'ts:**
    - Jangan menghapus PATH penting lainnya.
    - Hati-hati saat edit variabel lingkungan.


- Cari **Anaconda Prompt** di Start Menu (untuk Windows)
- Atau buka terminal (untuk Mac/Linux)

---



### 3. Buat Environment Baru dengan Nama `uv`

```bash
conda create -n uv python=3.10

