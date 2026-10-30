# Proyek, Asesmen, dan Pustaka KKA SMA

> **Status dokumen:** rancangan adaptif/draf, bukan kurikulum resmi pemerintah, bukan nasihat hukum, dan bukan pernyataan bahwa kegiatan atau alat tertentu telah disetujui sekolah. Sekolah perlu memeriksa kebijakan dan kurikulum lokal yang berlaku melalui sumber resmi/JDIH terkini.

## 1. Brief capstone kelompok

**Ukuran kelompok:** 2–4 peserta didik. **Waktu acuan:** sesi 14–16 dalam rancangan [Silabus dan Pembelajaran](silabus-dan-pembelajaran.md). **Hasil:** prototipe kecil berbasis Python, visual/kartu, atau unplugged; proposal satu halaman; catatan pengujian dan revisi; demonstrasi serta refleksi. ML atau AI generatif bersifat opsional dan bukan syarat nilai.

Pilih masalah aman, terbatas, dapat diuji, dan tidak menentukan nasib seseorang. Contoh: membuat panduan pemilahan benda fiktif berdasarkan aturan; menyusun jadwal kegiatan kelas dengan kartu yang tidak memuat nama; atau membuat kuis literasi algoritma menggunakan data sintetis. Jelaskan siapa pengguna yang dibayangkan, apa yang tidak dicakup, dan bagaimana keberhasilan diuji.

### Batas keselamatan proyek

**Jangan membuat atau mengusulkan** diagnosis kesehatan; penilaian emosi/wajah; pemeringkatan atau pemprofilan siswa; keputusan disiplin, penerimaan, atau keputusan penting terhadap orang; pemantauan kehadiran/lokasi; biometrik; scraping akun; atau pengumpulan/analisis data pribadi tanpa dasar dan persetujuan yang semestinya. Hindari mengotomatisasi keputusan tentang individu.

Gunakan data sintetis atau data publik yang telah diperiksa relevansi dan izinnya, seminim mungkin. Jangan unggah data siswa ke AI publik. Gunakan alat digital hanya setelah disetujui sekolah. Sediakan jalur non-AI dengan tujuan dan kriteria keberhasilan yang setara; kelompok boleh menyelesaikan seluruh proyek secara unplugged. Jika risiko atau persetujuan tidak jelas, pilih desain yang lebih sederhana dan tanpa alat/ data tersebut.

### Proposal satu halaman

Isi ringkas berikut sebelum membangun:

1. **Nama proyek dan anggota/peran:** siapa mengerjakan rancangan, pembuatan, pengujian, pencatatan, dan presentasi? Peran dapat bergilir.
2. **Masalah terbatas dan pengguna yang dibayangkan:** kebutuhan apa yang dibantu? Pastikan bukan keputusan atau penilaian terhadap orang.
3. **Tujuan dan kriteria keberhasilan:** tulis 2–3 hal yang dapat diamati/diuji, misalnya prototipe memberi keluaran sesuai aturan pada empat dari lima kasus contoh.
4. **Rancangan dan alur:** masukan, proses/aturan atau model, keluaran; sertakan diagram/pseudocode.
5. **Data dan alat:** nyatakan sumber dan jenis data, alasan perlu, cara minimisasi, alat yang dipakai, status persetujuan sekolah, serta alternatif non-AI.
6. **Risiko dan batas:** siapa/apa yang bisa terdampak, skenario gagal/bias, hal yang tidak akan dilakukan, dan cara mengurangi risiko.
7. **Rencana uji dan pembagian waktu:** kasus normal, batas, dan kasus gagal; kapan kelompok akan meninjau ulang.
8. **Penggunaan AI dan sumber:** jika AI digunakan, tulis untuk tugas apa, keluaran mana yang diverifikasi, dan sumber yang dipakai. Jika tidak digunakan, tulis “tidak menggunakan AI”.

## 2. Tahapan rancang–buat–uji–revisi

