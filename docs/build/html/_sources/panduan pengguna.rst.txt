.. Sistem Informasi Layanan Akademik Mahasiswa documentation master file, created by
   sphinx-quickstart on Wed Jan  8 08:28:11 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

*****************
Panduan Pengguna
*****************

Berikut panduan penggunanaan SILAMA berdasarkan peran masing-masing

1. Admin
=========
  
Secara default, SILAMA mempunyai satu akun pengguna yang perannya sebagai Admin. Selanjutnya Admin dapat membuat akun untuk pengguna-pengguna lainnya sesuai dengan peran yang diinginkan.


.. note::
    Khusus untuk pengguna dengan peran sebagai Mahasiswa, Mahasiswa dapat mendaftarkan dirinya sendiri secara mandiri melalui halaman pendaftaran di SILAMA. 


**1. Pembuatan akun pengguna**

Berikut langkah-langkah pembuatan akun pengguna untuk SILAMA. 

 1. Admin melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Admin akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Pengguna`.


  .. figure:: images/kelola-pengguna.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Lalu pada pojok kanan atas, pilih atau tekan tombol :code:`Tambah Pengguna`. Selanjutnya secara otomatis Admin akan diarahkan ke halaman tambah pengguna.


  .. figure:: images/tambah-pengguna.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 5. Pada halaman tambah pengguna, isikan semua detail pengguna sesuai dengan kolom isian yang ada.
 6. Pada kolom peran pengguna terdapat 4 peran pengguna yang bisa dipilih yaitu Admin, Mahasiswa, Staff Fakultas, dan Staff Jurusan. Pilih peran pengguna sesuai dengan peran yang diinginkan.
 7. Tekan :code:`Simpan`.
 8. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan, dan Admin akan secara otomatis diarahkan ke halaman daftar pengguna yang sudah dibuat. Sistem juga secara otomatis akan mengirimkan detail nama pengguna dan kata sandi ke alamat email dari pengguna yang baru saja dibuat. Detail nama pengguna dan kata sandi ini diperlukan oleh pengguna untuk proses otentikasi di halaman login ketika akan mengakses layanan SILAMA.


  .. figure:: images/pesan-ok.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 9. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

   
  .. figure:: images/pesan-error.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


**2.  Melihat detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin dilihat detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Detail`. Sistem akan otomatis mengarahkan ke halaman detail pengguna sesuai dengan pengguna yang dipilih


  .. figure:: images/detail-pengguna2.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


**2.  Memperbarui detail akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diperbarui detailnya.


  .. figure:: images/detail-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Edit`. Sistem akan otomatis mengarahkan ke halaman edit pengguna sesuai dengan pengguna yang dipilih


  .. figure:: images/edit.png
     :width: 600
     :alt: gambar 4. Edit Pengguna


**3.  Menonaktifkan akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin dinonaktifkan.


  .. figure:: images/opsi-pengguna.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Nonaktifkan`. Sistem akan menampilkan jendela konfirmasi, apakah proses penonaktifan akun akan diteruskan atau tidak. Pilih OK untuk mengkonfirmasi penonaktifan akun. 


  .. figure:: images/nonaktifkan.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


  .. note::
    Pengguna yang akunnya telah dinonaktifkan tidak dapat lagi mengakses layanan sistem informasi yang ada. Untuk dapat menggunakan lagi layanan sistem informasi yang ada, akun pengguna yang telah dinonaktifkan harus diaktifkan lagi oleh Admin.


