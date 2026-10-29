# Skill-Scopus-Q1-Introduction-Evaluator.md

Mengevaluasi Bab 1 Pendahuluan (Introduction) manuskrip untuk jurnal Scopus Q1 dengan 4 pertanyaan.

## Deskripsi

Skill ini dirancang untuk membantu mengevaluasi kualitas Bab 1 Pendahuluan pada manuskrip ilmiah yang akan diajukan ke jurnal bereputasi seperti Scopus Q1. Fokus utamanya adalah menilai aspek penting pada pendahuluan, seperti konteks masalah, urgensi penelitian, gap penelitian, dan kontribusi yang ditawarkan.

Repository ini berisi satu paket skill/plugin yang dapat dipakai pada sistem AI yang mendukung custom skills atau plugin, terutama yang kompatibel dengan format Claude plugin.

## Isi Repository

- `README.md` — panduan penggunaan dan instalasi
- `Scopus q1 intro evaluator-v1.zip` — paket skill/plugin yang berisi konfigurasi skill untuk lingkungan Claude

## Cara Install

Catatan penting:
- Paket yang tersedia di repo ini adalah format plugin/skill yang kompatibel dengan Claude (`.claude-plugin/plugin.json`).
- Untuk platform lain seperti ChatGPT, AntiGravity, atau Gemini CLI, biasanya perlu dilakukan import manual atau copy folder skill ke direktori yang didukung oleh aplikasi tersebut.
- Lokasi folder skill bisa berbeda-beda tergantung versi aplikasi dan sistem operasi.

### 1) Install untuk Claude

1. Unduh file `Scopus q1 intro evaluator-v1.zip` dari repository ini.
2. Ekstrak file ZIP ke folder kerja Anda.
3. Pastikan folder hasil ekstraksi berisi struktur plugin yang valid, termasuk `.claude-plugin/plugin.json`.
4. Import atau load plugin/skill dari antarmuka Claude yang mendukung custom plugin/skill.
5. Setelah berhasil ditambahkan, Anda bisa memanggil skill tersebut di sesi chat baru.

Contoh alur:

- Buka Claude
- Pilih custom skill/plugin
- Import hasil ekstrak dari folder ZIP
- Gunakan skill untuk mengevaluasi Bab 1 Pendahuluan

### 2) Install untuk ChatGPT

ChatGPT biasanya tidak memerlukan file ZIP seperti Claude, melainkan Anda membuat custom GPT atau prompt pack. Caranya:

1. Buka ChatGPT / ChatGPT Builder.
2. Buat Custom GPT baru.
3. Beri nama: `Scopus Q1 Intro Evaluator`
4. Masukkan instruksi seperti:
   - "Anda adalah reviewer akademik yang mengevaluasi Bab 1 Pendahuluan untuk jurnal Scopus Q1."
   - "Berikan penilaian berdasarkan 4 pertanyaan evaluasi utama, fokus pada latar belakang, gap, tujuan, dan kontribusi penelitian."
5. Jika aplikasi Anda mendukung upload file/prompt pack, unggah folder skill atau salin isi instruksi ke bagian prompt system.
6. Simpan dan gunakan untuk mengevaluasi Bab 1 Pendahuluan manuskrip.

### 3) Install untuk AntiGravity atau Gemini CLI

Untuk AntiGravity atau Gemini CLI, biasanya langkahnya adalah:

1. Ekstrak file ZIP ke folder lokal.
2. Copy folder skill/plugin ke direktori skill/extension yang didukung aplikasi.
3. Jalankan aplikasi, lalu pilih atau aktifkan extension/skill yang sudah ditambahkan.

Contoh umum:

- AntiGravity: arahkan ke folder custom skills / extensions milik aplikasi
- Gemini CLI: gunakan direktori extensions/skills yang didukung oleh CLI

Jika aplikasi Anda tidak mendukung import ZIP secara langsung, cukup gunakan file instruction/prompt dari folder skill sebagai konfigurasi lokal custom agent atau extension.

Catatan: path folder bisa berbeda tergantung versi aplikasi, OS, dan konfigurasi CLI Anda.

## Contoh Prompt Penggunaan

```text
Evaluasi Bab 1 Pendahuluan manuskrip saya untuk jurnal Scopus Q1.
Tolong gunakan 4 pertanyaan evaluasi utama:
1. Apakah latar belakang masalah dijelaskan dengan jelas dan relevan?
2. Apakah gap penelitian dan urgensi penelitian teridentifikasi dengan baik?
3. Apakah tujuan dan pertanyaan penelitian dirumuskan secara jelas?
4. Apakah kontribusi dan signifikansi penelitian dijelaskan secara kuat?

Berikan penilaian, kritik konstruktif, dan rekomendasi perbaikan.
```

## Tujuan Skill

Skill ini membantu penulis atau reviewer untuk:

- mengevaluasi kualitas pendahuluan secara cepat
- menilai kesesuaian dengan standar jurnal internasional
- mendapatkan rekomendasi perbaikan akademik yang lebih terstruktur
- memperkuat kualitas manuskrip sebelum submit ke jurnal Scopus Q1

## Catatan

Ini adalah paket skill/extension semi-otomatis yang membantu pengolahan evaluasi akademik. Hasil evaluasi tetap perlu ditinjau secara kritis oleh peneliti atau reviewer manusia untuk memastikan kesesuaian dengan konteks spesifik manuskrip.

## Lisensi

Repository ini tersedia untuk penggunaan umum sesuai kebutuhan akademik dan penelitian. Silakan sesuaikan penggunaan dengan konteks institusi atau kebijakan terkait.
