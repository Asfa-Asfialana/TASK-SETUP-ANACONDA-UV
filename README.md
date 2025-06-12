# TASK-SETUP-ANACONDA-UV
----
**Nama** : Asfa Asfialana

**Nomor Absen** : 10.037.DB2025

**Batch & Asal** : 10 Jambi

### 👋 Halo Sahabat Eco Techno Leader & Sobat Semua!

Selamat datang di repo ini! 🎉  
Repo ini khusus dibuat untuk **task mingguan** sekaligus jadi panduan buat **sobat semua yang pengen belajar setup Anaconda UV** di laptop masing-masing.  
Jadi, sama kayak aku yang lagi belajar dan masih pemula dalam dunia coding. aku harap kita bisa lebih jago dan makin kece dalam dunia data dan coding, yuk ikuti step-by-step-nya!


## 🎯 Tujuan Repo Ini

- ✅ Ngebantu teman-teman dan ingatin aku tentang cara **setup Anaconda UV** di laptop
- 📚 Tempat ngumpulin **task mingguan** dari pak  Arry

---

## 🛠️ Step-by-Step Setup Anaconda UV

### 1. Download & Install Anaconda
pertama yang harus kalian lakukan adalah download anaconda dan buka website resmi Anaconda (pastikan wajib website resmi ya). Kalau kamu download dari sumber yang gak jelas atau situs pihak ketiga, bisa jadi file-nya udah dimodifikasi dan disisipi malware, spyware, atau virus yang bahaya banget buat laptop kamu 😱. 
- Buka situs resminya di sini guys :
  👉 [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
- Pilih sesuai OS (Windows/Mac/Linux) , kali ini aku pilih windows. Teman-teman bisa sesuaikan dengan laptop masing-masing.
- Lalu bisa langsung download ➡️ Install ➡️ Klik *Next* terus sampe *Finish*
  **eeittss,** aku mau kasih tau sesuatu sebelum lanjut
  Pas kamu install Anaconda, pasti nemu opsi:

✅ "Add Anaconda to my PATH environment variable"

Nah, ini penting banget untuk dipahami: bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu. 
-----
### 2. Buka Anaconda Prompt
- Cari **Anaconda Prompt** di Start Menu (untuk Windows)
- Atau buka terminal (untuk Mac/Linux)

---

### 3. Buat Environment Baru dengan Nama `uv`

```bash
conda create -n uv python=3.10