**4.  Mengaktifkan kembali akun pengguna**

 1. Pada halaman daftar pengguna, klik tanda :code:`...` pada kolom opsi pada akun pengguna yang ingin diaktifkan kembali akunnya.


  .. figure:: images/aktifkan.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Aktifkan`. Sistem akan menampilkan jendela konfirmasi, apakah proses pengaktifan akun akan diteruskan atau tidak. Pilih OK untuk mengkonfirmasi pengaktifan akun. 


  .. figure:: images/aktifkan-lagi.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**5.  Menambahkan data Dosen**

 1. Pada panel menu di sebelah kiri, pilih menu :code:`Daftar Dosen`. Sistem akan menampilkan daftar Dosen, tekan tombol :code:`Tambah Dosen` untuk menambahkan data Dosen baru.


  .. figure:: images/dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman formulir untuk menambahkan data Dosen baru. Isi semua kolom isian dan tekan :code:`Simpan` untuk menyimpan data . 


  .. figure:: images/form-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**6.  Memperbarui data Dosen**

 1. Pada daftar Dosen klik tanda :code:`...` pada kolom Opsi pada baris Dosen yang ingin diperbarui. Pilih :code:`Edit`.


  .. figure:: images/opsi-dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman formulir untuk memperbarui data Dosen. Isi data dengan data yang baru pada  kolom isian yang ingin diperbarui datanya. Tekan :code:`Simpan` untuk menyimpan data . 


  .. figure:: images/edit-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**7.  Menghapus data Dosen**

 1. Pada daftar Dosen klik tanda :code:`...` pada kolom Opsi pada baris Dosen yang ingin dihapus. Pilih :code:`Hapus`.


  .. figure:: images/opsi-dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman konfirmasi penghapusan. Tekan tombol :code:`Ok` untuk menghapus data . 


  .. figure:: images/delete-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**8.  Melihat data layanan akademik**

 1. Terdapat dua layanan akademik pada SILAMA, yaitu layanan akdemik tingkat fakultas dan layanan akademik tingkat jurusan. Pengguna dengan peran Admin hanya dapat memonitor jalannya layanan yang diajukan oleh Mahasiswa dan mengekspor datanya sebagai bentuk laporan. Untuk melihat data layanan akademik, pilih layanan akademik sesuai dengan kategori layanan yang ingin dilihat. Sebagai contoh pilih/klik menu :code:`Izin Magang` untuk melihat data layanan akademik dengan kategori Izin Magang.


  .. figure:: images/magang-list.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan daftar pengajuan Izin Magang yang sudah dibuat oleh Mahasiswa. Tekan tombol :code:`Ekspor ke Excel` untuk mengunduh data daftar izin magang dalam format Excel.




**9.  Melihat detail data layanan akademik**

 1. Pada layanan akademik yang dipilih,  klik tombol :code:`Detail` pada kolom daftar layanan yang ingin dilihat detailnya.


  .. figure:: images/magang-list.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan detail data dari layanan akademik yang dipilih.

  .. figure:: images/magang-detail.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


Mahasiswa
=================================================
  
Literal Blocks
--------------

Literal blocks are indicated with a double-colon ("::") at the end of
the preceding paragraph (over there ``-->``).  They can be indented::

    if literal_block:
        text = 'is left as-is'
        spaces_and_linebreaks = 'are preserved'
        markup_processing = None

Or they can be quoted without indentation::

>> Great idea!
>
> Why didn't I think of that?

Line Blocks
-----------

This is a line block.  It ends with a blank line.

Peran utama Mahasiswa dalam SILAMA adalah untuk mengajukan layanan akademik sesuai dengan kebutuhan.

**1. Memperbarui akun**

 1. Mahasiswa melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Mahasiswa akan secara otomatis diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`. Sistem akan mengarahkan ke halaman detail akun pengguna.

  
  .. figure:: images/akun.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Isikan data pada kolom isian yang ingin diperbarui.
 5. Tekan tombol :code:`Perbarui`.
 6. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan. 

 
 .. figure:: images/akun-ok.png
    :width: 600
    :alt: gambar 1. halaman login


 7. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/akun-error.png
     :width: 600
     :alt: gambar 1. halaman login

**2. Mengajukan layanan tingkat fakultas**

Layanan akademik tingkat fakultas terdiri atas beberapa kategori yaitu, pengajuan Izin Magang, Izin Penelitian, Surat Keterangan Lulus (SKL), Permohonan Cuti dan Pemulihan Status. Berikut cara pengajuan layanan akademik di tingkat fakultas

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah kita buat. Tekan tombol :code:`Pengajuan Magang` untuk mengajukan Izin Magang baru.

  
  .. figure:: images/magang.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Izin Magang, isikan data pada kolom isian yang ada.
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Izin Magang.

  
  .. figure:: images/magang-form.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Fakultas untuk direview.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
 6. Pengajuan layanan Izin Magang yang berhasil disubmit akan berstatus  :code:`Menunggu` sampai proses review oleh pihak Fakultas selesai. Status pengajuan layanan Izin Magang dapat dilihat dalam Daftar Izin Magang pada kolom status. Terdapat 3 status sesuai kondisi masing-masing yaitu menunggu, disetujui dan ditolak. 

  :code:`Menunggu` berarti pengajuan usulan Izin Magang masih dalam proses review dan menunggu hasil review dari pihak Fakultas.

  :code:`Disetujui` berarti pengajuan usulan Izin Magang telah disetujui oleh pihak Fakultas. Nantinya Mahasiswa akan mendapatkan surat persetujuan yang dapat di unduh dan dicetak secara mandiri.

  :code:`Ditolak` berarti pengajuan usulan Izin Magang tidak disetujui. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan usulan Izin Magang. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi pengajuan usulan Izin Magang untuk kembali diajukan ke pihak Fakultas.


