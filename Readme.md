# Praktikum 3: CSS Dasar - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 3 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                 |
| --------------- | ---------------      |
| **Nama**        | Davarel Radivan Anwar|
| **Kelas**       | I251D                |
| **NIM**         | 312510384		|
| **Mata Kuliah** | Pemrograman Web      |

### Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

## Struktur Folder Proyek

```
Lab3Web/
├── Lab3_css_dasar.html
├── style_eksternal.css
└── README.md

```
## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

<img width="373" height="156" alt="image" src="https://github.com/user-attachments/assets/3f308731-6068-48ed-9784-69a6f8b63da9" />

## Langkah-langkah Praktikum

### 1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.

 <img width="975" height="520" alt="image" src="https://github.com/user-attachments/assets/92251b58-f66a-4f06-82ec-7c8cb9cac84c" />

Selanjutnya buka pada brwoser untuk melihat hasilnya.

 <img width="725" height="386" alt="image" src="https://github.com/user-attachments/assets/0b762c65-9ae3-4e24-86cb-0b7e0407d853" />

### 2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.

 <img width="480" height="434" alt="image" src="https://github.com/user-attachments/assets/c4609313-0844-4c9f-861e-37bd8c2cb736" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

 <img width="975" height="520" alt="image" src="https://github.com/user-attachments/assets/62c71cff-ed43-4c8f-aa93-ec480b05db31" />

### 3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

 <img width="986" height="174" alt="image" src="https://github.com/user-attachments/assets/5b0082ee-ef16-46a0-afa6-9f8a376783cf" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

 <img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/300fcd7c-4b6f-41d9-96e2-c66c2ad76add" />


### 4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.

 <img width="315" height="372" alt="image" src="https://github.com/user-attachments/assets/0b6a3db5-a4fa-4553-ab18-a8316af15b0a" />

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian
<head>

 <img width="563" height="168" alt="image" src="https://github.com/user-attachments/assets/b7c071ca-b2b9-4132-8812-32ad2065b84a" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="989" height="527" alt="image" src="https://github.com/user-attachments/assets/9299d5fc-9dbe-4c8d-921f-b25ca56eb5ce" />

### 5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.

<img width="383" height="594" alt="image" src="https://github.com/user-attachments/assets/1618ec46-1225-46f9-b0c0-ff08f4612474" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="885" height="498" alt="image" src="https://github.com/user-attachments/assets/4e3bb994-3aa0-42b7-812d-80f84d4d023b" />


### 6. Validasi Dokumen CSS (W3C Validator)

Melakukan pengujian kode pada style_eksternal.css menggunakan layanan W3C CSS Validator. Hasil pengecekan menunjukkan pesan "Tidak ditemukan kesalahan", yang berarti kode yang ditulis sudah valid dan sesuai dengan standar web internasional.

<img width="1194" height="636" alt="image" src="https://github.com/user-attachments/assets/b523e20f-4472-42ad-b19d-2f2c4f82654a" />
