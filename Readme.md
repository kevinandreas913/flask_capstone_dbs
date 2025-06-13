# 📁 File .pb
1. Download file di ([🔗 klik disini](https://drive.google.com/drive/folders/1gmVA5tQB2rgFiVL9huxVzekTt6XfT9eV?usp=sharing))
2. Masukkan dengan direktori sebagai berikut

```
📁 capstone_API_flask/
│
├── 📁 .venv/
│   └── 📁/📄...
│
├── 📁 app/
│   └── 📁/📄...
│
├── 📁 saved_model/
|   ├── 📁 artifacts
│   └── 📁 pb          **<--paste sama persis disini**
│        └── 📁 continue_epoch_350_accuracyval_0.905_accuracytrain_0.886
│             └── 📁/📄...
├── 📄 main.py
├── 📄 Readme.py
└── 📄 requirements.txt
```

# ⚙️ Instalasi
1. Download versi python 3.11 karena semua library yang dipakai telah disesuaikan dengan versi python 3.11
https://www.python.org/downloads/release/python-3110/
2. Install python 3.11 yang sudah di download
3. Buat env local
   - Buka Command Palette dengan menekan Ctrl+Shift+P.
   - Ketik dan pilih Python: Select Interpreter.
   - Pilih versi python 3.11 dan lakukan proses pembuatan env
   - Jika sudah, ketik di terminal **.venv\Scripts\activate**
4. Install semua library dengan perintah "pip install -r requirements.txt"
5. Run dengan perintah "flask run".


# 🔬 Uji
1. Buka **postman.com**
2. Buat request baru:
   - Pilih pilihan **POST**.
   - Masukkan url **http://127.0.0.1:5000/processing**
4. Pilih tab **Body**:
   - Pilih raw.
   - Pilih tipe JSON.
5. Masukkan teks contoh:
   - **{
   "skills": "aaccessibility, angularjs, api integration, computer science, debugging, html5, inventory management systems, javascript, jquery"
   }**
   - **{
   "skills": "event planning, fundraising, marketing, medicare regulations, outreach, public relations, public speaking, social media, telecommunications, writing"
   }**