**3. Memperbarui/mengedit layanan tingkat fakultas**

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah kita buat. Tekan tanda :code:`...` pada baris Izin Magang yang akan kita edit/perbarui datanya.

  
  .. figure:: images/opsi-magang.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Izin Magang, isikan data pada kolom isian yang ingin diperbarui datanya.
 3. Tekan tombol :code:`Ajukan` untuk menyimpan perubahan.

  
  .. figure:: images/edit-magang.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data pengajuan Izin Magang berhasil diperbarui.

  
  .. figure:: images/magang-ok.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
  
  .. figure:: images/magang-error.png
     :width: 600
     :alt: gambar 1. halaman login


**4. Mengunduh surat persetujuan**

Layanan akademik tingkat fakultas yang telah direview dan disetujui oleh pihak Fakultas akan mendapatkan surat persetujuan. Selanjutnya Mahasiswa dapat mengunduh surat persetujuan tersebut untuk dicetak secara mandiri untuk dipergunakan sesuai kebutuhan. Ikuti langkah berikut untuk mengunduh surat persetujuan.

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah kita buat. Tekan tombol :code:`Detail` pada baris Izin Magang yang berstatus disetujui.

  
  .. figure:: images/magang.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman detail pengajuan Izin Magang, tekan tombol :code:`Unduh Lampiran` untuk mengunduh surat persetujuan.

  
  .. figure:: images/detail-magang.png
     :width: 600
     :alt: gambar 1. halaman login

**4. Merevisi pengajuan layanan yang ditolak**

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah kita buat. Tekan tanda :code:`...` pada baris Izin Magang yang berstatus ditolak, lalu pilih :code:`Detail`.

  
  .. figure:: images/resubmit.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman detail pengajuan Izin Magang, cermati pada bagian alasan penolakan. Tekan tombol :code:`Edit` untuk merevisi pengajuan layanan.

  
  .. figure:: images/alasan.png
     :width: 600
     :alt: gambar 1. halaman login


 3. Isi field yang perlu diperbaiki sesuai pada alasan penolakan. Jika data isian telah sesuai, tekan tombol :code:`Ajukan` untuk mensubmit ulang pengajuan layanan Izin Magang. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Fakultas untuk direview.


  .. figure:: images/edit-revisi.png
     :width: 600
     :alt: gambar 1. halaman login


**5. Mengajukan layanan tingkat jurusan**

Layanan akademik tingkat jurusan terdiri atas beberapa kategori yaitu, pengajuan Judul Skripsi, Ujian Proposal,  Ujian Pendadaran, dan Surat Keterangan Pendamping Ijazah (SKPI). Berikut cara pengajuan layanan akademik di tingkat jurusan

 1. Pada panel menu di sebelah kiri, pilih layanan jurusan yang diinginkan. Sebagai contoh kita pilih :code:`Judul Skripsi` untuk membuat pengajuan tentang Judul Skripsi. Pada halaman daftar Judul Skripsi klik tombol :code:`Pengajuan Judul Skripsi` untuk membuat pengajuan baru.

  
  .. figure:: images/magang.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Judul Skripsi, isikan data pada kolom isian yang ada.
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/magang-form.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
 6. Pengajuan Judul Skripsi yang berhasil disubmit akan berstatus  :code:`Menunggu` sampai proses review oleh pihak Jurusan selesai. Status pengajuan Judul Skripsi dapat dilihat dalam Daftar Judul Skripsi pada kolom status. Terdapat 3 status sesuai kondisi masing-masing yaitu menunggu, disetujui dan ditolak. 

  :code:`Menunggu` berarti pengajuan Judul Skripsi masih dalam proses review dan menunggu hasil review dari pihak Jurusan.

  :code:`Disetujui` berarti pengajuan Judul Skripsi telah disetujui oleh pihak Jurusan. Nantinya Mahasiswa akan mendapatkan surat persetujuan yang dapat di unduh dan dicetak secara mandiri.

  :code:`Ditolak` berarti pengajuan Judul Skripsi tidak disetujui. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan Judul Skripsi. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi pengajuan Judul Skripsi untuk kembali diajukan ke pihak Jurusan.


.. note::
    Layanan akdemik tingkat Jurusan bersifat sequential (berurutan), dimana antara layanan satu dengan yang lainnya memiliki kesinambungan. Untuk dapat mengajukan Ujian Proposal kita harus terlebih dahulu mendapat persetujuan dari pengajuan Judul Skripsi yang kita buat. Demikian halnya dengan pengajuan Ujian Pendadaran, fitur pengajuan Ujian Pendadaran akan bisa diakses ketika pengajuan Ujian Proposal telah disetujui.  
