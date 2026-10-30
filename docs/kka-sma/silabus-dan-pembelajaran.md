# Silabus dan Pembelajaran Koding dan Kecerdasan Artifisial (KKA) SMA

> **Status dokumen:** rancangan adaptif/draf bahan ajar, bukan kurikulum resmi pemerintah dan bukan pemetaan resmi terhadap kurikulum nasional. Sekolah perlu mencocokkan tujuan, kalender, perangkat, serta kebijakan lokal dengan dokumen kurikulum dan JDIH yang berlaku dan terkini sebelum digunakan.

## 1. Gambaran umum

Rancangan ini berisi 16 pertemuan, masing-masing 90 menit (24 jam waktu belajar). Guru dapat memadatkan, memperluas, atau menggabungkan sesi sesuai waktu belajar, kesiapan peserta didik, akses perangkat, dan konteks sekolah. Pembelajaran berpusat pada pemecahan masalah aman dan terbatas, bukan pada penggunaan AI untuk mengambil keputusan tentang orang.

**Prasyarat:** tidak diperlukan pengalaman pemrograman. Siapkan pilihan aktivitas tanpa perangkat untuk seluruh konsep inti. Penggunaan akun, perangkat lunak, layanan daring, atau AI hanya dilakukan setelah disetujui sekolah dan mengikuti prosedur yang berlaku.

### Tujuan belajar terukur

Pada akhir rangkaian, peserta didik diharapkan dapat:

1. Memecah satu masalah terbatas menjadi submasalah, mengidentifikasi pola dan informasi penting, lalu menyusun abstraksi yang relevan; bukti: diagram atau uraian langkah untuk satu masalah.
2. Menuliskan algoritma dengan urutan, percabangan, dan pengulangan serta menjelaskan masukan, proses, dan keluaran; bukti: pseudocode/diagram alir dan sekurangnya tiga kasus uji.
3. Membuat atau menelusuri program sederhana dengan variabel, kondisi, loop, fungsi, dan data menggunakan Python, pseudocode, atau aktivitas unplugged; bukti: prototipe yang memenuhi kriteria uji yang disepakati.
4. Membedakan program deterministik berbasis aturan, sistem machine learning (ML) yang mempelajari pola dari contoh/data, dan AI generatif yang menghasilkan keluaran; bukti: mengklasifikasikan contoh dan menyebutkan alasan serta keterbatasannya.
5. Menguji keluaran program atau AI terhadap sumber/kasus acuan, menemukan setidaknya satu kesalahan atau ketidakpastian, dan memperbaiki atau membatasi klaim; bukti: catatan uji dan revisi.
6. Menerapkan praktik dasar keamanan dan tanggung jawab: menghindari data pribadi, mengenali bias/kegagalan generalisasi, menyatakan penggunaan AI, dan tidak mengandalkan keluaran tanpa pemeriksaan; bukti: checklist risiko dan refleksi proyek.

Tujuan dapat dinilai melalui artefak, penjelasan lisan, kerja kelompok, observasi, atau tugas tanpa komputer. Nilai bukan ukuran kemampuan peserta didik untuk “membuat AI” secara industri.

## 2. Peta 16 pertemuan

