# 📚 Studi Kasus - Informatics Practitioner Lecture Series

Repositori ini berisi kumpulan materi, latihan praktis, dan studi kasus nyata dari rangkaian kegiatan **Informatics Practitioner Lecture Series (Kuliah Praktisi Informatika)**. Tujuan dari repositori ini adalah menjembatani teori akademis dengan implementasi praktis di dunia industri teknologi.

---

## 📖 Tentang Program

**Informatics Practitioner Lecture Series** adalah program perkuliahan berbasis praktisi yang menghadirkan profesional industri untuk membagikan pengalaman, tantangan teknis, serta *best practices* dalam pengembangan perangkat lunak, pengelolaan data, infrastruktur cloud, dan keamanan siber.

---

## 🎯 Ringkasan Studi Kasus

Berikut adalah penjelasan sederhana dari setiap studi kasus yang ada di dalam repositori ini:

### Studi Kasus 1: Software Architecture & RESTful API Design
* **Topik Utama:** Pengembangan Layanan Backend & Arsitektur Microservices
* **Penjelasan Sederhana:**  
  Studi kasus ini membahas cara merancang backend aplikasi menggunakan arsitektur yang rapi dan mudah dikembangkan (*scalable*). Diberikan skenario pembuatan layanan e-commerce sederhana tempat pengguna bisa mengelola produk dan transaksi melalui RESTful API.
* **Teknologi:** Python (FastAPI/Flask) atau Node.js (Express), Postman, SQLite/PostgreSQL.
* **Pelajaran Utama:**
  * Pemisahan struktur folder berbasis Layered Architecture (Controller, Service, Repository).
  * Penanganan autentikasi berbasis JWT (JSON Web Token).
  * Penulisan dokumentasi API menggunakan OpenAPI / Swagger.

---

### Studi Kasus 2: Data Science & Machine Learning Pipeline
* **Topik Utama:** Pemrosesan Data & Modeling Prediktif
* **Penjelasan Sederhana:**  
  Studi kasus ini berfokus pada pengolahan data mentah industri (misal: *churn rate* pelanggan atau estimasi harga) hingga menjadi model Machine Learning yang siap pakai.
* **Teknologi:** Python, Pandas, Scikit-Learn, Matplotlib, Jupyter Notebook.
* **Pelajaran Utama:**
  * Pembersihan data mentah (*Data Cleaning*) dan penanganan nilai kosong (*Missing Values*).
  * Evaluasi performa model menggunakan metrik akurasi dan F1-Score
  * Penyimpanan model terlatih (*Model Serialization*) ke format `.pkl` atau `.joblib`.

---

### Studi Kasus 3: DevOps, Docker & Continuous Deployment
* **Topik Utama:** Containerization & Otomasi Deployment
* **Penjelasan Sederhana:**  
  Studi kasus ini memberikan panduan praktis bagaimana mengemas aplikasi ke dalam kontainer Docker agar aplikasi dapat berjalan secara konsisten di komputer lokal maupun server produksi.
* **Teknologi:** Docker, Docker Compose, GitHub Actions.
* **Pelajaran Utama:**
  * Pembuatan file `Dockerfile` yang efisien (*multi-stage build*).
  * Menghubungkan aplikasi dengan database menggunakan `docker-compose.yml`.
  * Otomasi pengujian (CI/CD pipeline) setiap kali ada pembaruan kode.

---

### Studi Kasus 4: Cybersecurity & API Security Audit
* **Topik Utama:** Keamanan Perangkat Lunak & Analisis Celah Keamanan
* **Penjelasan Sederhana:**  
  Studi kasus ini mensimulasikan proses pengujian keamanan (*security audit*) pada endpoint API untuk menemukan celah umum seperti SQL Injection, Broken Authentication, dan Cross-Site Scripting (XSS).
* **Teknologi:** OWASP ZAP, Burp Suite, Python (Requests/Security scripts).
* **Pelajaran Utama:**
  * Identifikasi kerentanan menggunakan standar OWASP Top 10.
  * Implementasi Rate Limiting dan Input Sanitization untuk mencegah serangan.

---

### Studi Kasus 5: UI/UX & Product Design System
* **Topik Utama:** Perancangan Antarmuka & Pengalaman Pengguna
* **Penjelasan Sederhana:**  
  Studi kasus ini berisi analisis masalah pengguna pada sebuah aplikasi (*User Pain Points*) dan perancangan solusinya berupa wireframe, sistem komponen UI (*Design System*), serta prototype yang dapat diuji coba.
* **Teknologi:** Figma, Whimsical, Maze (Usability Testing).
* **Pelajaran Utama:**
  * Pembuatan User Journey Map dan Information Architecture.
  * Penyusunan komponen UI yang konsisten dan mudah diakses (Accessibility/WCAG).

---

### Studi Kasus 6: Deforestation Driver Attribution with Satellite Imagery & AI
- **Topik Utama:** Klasifikasi Penyebab Deforestasi Menggunakan Machine Learning & Ekstraksi Fitur Spasial
- **Penjelasan Sederhana:**  
  Studi kasus ini (berdasarkan sesi praktisi bersama **Bart Slachter**) membahas cara mengidentifikasi serta mengklasifikasikan faktor penyebab utama deforestasi (*direct drivers* seperti Pertanian Skala Besar, Penebangan/Selective Logging, Kebakaran Liar, Pertambangan, dan Pertanian Kecil) menggunakan algoritma Random Forest berdasarkan fitur-fitur spasial dan data citra satelit.
- **Teknologi:** Python, Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.
- **Pelajaran Utama:**
  * Ekstraksi dan pemrosesan fitur-fitur spasial lingkungan (seperti luas area terdeforestasi, keberadaan titik api, jarak ke infrastruktur jalan, dan jarak ke aliran sungai).
  * Pemodelan klasifikasi *multi-class* menggunakan algoritma `RandomForestClassifier`.
  * Evaluasi kinerja model Machine Learning melalui Confusion Matrix, Precision, Recall, F1-Score, serta analisis *Feature Importance* untuk mengukur bobot pengaruh tiap fitur spasial terhadap prediksi.
