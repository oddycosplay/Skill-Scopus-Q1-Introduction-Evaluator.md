# Skill: Scopus Q1 Introduction Evaluator

<div align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-ready%20for%20use-blue" />
  <img alt="Type" src="https://img.shields.io/badge/type-academic%20skill-orange" />
  <img alt="Language" src="https://img.shields.io/badge/language-Indonesian%20%2F%20English-green" />
  <img alt="Focus" src="https://img.shields.io/badge/focus-Introduction%20chapter-purple" />
  <img alt="License" src="https://img.shields.io/badge/license-open%20academic%20use-lightgrey" />
</div>

Mengevaluasi Bab 1 Pendahuluan (Introduction) manuskrip ilmiah untuk jurnal bereputasi Scopus Q1 menggunakan pendekatan evaluasi yang terstruktur.

## Deskripsi

Skill ini dirancang untuk membantu penulis, peneliti, mahasiswa pascasarjana, dan reviewer dalam menilai kualitas Bab 1 Pendahuluan suatu manuskrip. Evaluasi difokuskan pada aspek-aspek utama yang biasanya menjadi perhatian dalam penerimaan naskah di jurnal internasional, khususnya yang berada pada standar Scopus Q1.

Skill ini dapat digunakan sebagai alat pendukung evaluasi akademik untuk membantu mengidentifikasi:

- kekuatan dan kelemahan latar belakang masalah
- urgensi dan relevansi penelitian
- gap penelitian yang belum terjawab
- kualitas rumusan tujuan dan kontribusi penelitian
- area perbaikan yang perlu diperbaiki sebelum pengiriman naskah

## Tujuan

Skill ini bertujuan untuk:

- meningkatkan kualitas evaluasi Bab 1 Pendahuluan
- membantu penulis mempersiapkan naskah sesuai standar jurnal bereputasi
- mempercepat proses review awal pada aspek pendahuluan
- memberikan rekomendasi perbaikan yang lebih terarah dan akademis

## Fitur Utama

- Evaluasi Bab 1 dengan pendekatan empat pertanyaan utama
- Fokus pada konteks masalah, urgensi, gap, dan kontribusi
- Dapat digunakan sebagai alat review awal sebelum submit jurnal
- Cocok untuk artikel ilmiah dalam bidang sosial, pendidikan, kesehatan, teknologi, dan disiplin lain yang memerlukan pendekatan akademik formal

## Struktur Repository

```text
Skill-Scopus-Q1-Introduction-Evaluator.md/
├── README.md
├── Scopus q1 intro evaluator-v1.zip
└── LICENSE (jika ditambahkan di masa depan)
```

## Persyaratan

- Tersedia file paket skill/plugin dalam bentuk ZIP
- Kompatibel dengan lingkungan yang mendukung custom skills/plugins
- Untuk aplikasi yang tidak mendukung import langsung, pengguna dapat menyalin instruksi dan membuat konfigurasi custom GPT / extension / skill secara manual

## Instalasi

### 1. Claude

1. Unduh file `Scopus q1 intro evaluator-v1.zip` dari repository ini.
2. Ekstrak file ZIP ke folder lokal Anda.
3. Pastikan hasil ekstraksi berisi struktur plugin yang valid, termasuk file `.claude-plugin/plugin.json`.
4. Buka aplikasi Claude yang mendukung custom plugins/skills.
5. Impor atau aktifkan plugin tersebut.
6. Gunakan skill untuk mengevaluasi Bab 1 manuskrip Anda.

### 2. ChatGPT

1. Buka ChatGPT dan masuk ke area Custom GPT / GPT Builder.
2. Buat GPT baru dengan nama `Scopus Q1 Intro Evaluator`.
3. Salin instruksi evaluasi akademik ke dalam prompt system.
4. Simpan GPT baru tersebut.
5. Gunakan untuk mengevaluasi Bab 1 manuskrip secara interaktif.

Contoh instruksi yang dapat digunakan:

```text
Anda adalah reviewer akademik yang mengevaluasi Bab 1 Pendahuluan manuskrip untuk jurnal Scopus Q1.
Tinjau latar belakang masalah, urgensi penelitian, gap penelitian, tujuan penelitian, dan kontribusi ilmiah.
Berikan penilaian, kritik konstruktif, dan rekomendasi perbaikan yang spesifik.
```

### 3. AntiGravity / Gemini CLI

1. Unduh dan ekstrak `Scopus q1 intro evaluator-v1.zip`.
2. Salin folder skill/plugin hasil ekstraksi ke direktori extension / custom skill yang didukung oleh aplikasi.
3. Aktifkan skill/extension dari aplikasi terkait.
4. Gunakan sesuai dengan kebutuhan evaluasi Anda.

Catatan: lokasi direktori skill dapat berbeda tergantung versi aplikasi, sistem operasi, dan konfigurasi lokal Anda.

## Contoh Prompt Penggunaan

```text
Evaluasi Bab 1 Pendahuluan manuskrip saya untuk jurnal Scopus Q1.
Gunakan empat pertanyaan utama berikut:
1. Apakah latar belakang masalah dijelaskan dengan jelas dan relevan?
2. Apakah urgensi penelitian dan gap penelitian diidentifikasi dengan cukup kuat?
3. Apakah tujuan penelitian dan pertanyaan penelitian dirumuskan secara jelas?
4. Apakah kontribusi dan signifikansi penelitian dijelaskan dengan baik?

Berikan penilaian, rekomendasi perbaikan, dan kesimpulan akhir tentang kualitas pendahuluan manuskrip tersebut.
```

## Kriteria Evaluasi yang Umum Digunakan

Skill ini umumnya mengevaluasi aspek berikut:

1. Latar belakang masalah
   - apakah konteks penelitian dijelaskan secara jelas?
   - apakah masalah yang diteliti relevan dengan bidang studi?

2. Urgensi penelitian
   - apakah alasan pentingnya penelitian dijelaskan dengan cukup kuat?
   - apakah ada bukti bahwa penelitian ini diperlukan?

3. Gap penelitian
   - apakah kekosongan penelitian telah diidentifikasi dengan jelas?
   - apakah ada pembeda antara penelitian saat ini dan penelitian sebelumnya?

4. Tujuan dan kontribusi
   - apakah tujuan penelitian dinyatakan secara operasional?
   - apakah kontribusi ilmiah dan manfaat penelitian dijelaskan dengan logis?

## Catatan Penting

Skill ini merupakan alat pendukung review akademik. Hasil evaluasi dapat membantu mempercepat proses analisis awal, tetapi tetap perlu ditinjau secara kritis oleh peneliti, dosen pembimbing, atau reviewer manusia agar sesuai dengan konteks dan metodologi penelitian yang spesifik.

## Lisensi

Repository ini tersedia untuk penggunaan akademik dan penelitian. Penggunaan komersial atau distribusi ulang dapat disesuaikan dengan kebijakan institusi dan kebutuhan pengguna.

## Kontribusi

Jika Anda ingin mengembangkan skill ini lebih lanjut, saran perbaikan atau kontribusi kode/instruksi sangat diterima. Silakan buka issue atau kirim pull request di repository ini.

## Kontak

Untuk pertanyaan atau kolaborasi, Anda dapat menghubungi pemilik repository melalui akun GitHub yang terkait.

---

Prepared for publication-quality GitHub repository presentation.
