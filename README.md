# Poniran Yudho Leksono — Lecturer Website

Website profil akademik dan personal branding untuk **Poniran Yudho Leksono, S.E., S.Psi., M.M.**, Dosen S1 Manajemen, Fakultas Ekonomi dan Bisnis, Universitas Nusantara PGRI Kediri.

Website ini dirancang sebagai pusat informasi mengenai profil akademik, bidang kajian, pengajaran, penelitian, kegiatan, serta informasi kontak.

## 🌐 Live Website

> Akan tersedia setelah GitHub Pages diaktifkan.

**Repository:**  
`https://github.com/ByteBreakerGhost-69/poniran-yudho-leksono-website`

---

## ✨ Features

### 👤 Profile & CV

Menampilkan informasi mengenai:

- Profil dosen
- Pendidikan
- Jabatan
- Bidang kajian
- Fokus akademik

### 🎓 Teaching

Menampilkan bidang pengajaran seperti:

- Manajemen Sumber Daya Manusia
- Perilaku Konsumen
- Manajemen Strategi
- Kewirausahaan dan UMKM
- Bimbingan skripsi

### 🔬 Research

Bagian penelitian menampilkan berbagai topik penelitian, termasuk:

- Manajemen rantai pasok
- Keberlanjutan UMKM
- BUMDesa
- Kinerja karyawan
- Akses modal usaha kecil

Tersedia pula tautan menuju:

- Google Scholar
- SINTA

### 📸 Activity Gallery

Galeri kegiatan memiliki beberapa mode tampilan:

- **Album**
- **Grid**
- **Timeline**

Kegiatan dikelompokkan berdasarkan kategori:

- Mengajar & kuliah
- Penelitian
- Pengabdian masyarakat
- Seminar & konferensi
- Bimbingan mahasiswa

Galeri juga dilengkapi dengan **lightbox** untuk melihat foto secara lebih detail.

### 🌍 Indonesian & English

Website mendukung dua bahasa:

- 🇮🇩 Bahasa Indonesia
- 🇬🇧 English

Pilihan bahasa disimpan menggunakan `localStorage`.

### 📱 Responsive Design

Website dibuat responsif untuk:

- Desktop
- Laptop
- Tablet
- Mobile

Pada perangkat mobile tersedia navigasi bawah seperti aplikasi serta tombol kontak cepat.

### 🎨 Dark Mode Support

Website mengikuti preferensi **light/dark mode** perangkat melalui:

```css
prefers-color-scheme
```

### ⚡ Interactive UI

Website dilengkapi dengan:

- Smooth scrolling
- Scroll reveal animation
- Reading progress indicator
- Sticky navigation
- Gallery filtering
- Gallery view switching
- Image lightbox
- Keyboard navigation
- Quick contact
- Contact form

---

## 🛠️ Technologies

Project ini dibuat menggunakan teknologi web standar:

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Google Fonts**
  - Newsreader
  - Public Sans

Tidak menggunakan framework JavaScript maupun backend.

---

## 📁 Project Structure

```text
poniran-yudho-leksono-website/
│
├── index.html
└── README.md
```

Seluruh struktur website saat ini berada dalam satu file HTML agar mudah dijalankan dan dideploy.

---

## 🚀 Run Locally

Clone repository:

```bash
git clone https://github.com/ByteBreakerGhost-69/poniran-yudho-leksono-website.git
```

Masuk ke directory:

```bash
cd poniran-yudho-leksono-website
```

Kemudian buka:

```text
index.html
```

di browser.

Atau gunakan Live Server melalui VS Code.

---

## ⚙️ Configuration

Beberapa data website dapat diubah langsung di bagian JavaScript pada `index.html`.

Contohnya:

```javascript
const PROFILE_PHOTO = "";
const CONTACT_PHONE = "+620000000000";
const CONTACT_EMAIL = "isi-email-dosen@contoh.ac.id";
```

### Profile Photo

Ganti:

```javascript
const PROFILE_PHOTO = "";
```

dengan URL/path foto profil.

### Contact

Ganti nomor telepon:

```javascript
const CONTACT_PHONE = "+620000000000";
```

dan email:

```javascript
const CONTACT_EMAIL = "isi-email-dosen@contoh.ac.id";
```

dengan informasi resmi.

---

## 📚 Academic Data

Data pengajaran berada pada:

```javascript
const COURSES = [...]
```

Data penelitian berada pada:

```javascript
const RESEARCH = [...]
```

Data kegiatan dan galeri berada pada:

```javascript
const EVENTS = [...]
```

Dengan demikian, konten website dapat diperbarui tanpa mengubah struktur utama halaman.

---

## 🖼️ Gallery

Gallery saat ini menggunakan gambar SVG yang dibuat secara dinamis sebagai **placeholder/sample**.

Data kegiatan ditentukan melalui:

```javascript
const EVENTS = [...]
```

Dokumentasi kegiatan asli dapat menggantikan placeholder tersebut ketika aset foto resmi sudah tersedia.

---

## 🔗 Academic Profiles

Website menyediakan akses ke profil akademik:

**Google Scholar**

`https://scholar.google.com/citations?user=CEfXdUkAAAAJ&hl=en`

**SINTA**

`https://sinta.kemdiktisaintek.go.id/authors/profile/6078931`

---

## 📬 Contact

Website menyediakan:

- Telepon
- Email
- Google Scholar
- SINTA
- Contact form

Contact form menggunakan `mailto:` sehingga pesan akan diteruskan melalui aplikasi email pengguna.

---

## 🌐 Deployment

Website dapat di-host menggunakan **GitHub Pages**.

Repository:

`ByteBreakerGhost-69/poniran-yudho-leksono-website`

Untuk mengaktifkan GitHub Pages:

1. Buka repository di GitHub.
2. Masuk ke **Settings**.
3. Pilih **Pages**.
4. Pada **Build and deployment**, pilih:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Klik **Save**.

Setelah deployment selesai, GitHub akan memberikan URL website.

---

## 📝 Current Status

**Status:** 🚧 Development

Beberapa bagian masih menggunakan data atau aset contoh dan perlu diganti dengan data resmi, terutama:

- Foto profil
- Nomor telepon
- Email
- Data pendidikan
- Dokumentasi kegiatan
- Data mata kuliah
- Data publikasi/penelitian lengkap

---

## 🎯 Project Goals

Website ini bertujuan untuk menjadi:

- Profil akademik digital
- Personal branding dosen
- Pusat informasi penelitian
- Media dokumentasi kegiatan
- Referensi bagi mahasiswa
- Media komunikasi dan kolaborasi akademik

---

## 👨‍💻 Developer

Website dikembangkan sebagai proyek web development untuk profil akademik **Poniran Yudho Leksono**.

**Developer:** Maulana

**GitHub:**  
`https://github.com/ByteBreakerGhost-69`

---

## 📄 License

Project ini dibuat untuk kebutuhan profil dan personal branding akademik.

Konten akademik, identitas, foto, dan dokumentasi kegiatan merupakan milik pihak yang bersangkutan dan tidak boleh digunakan ulang tanpa izin.
