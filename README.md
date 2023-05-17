# Simple-HPC


![central-computer-processor-with-neon-lights-integrated-microchip-circuit-board-server](https://github.com/NmaxDiesel/Simple-HPC/assets/123163060/23ea2741-98d9-4e62-abca-f908dd66d87c)

## Background

Dalam bidang Data Science, banyak sekali data yang perlu diproses dan dianalisis dengan cepat dan efisien. HPC memungkinkan pengguna untuk memproses data dengan cepat dan efisien dengan memanfaatkan teknologi paralel dan distribusi komputasi.

Untuk memanfaatkan kemampuan HPC (High-Performance Computing) dalam melakukan tugas-tugas seperti pengolahan big data, machine learning, analisis data real-time, simulasi, prediksi, dan visualisasi data, diperlukan pemrograman paralel. Pemrograman paralel adalah teknik pemrograman yang memungkinkan program untuk dijalankan secara simultan pada beberapa prosesor atau inti prosesor yang terdapat pada sebuah sistem HPC. Pemrograman paralel memungkinkan program untuk memanfaatkan kemampuan teknologi HPC secara maksimal dengan membagi tugas menjadi beberapa bagian kecil yang dapat dijalankan secara simultan pada beberapa prosesor.

Berikut ialah hal yang akan saya lakukan:

- Membangun algoritma decision tree
- Melakukan proses perancangan secara sequential dan parallel
- Melakukan split, menghitung entropi dan mencari informasional gain

## Tahapan Pengerjaan

Berikut adalah tahap-tahap yang harus dilakukan dalam membangun decision tree:

1. Persiapan Data
- Load dataset yang akan digunakan.
- Pisahkan antara atribut (fitur) dan label (target output) dari dataset.
- Bagi dataset menjadi data latih dan data uji.

2. Membangun Decision Tree Secara Sequential
- Pilih metode splitting (pemisahan) yang akan digunakan (misalnya, splitting berdasarkan informasi gain atau gini index).
- Hitung entropi atau impuritas pada setiap node (simpul).
- Hitung informasi gain atau reduksi impuritas dari setiap atribut dan pilih atribut dengan informasi gain tertinggi sebagai node berikutnya.
- Ulangi proses di atas pada setiap node hingga memperoleh decision tree yang lengkap.

3. Membangun Decision Tree Secara Paralel
- Tentukan jumlah thread atau proses yang akan digunakan.

4. Evaluasi Decision Tree


Tahap-tahap di atas merupakan proses umum yang dilakukan dalam membangun decision tree. Namun, ada beberapa variasi metode dan teknik yang dapat digunakan dalam masing-masing tahap tergantung pada jenis dan kompleksitas dari dataset yang digunakan.
