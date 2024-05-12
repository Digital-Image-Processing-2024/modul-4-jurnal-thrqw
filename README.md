[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1M95yCDL)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15042121&assignment_repo_type=AssignmentRepo)
# Jurnal Modul Deteksi Tepi dan Perbaikan Kualitas Citra

> Additional notes

- Jangan merubah struktur folder yang ada
- Gambar terkait sudah tersimpan di folder ./assets
- Pastikan hasil sesuai dengan **Expected Result** pada ./modul_jurnal.pdf
- Tidak ada Penambahan waktu deadline
- Jangan merubah format default pada file ./main.ipynb
- Overtime tidak menjamin apa yang dirimu kerjakan sesuai dengan ekspetasi. Jadi kerjakan sewajarnya dan jangan dipaksakan...

### Soal

Perbaikilah kualitas citra dari gambar yang tersedia dengan menggunakan:

- Kernel 3x3 berisi 1/9 dengan metode Mean, Median dan Modus
- Kernel 9x9 dengan berisi 1/81 dengan metode yang sama seperti poin sebelumnya
- kernel 3x3 untuk melakukan sharpening dan smoothing dengan kernel yang berisi sebagai berikut

> Contoh

![Contoh kernel 1 pada soal](./assets/expict1_1.png "gambar_expict1_1")
![Contoh kernel 2 pada soal](./assets/expict1_2.png "gambar_expict1_2")

Lalu deteksi tepi untuk semua jenis perbaikan tadi dengan operator Sobel, Prewitt dan Robert pada gambar ./assets/manchester_united.jpeg

![Contoh gambar pada soal](./assets/manchester_united.jpeg "gambar_manchester_united")

> Expected Result

![Contoh hasil gambar 1 pada soal](./assets/exres1_1.png "gambar_exres1_1")
![Contoh hasil gambar 2 pada soal](./assets/exres1_2.png "gambar_exres1_2")
![Contoh hasil gambar 3 pada soal](./assets/exres1_3.png "gambar_exres1_3")
![Contoh hasil gambar 4 pada soal](./assets/exres1_4.png "gambar_exres1_4")