| Sesi | Fokus dan tujuan utama | Kegiatan/bukti belajar |
|---|---|---|
| 1 | Orientasi, kesepakatan aman, pemecahan masalah | Menyusun instruksi untuk tugas sederhana, menemukan ambiguitas, dan menulis aturan kelas; bukti: algoritma awal dan kesepakatan kelas. |
| 2 | Berpikir komputasional dan algoritma | Dekomposisi, pola, abstraksi, urutan; menyusun pseudocode atau diagram alir. |
| 3 | Variabel, tipe data, masukan-keluaran | Menelusuri nilai dan membangun program kecil atau simulasi kartu nilai. |
| 4 | Kondisi dan keputusan | Membuat aturan if/else, menguji nilai batas dan kasus alternatif. |
| 5 | Pengulangan | Memilih loop yang sesuai, menelusuri iterasi, mencegah loop tak berujung. |
| 6 | Fungsi dan modularitas | Membagi solusi menjadi fungsi; menjelaskan parameter, keluaran, dan penggunaan ulang. |
| 7 | Data dan representasi | Mengelompokkan data sintetis/publik yang diperiksa, membaca tabel kecil, membahas kualitas dan minimisasi data. |
| 8 | Debugging dan asesmen tengah | Menjelaskan strategi mencari bug; asesmen individual singkat konsep dan penelusuran algoritma. |
| 9 | Aturan deterministik, ML, dan AI generatif | Mengelompokkan contoh sistem berdasarkan cara kerja, masukan, dan jenis keluaran. |
| 10 | Bias dan generalisasi | Menguji model/aturan mainan pada contoh yang beragam; mencatat keterbatasan dan kasus gagal. |
| 11 | Verifikasi keluaran AI | Memeriksa klaim dengan rujukan yang dapat ditelusuri, menguji contoh, mencatat ketidakpastian. |
| 12 | Prompting dan iterasi | Menulis instruksi dengan tujuan, konteks aman, batasan, serta kriteria keluaran; membandingkan hasil tanpa menganggapnya benar. |
| 13 | Etika, privasi, keamanan, dan dampak | Menilai skenario penggunaan; menerapkan checklist privasi/AI dan mengusulkan alternatif non-AI. |
| 14 | Capstone: rancang dan bangun | Kelompok 2–4 orang membuat prototipe aman sesuai brief pada dokumen proyek dan asesmen. |
| 15 | Capstone: uji, revisi, persiapan demo | Menjalankan kasus uji, mendokumentasikan revisi, memeriksa risiko dan atribusi. |
| 16 | Demo, umpan balik, refleksi | Menunjukkan prototipe, menjelaskan batasnya, menerima umpan balik, dan refleksi individu. |

### Pola waktu 90 menit

Gunakan pola berikut sebagai titik awal untuk **setiap** pertemuan; sesuaikan dengan kebutuhan, jeda, dan aksesibilitas kelas:

| Durasi | Tahap |
|---|---|
| 0–10 menit | Pembuka, tujuan, pemeriksaan kesiapan, dan pengingat aturan aman. |
| 10–25 menit | Pemantik/diagnostik singkat dan menghubungkan materi sebelumnya. |
| 25–45 menit | Penjelasan konsep dengan contoh kecil dan pemeriksaan pemahaman. |
| 45–70 menit | Praktik individu/berpasangan/kelompok, dengan opsi unplugged setara. |
| 70–82 menit | Uji, debugging, berbagi hasil atau umpan balik teman. |
| 82–90 menit | Tiket keluar/refleksi dan penjelasan tindak lanjut. |

## 3. Panduan rinci untuk sesi pertama

**Tujuan sesi:** peserta didik mampu (a) menjelaskan satu contoh algoritma sebagai langkah yang jelas dan berurutan, (b) menemukan setidaknya satu instruksi ambigu, dan (c) menyebutkan dua aturan untuk melindungi diri dan teman saat belajar dengan teknologi.

**Bahan:** kartu langkah atau kertas, papan tulis, dan contoh sederhana yang tidak membutuhkan data pribadi. Tidak perlu akun atau layanan daring.

