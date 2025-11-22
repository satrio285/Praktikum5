# Praktikum5

## Penjelasan 

Program ini dibuat menggunakan Python dan memanfaatkan struktur data dictionary untuk menyimpan data mahasiswa. Program dapat menambah, mengubah, menghapus, menampilkan, dan mencari data mahasiswa melalui menu interaktif


Program ini bertujuan mengelola daftar nilai mahasiswa menggunakan dictionary, menyediakan menu interaktif yang dapat memudahkan pengguna dan menghitung nilai akhir berdasarkan bobot untuk tugas = 30%, UTS = 35%, UAS = 35%.

## 1. Struktur Data (Dictionary)

Data mahasiswa disimpan dalam dictionary dengan format berikut:

data = {
    "NIM": {
        "nama": "...",
        "tugas": nilai,
        "uts": nilai,
        "uas": nilai,
        "akhir": nilai
    }
}

Key utama = NIM mahasiswa

Value = dictionary berisi data nilai mahasiswa


Struktur ini dipilih karena:

Mudah diakses menggunakan kunci

Cocok untuk menyimpan data banyak mahasiswa

Mudah diubah dan dihapus



---

## 2. Perhitungan Nilai Akhir

Nilai akhir dihitung menggunakan rumus:

Nilai Akhir = 30% * Tugas + 35% * UTS + 35% * UAS

Dalam program ditulis sebagai:

akhir = round((0.30 * tugas) + (0.35 * uts) + (0.35 * uas), 2)

Fungsi round() digunakan agar nilai akhir hanya tampil 2 angka di belakang koma.

## Flowchart
![Flowchart](https://github.com/user-attachments/assets/eaff13b6-45b1-4da2-9760-c19b66dd0742)


## Tampilan Program
<img width="1920" height="1080" alt="ss1" src="https://github.com/user-attachments/assets/371857c3-b466-4875-8497-ff6c1ed93076" />
<img width="1920" height="1080" alt="ss2" src="https://github.com/user-attachments/assets/6a6885f3-c42e-4ea6-ae44-b55f2ad0e3c8" />




