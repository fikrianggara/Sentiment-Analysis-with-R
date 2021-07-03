# Sentiment-Analysis-with-R
program yang berisikan fungsi dan langkah langkah untuk melakukan analisis sentimen sederhana menggunakan data twitter.
data yang digunakan merupakan data yang diperoleh dari sertifikasi R dasar Hackerrank, memiliki tiga atribut yaitu id twitter, pesan twitter, sentimen.
kode ini berisi:
 - fungsi untuk cleaning data bertipe character. cleaning mencakup:
    - menghilangkan tanda baca seperti ","; "."; "!"; "("; ")"; "'"; "?"; dll.
    - mengubah pesan menjadi huruf kecil.
    - menghilangkan leading dan trailing space pada pesan.
 - fungsi untuk mentransformasi data twitter menjadi kata-kata yang memiliki sentimen. setiap twitter dipecah menjadi kata, kata tersebut diklasifikasikan berdasarkan label pesan twitter.