1. **0–10 menit — Pembuka:** jelaskan bahwa KKA mencakup cara berpikir, menulis instruksi, memeriksa hasil, dan membicarakan dampak; tidak semua kegiatan membutuhkan komputer atau AI. Nyatakan bahwa dokumen ini rancangan kelas, bukan kurikulum resmi.
2. **10–20 menit — Diagnostik ringan:** minta peserta didik menulis langkah untuk mengatur benda-benda kelas ke dalam urutan tertentu. Jangan meminta informasi pribadi. Terima gambar, lisan, atau teks.
3. **20–35 menit — Demonstrasi ambiguitas:** guru mengikuti instruksi contoh secara harfiah (misalnya “susun kartu berdasarkan angka”) dan bertanya: urut naik atau turun? Bagaimana jika nilainya sama? Perbaiki instruksi bersama.
4. **35–55 menit — Tantangan berpasangan:** satu peserta didik menjadi “pelaksana”, yang lain “penyusun algoritma” untuk mengurutkan lima kartu angka. Tukar peran; uji kasus nilai sama dan urutan terbalik.
5. **55–68 menit — Refleksi:** hubungkan kegiatan dengan dekomposisi (langkah kecil), pola (membandingkan nilai), dan pengujian (mencoba lebih dari satu kasus).
6. **68–80 menit — Kesepakatan kelas:** susun aturan singkat, termasuk tidak memasukkan data pribadi/rahasia ke layanan AI, memeriksa jawaban, menyatakan penggunaan AI, serta meminta bantuan sebelum menggunakan alat digital.
7. **80–90 menit — Tiket keluar:** setiap peserta didik menulis satu algoritma pendek, satu hal yang masih membingungkan, dan satu praktik aman yang akan dilakukan. Sediakan jawaban lisan/gambar sebagai alternatif.

**Penilaian:** gunakan hasil diagnostik untuk mengatur dukungan, bukan untuk memberi label kemampuan. Beri umpan balik pada kejelasan, urutan, dan pengujian instruksi.

## 4. Panduan sesi koding: variabel, kondisi, dan pengujian

Python adalah salah satu pilihan, bukan prasyarat atau satu-satunya cara mencapai tujuan. Sebelum sesi, pastikan lingkungan lokal telah disetujui sekolah; jalankan contoh dengan nilai contoh saja. Tidak ada akun, jaringan, paket tambahan, berkas pribadi, atau layanan AI yang diperlukan.

**Konsep yang diperkenalkan:** variabel menyimpan nilai; `input` membaca teks dari pengguna; konversi tipe mengubah teks menjadi bilangan; kondisi memilih cabang; `print` menampilkan hasil. Bedakan validasi masukan sederhana dari jaminan keamanan menyeluruh.

Contoh aman dan deterministik:

```python
nilai_teks = input("Masukkan bilangan bulat 0 sampai 100: ")

if nilai_teks.isdigit():
    nilai = int(nilai_teks)
    if 0 <= nilai <= 100:
        if nilai >= 75:
            print("Memenuhi batas contoh.")
        else:
            print("Belum memenuhi batas contoh.")
    else:
        print("Nilai harus berada pada rentang 0 sampai 100.")
else:
    print("Masukkan angka bulat saja.")
```

Tegaskan bahwa batas 75 di sini hanya angka contoh untuk mengajarkan kondisi, bukan standar penilaian atau kebijakan sekolah. Uji masukan `80`, `40`, `101`, `-1`, dan `abc`; diskusikan mengapa `-1` ditolak oleh pemeriksaan digit dan bagaimana desain masukan dapat diperluas jika kebutuhan pembelajaran menghendaki bilangan negatif. Contoh ini tidak membaca file, menggunakan jaringan, menyimpan masukan, atau menilai seseorang.

**Langkah mengajar yang disarankan:** prediksi keluaran sebelum menjalankan; tandai nilai tiap variabel; ubah satu kondisi; uji nilai tepat di batas dan di luar batas; minta peserta didik menjelaskan satu perbaikan. Guru dapat mengawali dengan pseudocode:

```text
baca teks
jika teks berisi digit:
    ubah menjadi bilangan
    jika bilangan berada pada rentang contoh:
        tampilkan hasil sesuai aturan
    jika tidak: beri pesan rentang
jika tidak: beri pesan format
```

### Alternatif unplugged setara

