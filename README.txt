E-PORTFOLIO 1 - MUHAMMAD RAHMAN ASYIDKA

1. Ekstrak ZIP.
2. Buka index.html menggunakan Chrome/Edge/Firefox. Navigasi, modul PDF, dan foto badminton dapat digunakan secara lokal.
3. Untuk video, masuk ke menu 'Video Praktik Mengajar' dan tempel tautan YouTube. Penyimpanan melalui tombol ini HANYA berlaku pada browser/perangkat itu (localStorage), bukan otomatis di website yang dilihat pengunjung lain.
4. Untuk membuat video tampil bagi semua pengunjung di website publik, edit index.html dan ubah kode konstanta stored menjadi ID video default sesuai kebutuhan, misalnya: const stored=localStorage.getItem('eporto_youtube') || 'VIDEO_ID_11_KARAKTER';
5. Untuk menambahkan foto mengajar permanen, masukkan foto ke folder assets lalu sunting elemen HTML id='teachGallery' menggunakan elemen <img src="assets/nama-foto.jpg" alt="...">.
6. Publikasikan seluruh isi folder dengan hosting statis seperti Netlify Drop, GitHub Pages, atau layanan hosting lain. File-file harus tetap berada pada struktur folder yang sama.
7. Google Sites tidak menerima file HTML ini sebagai satu website langsung. Gunakan Google Sites sebagai navigasi/tautan ke website yang di-host, atau pindahkan kontennya secara manual.
8. Data hasil penilaian dan analisis rekaman belum dilengkapi karena belum disediakan. Hindari mengklaim bahwa semua kegiatan yang direncanakan telah terlaksana.
