# Pratikum9
### Richie Pranata
### 312410451
### TI.24.A.5

## 📌 Penjelasan Singkat Praktikum 9 (PHP Modularisasi & Routing)

### Pada praktikum 9 ini saya belajar bagaimana membuat sebuah project PHP yang lebih rapi, terstruktur, dan mudah dikelola dengan cara memisahkan bagian-bagian halaman menjadi modul. Jika pada praktikum sebelumnya (praktikum 8) semua kode masih tercampur dalam satu file, maka di praktikum ini saya memecahnya menjadi komponen-komponen terpisah seperti:

header.php untuk bagian atas halaman (judul, navbar, tag HTML pembuka)

footer.php untuk bagian bawah halaman

koneksi.php untuk koneksi database

File-file CRUD diletakkan dalam folder terpisah (misalnya /user/)

Dengan pendekatan seperti ini, ketika saya ingin mengubah tampilan header atau menu, saya hanya perlu mengubah satu file, dan perubahan tersebut akan langsung diterapkan ke seluruh halaman. Jadi lebih efisien dan profesional, seperti cara kerja framework modern.

Selain modularisasi, saya juga menerapkan routing, yaitu cara mengatur halaman yang ditampilkan menggunakan parameter page pada URL.
Contohnya:


> index.php?page=user/list


# Cara ini membuat project lebih mudah dikembangkan dan terlihat lebih rapi dibanding memanggil file secara langsung (seperti list.php, tambah.php, dll).

Secara keseluruhan, praktikum ini mengajarkan bagaimana membuat aplikasi PHP yang:

### lebih terstruktur

### lebih mudah dipelihara

### lebih mudah dikembangkan

### dan lebih mendekati standar project web modern.