1. **Pilih dan batasi:** rumuskan masalah kecil, daftar pengguna/keluaran, cek batas keselamatan dan persetujuan alat. Guru dapat meminta perubahan sebelum proyek dimulai.
2. **Rancang:** buat proposal, diagram alur, aturan/data sintetis, kriteria keberhasilan, serta kasus uji. Pisahkan apa yang diketahui dari asumsi.
3. **Buat:** bangun prototipe sekecil mungkin dengan Python, media visual, kartu, atau prosedur unplugged. Tambahkan ML/generatif hanya bila tujuan belajar jelas dan disetujui.
4. **Uji:** jalankan kasus normal, nilai batas, data/masukan tak terduga, dan kasus gagal. Catat hasil aktual dibanding hasil yang diharapkan; jangan menguji dengan data pribadi.
5. **Revisi:** pilih satu masalah yang teramati, ubah desain, dan ulangi kasus terkait. Catat perubahan dan risiko yang tersisa.
6. **Demonstrasikan dan refleksikan:** tunjukkan cara kerja, hasil uji, batas kegunaan, kontribusi anggota, dan penggunaan AI/sumber. Jangan menyatakan prototipe setara sistem profesional atau siap dipakai untuk keputusan nyata.

### Alur debugging untuk peserta didik

**Amati gejala → ulangi dengan masukan aman yang sama → tulis keluaran yang diharapkan dan yang terjadi → telusuri langkah/nilai satu per satu → ubah satu hal → ulangi kasus uji → catat perbaikan dan efek samping.** Jika masalah tidak dapat direproduksi, kumpulkan informasi teknis minimum tanpa data pribadi dan minta bantuan guru. Untuk keluaran AI yang keliru, jangan “debug” dengan menganggap model pasti dapat diperbaiki melalui prompt: verifikasi sumber, nyatakan ketidakpastian, dan gunakan alternatif yang dapat diperiksa.

## 3. Asesmen

Asesmen menilai proses berpikir dan bukti belajar, bukan akses perangkat, kepiawaian memakai layanan AI, atau kompleksitas alat. Beri pilihan lisan, tulisan, visual, dan unplugged yang setara.

| Jenis | Waktu/contoh | Bukti dan tindak lanjut |
|---|---|---|
| Diagnostik | Sesi 1–2: instruksi singkat, pengurutan kartu, atau pertanyaan konsep awal. | Identifikasi pengetahuan awal untuk menyesuaikan dukungan; bukan label atau nilai akhir. |
| Formatif | Sepanjang sesi: tiket keluar, prediksi keluaran, penelusuran variabel, kasus uji, umpan balik teman. | Catatan kemajuan pada algoritma, konsep, verifikasi, dan keamanan; beri kesempatan memperbaiki. |
| Tengah | Sesi 8: tugas individual ringkas berupa menelusuri/memperbaiki pseudocode dan menjelaskan satu konsep. | Periksa pemahaman individual sebelum materi ML/AI; sediakan format aksesibel dan waktu sesuai kebutuhan. |
| Akhir | Sesi 14–16: proposal, prototipe, uji/revisi, demo, refleksi individu. | Gunakan enam aspek rubrik; pertimbangkan bukti proses dan kontribusi individu, bukan hanya presentasi kelompok. |

### Rubrik capstone enam aspek

Gunakan skala **1–4** per aspek. Tetapkan bobot secara terbuka sebelum proyek; jika tidak ada bobot khusus, jumlahkan skor secara setara (maksimum 24). Nilai 2 atau 3 yang tidak secara khusus dijelaskan dapat ditentukan sebagai tingkat antara descriptor yang berdekatan dan disertai umpan balik.