- **Variabel:** kartu berlabel `nilai` dan kartu angka; peserta didik mengganti kartu untuk menelusuri perubahan.
- **Kondisi:** kartu “jika/maka/jika tidak” dan masukan angka; kelompok memilih cabang yang tepat.
- **Loop:** ulangi instruksi untuk setiap kartu dalam tumpukan; berhenti saat kartu habis.
- **Fungsi:** buat kartu prosedur bernama dengan masukan dan keluaran yang dinyatakan.
- **Debugging:** satu langkah sengaja dihilangkan atau diubah; kelompok menemukan kasus yang gagal dan memperbaiki instruksi.

Alternatif tersebut dinilai dengan kriteria tujuan yang sama, bukan sebagai tugas yang lebih rendah nilainya.

## 5. Inklusi dan manajemen kelas

- Tawarkan representasi teks, diagram, contoh konkret, demonstrasi, dan penjelasan lisan; izinkan peserta didik menunjukkan pemahaman melalui tulisan, lisan, gambar, atau prototipe.
- Pecah tugas menjadi langkah kecil, sediakan kosakata kunci dan contoh awal, serta beri waktu tambahan atau pasangan dukungan sesuai kebutuhan.
- Dalam kerja kelompok, rotasikan peran (perancang, pencatat, penguji, penyaji) agar kontribusi tidak hanya diukur dari kecepatan mengetik.
- Hindari meminta peserta didik mengungkap pengalaman pribadi untuk contoh data atau isu AI. Gunakan skenario dan data sintetis.
- Atur penggunaan perangkat dan akun hanya sesuai persetujuan sekolah; siapkan aktivitas kertas bila jaringan/perangkat tidak tersedia.
- Bahas kesalahan sebagai informasi untuk memperbaiki solusi; jangan mempermalukan peserta didik karena bug atau karena memilih opsi non-AI.

## 6. Checklist privasi dan penggunaan AI

Sebelum kegiatan digital atau AI, guru/kelompok memastikan:

- [ ] Sekolah telah menyetujui alat, akun, dan tujuan penggunaan sesuai prosedur yang berlaku.
- [ ] Tidak ada data siswa, identitas, kontak, foto, suara, lokasi, kredensial, data sensitif, atau karya yang belum diizinkan dimasukkan ke layanan AI publik.
- [ ] Data yang digunakan sintetis atau publik dan telah diperiksa kesesuaian serta lisensinya; data diminimalkan.
- [ ] Ada alternatif non-AI setara dan peserta didik memahami bahwa AI tidak wajib digunakan.
- [ ] Keluaran diperiksa terhadap kasus uji dan sumber tepercaya; ketidakpastian dan penggunaan AI dicatat.
- [ ] Penggunaan tidak mengambil keputusan penting tentang orang, tidak melakukan pemantauan, dan tidak mengumpulkan data yang tidak diperlukan.
- [ ] Berkas, akun, dan hasil belajar disimpan/dihapus mengikuti arahan sekolah; jangan membagikan tautan/hasil yang mengungkap identitas.

Jika satu pemeriksaan penting tidak terpenuhi, hentikan penggunaan alat tersebut dan lanjutkan dengan alternatif offline/non-AI.

## 7. Batas klaim dan penggunaan rancangan

Dokumen ini merupakan bahan rancangan pembelajaran, bukan pengesahan, interpretasi hukum, rekomendasi produk, jaminan kepatuhan, ataupun pengganti kebijakan sekolah. Jangan mengklaim bahwa materi ini diwajibkan, disahkan, atau dipetakan secara resmi oleh pemerintah. Sekolah perlu memeriksa kurikulum dan kebijakan yang relevan melalui dokumen resmi/JDIH terkini serta menyesuaikan dengan kebutuhan dan aturan setempat. Ringkasan referensi dan status verifikasinya tersedia dalam [Proyek, asesmen, dan pustaka](proyek-asesmen-dan-pustaka.md).
