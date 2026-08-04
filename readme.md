# Algoritma Pemrograman (IF25-11001)

Mata kuliah **Algoritma Pemrograman** membangun fondasi *computational thinking* dan logika pemrograman mahasiswa Teknik Informatika melalui pseudocode dan flowchart, sebelum diimplementasikan dalam bahasa C++ pada mata kuliah sinergi **Praktikum Pemrograman (IF25-11002)**.

Repo ini berisi seluruh materi ajar: slide deck per pertemuan, RPS, contoh UTS/UAS, dan dokumen sinkronisasi dengan Praktikum.

## Informasi Umum

| | |
|---|---|
| **Kode Mata Kuliah** | IF25-11001 |
| **Nama Mata Kuliah** | Algoritma Pemrograman |
| **Bobot** | 2 SKS (Teori) |
| **Program Studi** | S1 Teknik Informatika |
| **Institusi** | Institut Teknologi Sumatera (ITERA) |
| **Dosen Penyusun** | [M Habib Algifari](https://github.com/mh4Scripts) |
| **Mata Kuliah Sinergi** | IF25-11002 - Praktikum Pemrograman (2 SKS) |

## Peta 16 Pertemuan

| Pertemuan | Topik | Fase |
|:---:|---|---|
| P1 | Computational Thinking | Fondasi |
| P2 | Tipe Data, Variabel dan Ekspresi | Fondasi |
| P3 | Operator dan Precedence | Fondasi |
| P4 | Percabangan | Kontrol Alur |
| P5 | Perulangan 1 | Kontrol Alur |
| P6 | Perulangan 2 dan Pattern | Kontrol Alur |
| P7 | Review dan Simulasi UTS | UTS |
| P8 | **UTS** | UTS |
| P9 | Array 1D | Struktur Data |
| P10 | Array 2D dan String | Struktur Data |
| P11 | Searching | Algoritma Klasik |
| P12 | Sorting | Algoritma Klasik |
| P13 | Fungsi dan Modularitas | Abstraksi |
| P14 | Rekursi dan Struct/Record | Abstraksi |
| P15 | Review dan Simulasi UAS | UAS |
| P16 | **UAS** | UAS |

## Capaian Pembelajaran dan Skema Penilaian

Penilaian mengacu pada dua CPMK yang dinilai **paralel** setiap pertemuan — **CPMK0607** melalui Tugas mingguan, dan **CPMK0608** melalui Exit Ticket — ditambah kontribusi PBL, UTS, dan UAS. Masing-masing CPMK berkontribusi maksimal **50 poin** terhadap nilai akhir (total 100).

| Pertemuan | CPMK0607 | Bobot | CPMK0608 | Bobot |
|:---:|---|:---:|---|:---:|
| 1 | Tugas | 1 | Exit Ticket | 1 |
| 2 | Tugas | 1 | Exit Ticket | 1 |
| 3 | Tugas | 1 | Exit Ticket | 1 |
| 4 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 5 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 6 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 7 | UTS | 12.5 | UTS | 12.5 |
| 9 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 10 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 11 | Tugas, PBL | 2+1.5 | Exit Ticket, PBL | 2+1.5 |
| 12 | Tugas | 2 | Exit Ticket | 2 |
| 13 | Tugas, PBL | 2+1 | Exit Ticket, PBL | 2+1 |
| 14 | Tugas, PBL | 1+1 | Exit Ticket, PBL | 1+1 |
| 15 | UAS, PBL | 12.5+1.5 | UAS, PBL | 12.5+1.5 |
| | **TOTAL CPMK0607** | **50** | **TOTAL CPMK0608** | **50** |

> **Catatan kelulusan:** nilai minimum lulus per CPMK adalah **50**. Jika salah satu CPMK tidak lulus, mahasiswa wajib mengikuti **remedial** agar dapat lulus mata kuliah.
>
> Pertemuan 8 (UTS) dan Pertemuan 16 (UAS) adalah pelaksanaan ujian; bobotnya tercatat pada baris Pertemuan 7 dan Pertemuan 15.

## Proyek PBL (Project-Based Learning)

| Proyek | Rentang | Fokus |
|---|:---:|---|
| PBL#1 — Smart Calculator | P3–P6 | Operator dan percabangan |
| PBL#2 — Data Analyzer | P9–P12 | Statistik array, searching, sorting |
| PBL#3 — Student Record System | P13–P15 | Fungsi modular, rekursi, struct |

## Sinergi dengan Praktikum Pemrograman

Setiap pertemuan Algoritma (2 SKS Teori) dirancang sejajar dengan Praktikum Pemrograman — IF25-11002 (2 SKS): konsep dan pseudocode dibahas di Algoritma, lalu diimplementasikan dalam C++ pada sesi Praktikum di minggu yang sama. Detail pemetaan ada di [`Briefing_Sinkronisasi_Algoritma_Praktikum.md`](./Briefing_Sinkronisasi_Algoritma_Praktikum.md).

## Struktur Direktori

```
.
├── README.md
├── Rencana Pembelajaran Semester.pdf
├── slides/
│   ├── P1 - Computational Thinking.pdf
│   ├── P2 - TipeData Variabel Ekspresi.pdf
│   ├── P3 - Operator Precedence.pdf
│   ├── P4 - Percabangan.pdf
│   ├── P5 - Perulangan1.pdf
│   ├── P6 - Perulangan2 Pattern.pdf
│   ├── P7 - Review SimulasiUTS.pdf
│   ├── P9 - Array1D.pdf
│   ├── P10 - Array2D String.pdf
│   ├── P11 - Searching.pdf
│   ├── P12 - Sorting.pdf
│   ├── P13 - Fungsi.pdf
│   ├── P14 - Rekursi Struct.pdf
│   └── P15 - Review SimulasiUAS.pdf
└── ujian/
    ├── Contoh UTS Algoritma Pemrograman.pdf
    └── Contoh UAS Algoritma Pemrograman.pdf
```

## Format Setiap Slide Deck

Semua deck (P1–P7, P9–P15) mengikuti struktur konsisten: Cover → Review pertemuan sebelumnya → Sub-CPMK → Outline → Hook → Materi inti → Workshop → Jawaban → Algorithm Detective → Progress PBL → Ringkasan → Exit Ticket → Tugas → Referensi → Penutup.

## Referensi Utama

- Cormen, Leiserson, Rivest, Stein — *Introduction to Algorithms* (CLRS)
- Deitel & Deitel — *C++ How to Program*
- Gaddis — *Starting Out with C++*
- Wing, J.M. (2006) — "Computational Thinking", *Communications of the ACM*
- [visualgo.net](https://visualgo.net) · [cs50.harvard.edu](https://cs50.harvard.edu) · [csunplugged.org](https://csunplugged.org)