| Aspek | 4 — Kuat | 3 — Tercapai | 2 — Berkembang | 1 — Perlu dukungan |
|---|---|---|---|---|
| 1. Rumusan masalah dan batas | Masalah terukur dan aman; pengguna, batas, dan kriteria keberhasilan jelas. | Masalah dan kriteria cukup jelas; batas utama dinyatakan. | Masalah masih luas atau beberapa kriteria/batas belum jelas. | Tujuan sulit dipahami atau berisiko; belum ada batas/kriteria yang dapat diuji. |
| 2. Algoritma dan konsep komputasi | Alur logis, terurai, dan tepat menggunakan konsep yang dipilih; keputusan desain dijelaskan. | Alur dapat diikuti dan konsep inti umumnya tepat. | Ada langkah/konsep yang tidak jelas atau tidak konsisten. | Solusi belum menunjukkan alur yang dapat dijalankan/ditelusuri. |
| 3. Prototipe dan fungsi | Prototipe berjalan/dapat diperagakan dan memenuhi seluruh kriteria yang disepakati. | Prototipe dapat diperagakan dan memenuhi sebagian besar kriteria. | Hanya sebagian fungsi/prosedur bekerja; bukti uji terbatas. | Belum ada prototipe/prosedur yang dapat diperagakan. |
| 4. Pengujian, debugging, dan revisi | Kasus normal, batas, dan gagal diuji; bukti dibandingkan dan revisi beralasan. | Beberapa kasus relevan diuji dan satu perbaikan dijelaskan. | Uji atau revisi minim dan alasan belum jelas. | Tidak ada bukti pengujian atau perbaikan. |
| 5. Verifikasi, tanggung jawab, dan privasi | Sumber/keluaran diverifikasi; risiko dan batas dijelaskan; data diminimalkan; norma dipatuhi. | Pemeriksaan dan batas utama dinyatakan; tidak ada praktik terlarang. | Verifikasi, sumber, atau mitigasi masih belum lengkap. | Klaim tak terverifikasi atau praktik berisiko belum ditangani; perlu revisi sebelum demo. |
| 6. Kolaborasi dan komunikasi | Kontribusi anggota terlihat; demo ringkas, dapat diikuti, dan menjelaskan batas serta pembelajaran. | Peran dan penjelasan cukup jelas; kontribusi mayoritas anggota tampak. | Kontribusi/penjelasan tidak merata atau sebagian batas tidak disebutkan. | Proses dan kontribusi sulit diketahui; belum dapat menjelaskan cara kerja/batas. |

Jika proyek melanggar batas keselamatan, hentikan pengujian/penggunaan terkait dan arahkan kelompok merancang ulang. Jangan memberi nilai tinggi pada demonstrasi yang menggunakan data atau alat yang tidak disetujui.

## 4. Norma kelas untuk penggunaan AI

- Penggunaan AI opsional; tidak menggunakan AI bukan kekurangan.
- Ikuti aturan guru/sekolah dan batas usia/akun yang berlaku; jangan membuat akun atau menggunakan alat tanpa persetujuan.
- Jangan memasukkan identitas atau data pribadi/sensitif, karya teman tanpa izin, kredensial, atau informasi sekolah yang tidak untuk publik.
- AI dapat keliru, bias, tidak lengkap, atau membuat referensi yang tidak ada. Periksa fakta/kode dengan sumber dan pengujian yang sesuai.
- Catat dengan jujur jika dan bagaimana AI digunakan; peserta didik tetap bertanggung jawab memahami dan menjelaskan hasil.
- Jangan gunakan AI untuk menilai orang, membuat keputusan penting, atau menggantikan pertimbangan manusia.
- Hormati lisensi, atribusi, dan privasi; jangan menyalin keluaran sebagai karya sendiri jika aturan tugas meminta karya mandiri.
- Guru dapat menghentikan penggunaan alat bila persetujuan, keamanan, atau tujuan belajarnya tidak jelas. Berikan alternatif non-AI yang setara.

### Checklist sebelum mulai

