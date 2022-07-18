# Image-Classification---TF
Dalam project ini, saya mencoba mengklasifikasikan gambar dengan menggunakan pembelajaran transfer dari jaringan yang telah dilatih sebelumnya.  Intuisi di balik pembelajaran transfer untuk klasifikasi gambar adalah bahwa jika model dilatih pada kumpulan data yang cukup besar dan umum, model ini akan secara efektif berfungsi sebagai model umum dunia visual. Kemudian dapat memanfaatkan peta fitur yang dipelajari ini tanpa harus memulai dari awal dengan melatih model besar pada kumpulan data yang besar.  Kemudian akan mencoba dua cara untuk menyesuaikan model yang sudah dilatih sebelumnya :  Ekstraksi fitur, representasi yang dipelajari oleh jaringan sebelumnya untuk mengekstrak fitur yang berarti dari sampel baru Fine-Tuning, Mencairkan beberapa lapisan atas dari basis model yang dibekukan dan bersama-sama melatih lapisan pengklasifikasi yang baru ditambahkan dan lapisan terakhir dari model dasar