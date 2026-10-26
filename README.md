# IF25-11001 Algoritma Pemrograman

Algoritma Pemrograman membangun cara berpikir komputasional mahasiswa Teknik Informatika lewat pseudocode, flowchart, dan trace table, sebelum algoritma itu ditulis dalam C++ di mata kuliah pasangannya, [Praktikum Pemrograman (IF25-11002)](https://github.com/informatika-itera/IF25-11002-Praktikum-Pemrograman). Prinsipnya: pikirkan dulu, tulis kodenya kemudian. Topik yang sama dibahas di minggu yang sama, Algoritma di kertas, Praktikum di komputer.

Setiap pertemuan punya tiga bahan yang saling melengkapi: slide di `01 Slide/` untuk kelas, lembar latihan bertingkat di `02 Latihan/` yang dikerjakan di kertas, dan modul di `03 Modul/` untuk belajar mandiri. Dokumen resmi mata kuliah ada di akar repo: [Rencana Pembelajaran Semester](Rencana%20Pembelajaran%20Semester.pdf) dan [RPS MK IF25-11001](RPS_MK_IF25-11001.pdf).

## Identitas Mata Kuliah

| Data | Deskripsi |
|---|---|
| Kode | IF25-11001 |
| Nama | Algoritma Pemrograman |
| Bobot | 2 SKS teori (16 pertemuan, 100 menit) |
| Semester | 1 (Ganjil) |
| Prasyarat | Tidak ada |
| Mata kuliah pasangan | IF25-11002 Praktikum Pemrograman |
| Metode | Problem-Based Learning; pseudocode, flowchart, dan trace table di kertas |
| Program Studi | S1 Teknik Informatika, Institut Teknologi Sumatera |
| Tim pengajar | Tim Pengajar Algoritma Pemrograman, Program Studi Teknik Informatika ITERA |
| Tahun | 2026 |

## Capaian Pembelajaran

**CPL06**: Mampu menganalisis dan mengimplementasi konsep dasar matematika, statistika, algoritma dan sistem komputer sebagai fondasi komputasional.

| CPMK | Deskripsi | Bobot |
|---|---|---|
| CPMK0607 | Mahasiswa mampu **menerapkan** konsep dasar algoritma dan sistem komputer untuk menyelesaikan masalah komputasi (C3) | 50% |
| CPMK0608 | Mahasiswa mampu **menjelaskan** konsep dasar algoritma dan sistem komputer untuk menyelesaikan masalah komputasi (C2) | 50% |

Setiap pertemuan menurunkan kedua CPMK menjadi Sub-CPMK n.1 (merancang pseudocode, CPMK0607) dan n.2 (menelusuri dan menjelaskan, CPMK0608). Rumusan lengkapnya ada di slide penyelarasan dan modul setiap pertemuan.

## Siklus Setiap Pertemuan

| Fase | Waktu | Isi |
|---|---|---|
| Pembuka | 10 menit | Soal pertemuan sebelumnya tanpa catatan, lalu masalah minggu ini |
| Coba dulu | 15 menit | Misi berkelompok sebelum ada penjelasan, lalu debrief |
| Materi | 35 menit | Tebak lalu buktikan, trace table, contoh setengah jadi, pertanyaan engsel, kasus detektif |
| Latihan | 20 menit | Lembar latihan bertingkat di `02 Latihan/` |
| Papan | 10 menit | Dua mahasiswa yang diundi menjelaskan satu soal |
| Exit ticket | 10 menit | Satu soal per Sub-CPMK dan satu kalimat refleksi, tanpa catatan |

## Peta 16 Pertemuan

Urutan pertemuan disamakan dengan Praktikum Pemrograman. Setelah UTS, String lanjutan (dua penunjuk, palindrom, frekuensi karakter) masuk ke P10, lalu Searching (P11), Sorting (P12), dan Fungsi (P13). Karena itu pencarian dan pengurutan ditulis sebagai pseudocode langsung di P11 dan P12, lalu dibungkus menjadi fungsi dan prosedur di P13.

| P | Topik | Fokus algoritma | Pasangan di Praktikum | Asesmen |
|---|---|---|---|---|
| P1 | Computational Thinking | flowchart, pseudocode, langkah pemecahan masalah | Hello World dan Struktur Program C++ | Exit ticket, tugas |
| P2 | Tipe Data, Variabel dan Ekspresi | model memori, trace table | Variabel, Tipe Data, Ekspresi, dan Input | Exit ticket, tugas |
| P3 | Operator dan Precedence | tabel kebenaran, urutan evaluasi | Operator dan Precedence | Exit ticket, tugas |
| P4 | Percabangan | pohon keputusan, flowchart | Percabangan | Exit ticket, PBL 1 mulai |
| P5 | Perulangan Bagian 1 | trace perulangan, counting | Perulangan Bagian 1 | Exit ticket, tugas |
| P6 | Perulangan Bagian 2 dan Pattern | perulangan bersarang, kompleksitas | Perulangan Bagian 2 dan Pola | Exit ticket, PBL 1 dikumpulkan |
| P7 | Review dan Simulasi UTS | konsolidasi P1 sampai P6 | Review dan Simulasi UTS | Simulasi UTS |
| P8 | **Ujian Tengah Semester** | | Ujian Tengah Semester | UTS 30% |
| P9 | Array Satu Dimensi | alamat memori, traversal, statistik, menggeser | Array Satu Dimensi | Exit ticket, tugas, PBL 2 mulai |
| P10 | Array Dua Dimensi dan String | perulangan bersarang, diagonal, dua penunjuk, palindrom | Array Dua Dimensi dan String | Exit ticket, tugas, PBL 2 Milestone 1 |
| P11 | Searching | linear dan binary search, $O(n)$ lawan $O(\log n)$ | Searching | Exit ticket, tugas, PBL 2 Milestone 2 |
| P12 | Sorting | bubble dan selection sort, perbandingan dan penukaran | Sorting | Exit ticket, tugas, PBL 2 dikumpulkan |
| P13 | Fungsi dan Modularitas | parameter, nilai kembali, REF, tumpukan panggilan | Fungsi dan Modularitas | Exit ticket, tugas, PBL 3 mulai |
| P14 | Rekursi dan Struct | basis, pohon pemanggilan, array of struct | Rekursi dan Struct | Exit ticket, tugas, PBL 3 Milestone 2 |
| P15 | Review dan Simulasi UAS | konsolidasi P9 sampai P14 | Review dan Simulasi UAS | Simulasi UAS, PBL 3 dikumpulkan |
| P16 | **Ujian Akhir Semester** | | Ujian Akhir Semester | UAS 30% |

## Penilaian

Penilaian mengikuti RPS.

| Komponen | Pelaksanaan | Bobot |
|---|---|---|
| UTS | P8, lima soal, 120 menit, satu lembar A4 ringkasan tulisan tangan | 30% |
| UAS | P16, enam soal, 120 menit, dua lembar A4 catatan tulisan tangan bolak-balik | 30% |
| Weekly Mini-Problem | exit ticket dan tugas mingguan (pseudocode dan trace) setiap pertemuan | 15% |
| PBL | PBL 1 (6%), PBL 2 (7%), PBL 3 (7%), kelompok 3 sampai 4 orang | 20% |
| Partisipasi dan peer review | keaktifan diskusi, presentasi papan, review algoritma teman | 5% |
| **Total** | | **100%** |

Konversi nilai huruf: A 85 ke atas, AB 75, B 65, BC 55, C 45, D 35, E di bawah 35.

**Komponen UTS.** Flowchart dari narasi 15% (CPMK0608), penulisan pseudocode 25% (CPMK0607), trace table 30% (CPMK0607), analisis benar atau salah 15% (CPMK0608), desain solusi 15% (CPMK0607).

**Komponen UAS.** Trace array dan memori 15%, analisis pencarian 15%, trace pengurutan 20%, desain fungsi dan struct 20%, trace rekursi 10% (semuanya CPMK0607), dan studi kasus integrasi 20% (CPMK0607 dan CPMK0608). Kisi-kisi dan contoh soalnya ada di `02 Latihan/P16 - Ujian Akhir Semester - Kisi-kisi/`; untuk UTS di `02 Latihan/P8 - Ujian Tengah Semester - Kisi-kisi/`.

**Rubrik PBL.** Analisis masalah 20%, desain algoritma 30%, analisis efisiensi 15%, dokumen desain 20%, presentasi dan peer review 15%.

**Penggunaan AI.** Boleh dipakai di rumah untuk memahami konsep atau memeriksa trace yang sudah kalian tulis sendiri, tidak untuk meminta solusi utuh. Coba dulu, exit ticket, simulasi, UTS, dan UAS dikerjakan tanpa AI.

## Proyek PBL

| Proyek | Rentang | Fokus |
|---|---|---|
| PBL 1, Smart Calculator | P4 sampai P6 | flowchart, pohon keputusan, dan pseudocode untuk BMI, konversi suhu, diskon bertingkat |
| PBL 2, Data Analyzer | P9 sampai P12 | statistik array, analisis teks, pencarian, pengurutan |
| PBL 3, Student Record System | P13 sampai P15 | fungsi modular, struct Mahasiswa, minimal satu fungsi rekursif |

## Bahan per Pertemuan

| P | Slide | Latihan | Modul |
|---|---|---|---|
| P1 | `01 Slide/P1 Computational Thinking.pdf` | `02 Latihan/P1 - Computational Thinking - Latihan/` | `03 Modul/Modul 01 - Computational Thinking.pdf` |
| P2 | `01 Slide/P2 Tipe Data, Variabel dan Ekspresi.pdf` | `02 Latihan/P2 - Variabel dan Ekspresi - Latihan/` | `03 Modul/Modul 02 - Tipe Data, Variabel dan Ekspresi.pdf` |
| P3 | `01 Slide/P3 Operator dan Precedence.pdf` | `02 Latihan/P3 - Operator - Latihan/` | `03 Modul/Modul 03 - Operator dan Precedence.pdf` |
| P4 | `01 Slide/P4 Percabangan.pdf` | `02 Latihan/P4 - Percabangan - Latihan/` | `03 Modul/Modul 04 - Percabangan.pdf` |
| P5 | `01 Slide/P5 Perulangan Bagian 1.pdf` | `02 Latihan/P5 - Perulangan 1 - Latihan/` | `03 Modul/Modul 05 - Perulangan Bagian 1.pdf` |
| P6 | `01 Slide/P6 Perulangan Bagian 2 dan Pattern.pdf` | `02 Latihan/P6 - Perulangan 2 dan Pola - Latihan/` | `03 Modul/Modul 06 - Perulangan Bagian 2 dan Pattern.pdf` |
| P7 | `01 Slide/P7 Review dan Simulasi UTS.pdf` | `02 Latihan/P7 - Review dan Simulasi UTS - Simulasi/` | `03 Modul/Modul 07 - Review dan Simulasi UTS.pdf` |
| P8 | `01 Slide/P8 Ujian Tengah Semester.pdf` | `02 Latihan/P8 - Ujian Tengah Semester - Kisi-kisi/` | `03 Modul/Modul 08 - Ujian Tengah Semester.pdf` |
| P9 | `01 Slide/P9 Array Satu Dimensi.pdf` | `02 Latihan/P9 - Array 1D - Latihan/` | `03 Modul/Modul 09 - Array Satu Dimensi.pdf` |
| P10 | `01 Slide/P10 Array Dua Dimensi dan String.pdf` | `02 Latihan/P10 - Array 2D dan String - Latihan/` | `03 Modul/Modul 10 - Array Dua Dimensi dan String.pdf` |
| P11 | `01 Slide/P11 Searching.pdf` | `02 Latihan/P11 - Searching - Latihan/` | `03 Modul/Modul 11 - Searching.pdf` |
| P12 | `01 Slide/P12 Sorting.pdf` | `02 Latihan/P12 - Sorting - Latihan/` | `03 Modul/Modul 12 - Sorting.pdf` |
| P13 | `01 Slide/P13 Fungsi dan Modularitas.pdf` | `02 Latihan/P13 - Fungsi - Latihan/` | `03 Modul/Modul 13 - Fungsi dan Modularitas.pdf` |
| P14 | `01 Slide/P14 Rekursi dan Struct.pdf` | `02 Latihan/P14 - Rekursi dan Struct - Latihan/` | `03 Modul/Modul 14 - Rekursi dan Struct.pdf` |
| P15 | `01 Slide/P15 Review dan Simulasi UAS.pdf` | `02 Latihan/P15 - Review dan Simulasi UAS - Simulasi/` | `03 Modul/Modul 15 - Review dan Simulasi UAS.pdf` |
| P16 | `01 Slide/P16 Ujian Akhir Semester.pdf` | `02 Latihan/P16 - Ujian Akhir Semester - Kisi-kisi/` | `03 Modul/Modul 16 - Ujian Akhir Semester.pdf` |

## Struktur Repo

```
.
├── README.md
├── Rencana Pembelajaran Semester.pdf
├── RPS_MK_IF25-11001.pdf
├── 01 Slide/        # slide PDF per pertemuan
├── 02 Latihan/      # satu folder per pertemuan: lembar latihan PDF dan README
└── 03 Modul/        # modul belajar mandiri PDF
```

Kunci latihan dan simulasi (`kunci/`) serta sumber bahan (`src/`) disimpan tim pengajar dan tercantum di `.gitignore`, sehingga tidak ikut ter-commit. Versi PowerPoint setiap slide, lengkap dengan catatan pengajar, dibagikan terpisah.

## Cara Memakai Lembar Latihan

Semua latihan dikerjakan di kertas dengan pseudocode dan trace table, tanpa komputer. Angka di sebagian soal diambil dari NIM: $A$ adalah digit terakhir (kalau 0, pakai 5) dan $B$ digit kedua dari belakang (kalau 0, pakai 3). Implementasi C++ dari algoritma yang sama dikerjakan di hands-on Praktikum Pemrograman pada minggu yang sama.

## Referensi

1. Cormen, T. H. dkk. *Introduction to Algorithms*. MIT Press.
2. Deitel, P. dan Deitel, H. *C++ How to Program*. Pearson.
3. Gaddis, T. *Starting Out with C++: From Control Structures through Objects*. Pearson.
4. Sedgewick, R. dan Wayne, K. *Algorithms*. Addison-Wesley.
5. Bhargava, A. *Grokking Algorithms*. Manning.
6. [visualgo.net](https://visualgo.net), [pythontutor.com/cpp](https://pythontutor.com/cpp.html), [cs50.harvard.edu](https://cs50.harvard.edu)
