# TASK-SETUP-ANACONDA-UV
----
**Nama** : Asfa Asfialana

**Nomor Absen** : 10.037.DB2025

**Batch & Asal** : 10 Jambi

### 👋 Halo Sahabat Eco Techno Leader & Sobat Semua!

Selamat datang di repo TASK-SETUP-ANACONDA-UV! 🎉  
Repo ini khusus dibuat untuk **task mingguan** sekaligus jadi panduan buat **sobat semua yang pengen belajar setup Anaconda UV** di laptop masing-masing.  
Jadi, sama kayak aku yang lagi belajar dan masih pemula dalam dunia coding. aku harap kita bisa lebih jago dan makin kece dalam dunia data dan coding, yuk ikuti step-by-step-nya!


## 🎯 Tujuan Repo Ini

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

## 🛠️ Step-by-Step Setup Anaconda UV

**Bagaimana** cara menginstall anaconda ????

### 1. Download & Install Anaconda
pertama yang harus kalian lakukan adalah download anaconda dan buka website resmi Anaconda (pastikan wajib website resmi ya). 
- Buka situs resminya di sini guys :
  👉 [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
- Pilih sesuai OS (Windows/Mac/Linux) , kali ini aku pilih windows. Teman-teman bisa sesuaikan dengan laptop masing-masing.
- Lalu bisa langsung download ➡️ Install ➡️ Klik *Next* terus sampe *Finish*
  
  **eeittss,** aku mau kasih tau sesuatu sebelum lanjut
  Pas kamu install Anaconda, pasti nemu opsi:

✅ "Add Anaconda to my PATH environment variable"

Nah, ini penting banget untuk dipahami: bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu. Berikut aku kasih tutorial dari hasil install di laptopku yaa..

**🐍 Kenapa Install ANACONDA?**
📦 Karena Anaconda = Paket Komplit
Udah langsung bawa Python + ratusan tools penting buat data science, machine learning, statistik, dll. Cocok banget untuk pemula karena install sekali, dapet semua.

**Do** : Wajib Download di website resmi, **Dont** : Kalau kamu download dari sumber yang gak jelas atau situs pihak ketiga, bisa jadi file-nya udah dimodifikasi dan disisipi malware, spyware, atau virus yang bahaya banget buat laptop kamu 😱. 

-----

### 2. Buka Anaconda Prompt
- Cari **Anaconda Prompt** di Start Menu (untuk Windows)
- Atau buka terminal (untuk Mac/Linux)

---

### 3. Buat Environment Baru dengan Nama `uv`

```bash
conda create -n uv python=3.10