- [ ] Tujuan, waktu, tingkat kesiapan, aksesibilitas, dan cara penilaian dipahami.
- [ ] Proyek aman, terbatas, bukan keputusan/pemantauan terhadap orang, dan telah melewati pemeriksaan risiko.
- [ ] Data sintetis/publik telah diperiksa; tidak ada data siswa yang akan diunggah ke AI publik.
- [ ] Alat digital/AI dan akun telah disetujui sekolah; tidak ada instalasi atau layanan yang diasumsikan tersedia.
- [ ] Jalur Python lokal atau jalur visual/unplugged setara telah disiapkan.
- [ ] Proposal menyatakan kriteria keberhasilan, kasus uji, batas klaim, sumber, dan cara menyatakan penggunaan AI.
- [ ] Peserta didik tahu cara meminta bantuan dan cara menghentikan aktivitas yang berisiko.

## 5. Pustaka dan catatan verifikasi

Daftar berikut adalah titik awal untuk guru, bukan daftar lengkap atau penetapan kebijakan Indonesia. Cantumkan tanggal akses dan periksa kembali isi, versi, ketersediaan, serta kesesuaiannya sebelum materi dibagikan atau dijadikan dasar keputusan. Tautan rujukan tidak berarti sumber tersebut telah dipetakan ke kurikulum sekolah.

1. **UNESCO (2024), _AI competency framework for students_.** [Halaman dokumen](https://unesdoc.unesco.org/ark:/48223/pf0000391105). Tautan ini sebelumnya menghasilkan HTTP 403 pada akses otomatis; metadata dan isi penuh belum diverifikasi melalui akses tersebut. Kerangka internasional, bukan kurikulum resmi Indonesia.
2. **UNESCO (2023), _Guidance for generative AI in education and research_.** [Halaman dokumen](https://unesdoc.unesco.org/ark:/48223/pf0000386693). Tautan ini sebelumnya menghasilkan HTTP 403 pada akses otomatis; metadata dan isi penuh belum diverifikasi melalui akses tersebut. Panduan internasional; tinjau dokumen penuh sebelum mengutip rekomendasi tertentu.
3. **UNICEF Innocenti, _Policy Guidance on AI for Children_.** [Halaman panduan](https://www.unicef.org/innocenti/reports/policy-guidance-ai-children). Laman yang diperiksa menyebut versi 3; periksa versi dan tanggal pemutakhiran langsung sebelum digunakan.
4. **Republik Indonesia, Undang-Undang Nomor 27 Tahun 2022 tentang Pelindungan Data Pribadi.** [Basis data peraturan BPK](https://peraturan.bpk.go.id/Details/229798/uu-no-27-tahun-2022). Metadata basis data BPK menyebut status berlaku. Rujukan ini bukan analisis hukum atau jaminan kepatuhan kegiatan; sekolah perlu memeriksa naskah dan status terkini melalui kanal resmi/JDIH.
5. **Computer Science Teachers Association (CSTA), _K–12 Computer Science Standards_.** [Situs CSTA](https://csteachers.org/pk12standards/). Kerangka standar Amerika Serikat; bukan standar atau kurikulum Indonesia.
6. **Scratch Educator Guides.** [Panduan pendidik Scratch](https://www.scratchfoundation.org/learn/for-educators). Sumber pengayaan untuk aktivitas kreatif; cek ketersediaan, persyaratan akun, dan kesesuaian alat sebelum penggunaan di sekolah.
7. **Dokumentasi Python resmi.** [Tutorial Python](https://docs.python.org/3/tutorial/). Referensi teknis untuk guru/peserta didik; pilih bagian sesuai kesiapan, bukan pengganti rancangan pedagogis.

**Verifikasi lokal:** sebelum pelaksanaan, sekolah mencocokkan rancangan ini dengan kurikulum, kebijakan perlindungan data, prosedur penggunaan perangkat/akun, serta aturan lain yang relevan dan terkini melalui kanal resmi/JDIH yang sesuai. Dokumen ini sengaja tidak membuat klaim pemetaan atau kepatuhan resmi.
