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


 4. Lalu pada pojok kanan atas, pilih atau tekan tombol :code:`Tambah Pengguna`. Selanjutnya Admin akan diarahkan ke halaman tambah pengguna.


  .. figure:: images/tambah-pengguna.png
     :width: 600
     :alt: gambar 2. Tambah pengguna


 5. Pada halaman tambah pengguna, isikan semua detail pengguna sesuai dengan kolom isian yang ada.
 6. Pada kolom peran pengguna terdapat 4 peran pengguna yang bisa dipilih yaitu Admin, Mahasiswa, Staff Fakultas, dan Staff Jurusan. Pilih peran pengguna sesuai dengan peran yang diinginkan.
 7. Tekan :code:`Simpan`.
 8. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan, dan Admin akan  diarahkan ke halaman daftar pengguna yang sudah dibuat. Sistem juga akan mengirimkan detail nama pengguna dan kata sandi ke alamat email dari pengguna yang baru saja dibuat. Detail nama pengguna dan kata sandi ini diperlukan oleh pengguna untuk proses otentikasi di halaman login ketika akan mengakses layanan SILAMA.


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


 2. Pilih :code:`Edit`. Sistem akan mengarahkan ke halaman edit pengguna sesuai dengan pengguna yang dipilih


  .. figure:: images/edit.png
     :width: 600
     :alt: gambar 4. Edit Pengguna


 3. Pada halaman edit pengguna, isikan detail pengguna pada kolom yang ingin diperbarui.
 4. Tekan :code:`Simpan` untuk menyimpan perubahan.


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

 1. Terdapat dua layanan akademik pada SILAMA, yaitu layanan akdemik tingkat fakultas dan layanan akademik tingkat jurusan. Pengguna dengan peran Admin hanya dapat memonitor jalannya layanan yang diajukan oleh Mahasiswa dan mengekspor datanya sebagai bentuk laporan. Untuk melihat data layanan akademik, pilih layanan akademik sesuai dengan kategori layanan yang ingin dilihat. Sebagai contoh pilih menu :code:`Izin Magang` untuk melihat data layanan akademik dengan kategori Izin Magang.


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


2. Mahasiswa
=================================================

Peran utama Mahasiswa dalam SILAMA adalah untuk mengajukan layanan akademik sesuai dengan kebutuhan.

**1. Memperbarui akun**

 1. Mahasiswa melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Mahasiswa akan diarahkan ke halaman Dashboard.
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


Layanan akademik tingkat fakultas
----------------------------------

**1. Mengajukan layanan tingkat fakultas**

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


**2. Memperbarui/mengedit layanan tingkat fakultas**

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah kita buat. Tekan tanda :code:`...` pada baris Izin Magang yang akan kita edit datanya. Pilih :code:`Edit`, sistem akan mengarahkan ke halaman edit pengajuan Izin Magang.

  
  .. figure:: images/opsi-magang.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Izin Magang, isikan data pada kolom isian yang ingin diperbarui datanya.
 3. Tekan tombol :code:`Ajukan` untuk menyimpan perubahan.

  
  .. figure:: images/edit-magang.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data pengajuan Izin Magang berhasil diperbarui dan dikirmkan ke Staff Fakultas.

  
  .. figure:: images/magang-ok.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
  
  .. figure:: images/magang-error.png
     :width: 600
     :alt: gambar 1. halaman login


**3. Mengunduh surat persetujuan**

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



Layanan akademik tingkat jurusan
---------------------------------

Layanan akademik tingkat jurusan terdiri atas beberapa kategori yaitu, pengajuan Judul Skripsi, Ujian Proposal,  Ujian Pendadaran, dan Surat Keterangan Pendamping Ijazah (SKPI). Berikut cara pengajuan layanan akademik di tingkat jurusan

**1. Mengajukan judul skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Judul Skripsi` untuk membuat pengajuan tentang Judul Skripsi. Pada halaman daftar Judul Skripsi klik tombol :code:`Pengajuan Judul Skripsi` untuk membuat pengajuan baru.

  
  .. figure:: images/judul-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Judul Skripsi, isikan data pada kolom isian yang ada.
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/judul-form.png
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


**2. Mengajukan ujian proposal**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Proposal`. Pada halaman daftar Ujian Proposal klik tombol :code:`Pendaftaran Ujian Proposal`.

  
  .. figure:: images/proposal-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pendaftaran Ujian Proposal, isikan data pada kolom isian yang ada. Cermati pada bagian kolom pilih Judul Skripsi. Jika kita belum mengajukan usulan Judul Skripsi atau usulan Judul Skripsi kita belum disetujui, maka kolom pilih Judul Skripsi datanya akan kosong dan kita tidak dapat melakukan pengajuan Ujian Proposal.
 3. Jika kolom Judul Skripsi ada datanya, pilih Judul Skripsi pada kolom tersebut. Secara otomatis kolom Ringkasan Proposal akan terisi sesuai dengan Ringkasan Proposal pada Judul Skripsi yang dipilih.  
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/proposal-form.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

.. note::
    Ketika pengajuan Ujian proposal telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan dosen penguji untuk kita. Data tentang dosen penguji ini dapat kita lihat pada halaman detail pada pengajuan Ujian Proposal dengan status :code:`Disetujui`.


  
  .. figure:: images/proposal-detail.png
     :width: 600
     :alt: gambar 1. halaman login


**3. Mengajukan ujian skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Pendadaran`. Pada halaman daftar Ujian Skripsi klik tombol :code:`Pendaftaran Ujian Skripsi`.

  
  .. figure:: images/skripsi-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pendaftaran Ujian Skripsi, isikan data pada kolom isian yang ada. Cermati pada bagian kolom pilih Judul Skripsi. Jika kita belum mengajukan usulan Ujian Proposal atau usulan Ujian Proposal kita belum disetujui, maka kolom pilih Judul Skripsi datanya akan kosong dan kita tidak dapat melakukan pengajuan Ujian Skripsi.
 3. Jika kolom Judul Skripsi ada datanya, pilih Judul Skripsi pada kolom tersebut. Secara otomatis kolom Ringkasan Proposal dan Dosen Pembimbing akan terisi secara otomatis, sesuai dengan Ringkasan Proposal dan Dosen Pembimbing pada Judul Skripsi yang dipilih.  
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/skripsi-form.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

.. note::
    Ketika pengajuan Ujian Skripsi telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan dosen penguji untuk kita. Data tentang dosen penguji ini dapat kita lihat pada halaman detail pada pengajuan Ujian Skripsi dengan status :code:`Disetujui`.


**4. Mengajukan SKPI**

 1. Pada panel menu di sebelah kiri, pilih :code:`SKPI`. Pada halaman daftar pengajuan SKPI klik tombol :code:`Pengajuan SKPI`.

  
  .. figure:: images/skpi-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan SKPI, isikan data pada kolom isian yang ada. 
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan SKPI.

  
  .. figure:: images/skpi-form.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.


3. Staff Fakultas
=================================================
  
Staff Fakultas mempunyai peran untuk merespon pengajuan layanan akademik di tingkat Fakultas yang diajukan oleh Mahasiswa. Staff Fakultas juga dapat melakukan rekapitulasi terhadap semua layanan yang diajukan Mahasiswa di tingkat Fakultas sebagai bentuk laporan dan kontrol.


**1. Memperbarui akun**

 1. Staff Fakultas melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Staff Fakultas akan diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`. Sistem akan mengarahkan ke halaman detail akun pengguna.

  
  .. figure:: images/sf-profil.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Isikan data pada kolom isian yang ingin diperbarui.
 5. Tekan tombol :code:`Perbarui`.
 6. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan. 

 
 .. figure:: images/sf-ok.png
    :width: 600
    :alt: gambar 1. halaman login


 7. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/sf-error.png
     :width: 600
     :alt: gambar 1. halaman login


**2.  Menambahkan data Dosen**

 1. Pada panel menu di sebelah kiri, pilih menu :code:`Daftar Dosen`. Sistem akan menampilkan daftar Dosen, tekan tombol :code:`Tambah Dosen` untuk menambahkan data Dosen baru.


  .. figure:: images/dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman formulir untuk menambahkan data Dosen baru. Isi semua kolom isian dan tekan :code:`Simpan` untuk menyimpan data . 


  .. figure:: images/form-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**3.  Memperbarui data Dosen**

 1. Pada daftar Dosen klik tanda :code:`...` pada kolom Opsi pada baris Dosen yang ingin diperbarui. Pilih :code:`Edit`.


  .. figure:: images/opsi-dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman formulir untuk memperbarui data Dosen. Isi data dengan data yang baru pada  kolom isian yang ingin diperbarui datanya. Tekan :code:`Simpan` untuk menyimpan data . 


  .. figure:: images/edit-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**4.  Menghapus data Dosen**

 1. Pada daftar Dosen klik tanda :code:`...` pada kolom Opsi pada baris Dosen yang ingin dihapus. Pilih :code:`Hapus`.


  .. figure:: images/opsi-dosen.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Sistem akan menampilkan halaman konfirmasi penghapusan. Tekan tombol :code:`Ok` untuk menghapus data . 


  .. figure:: images/delete-dosen.png
     :width: 600
     :alt: gambar 4. Hapus Pengguna


**5.  Mereview pengajuan layanan akademik**

 1. Pada panel menu di sebelah kiri, pilih layanan fakultas yang diinginkan. Sebagai contoh kita pilih :code:`Izin Magang`. Sistem akan menampilkan daftar Izin Magang yang sudah dibuat oleh Mahasiswa. 


  .. figure:: images/sf-list.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Pilih :code:`Detail` pada baris Izin Magang yang ingin direview. Sistem akan otomatis mengarahkan ke halaman detail pengajuan Izin Magang.


  .. figure:: images/sf-detail.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 3. Tekan :code:`Tolak` untuk menolak pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses penolakan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Tolak` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses penolakan.


  .. figure:: images/sf-tolak.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


3. Tekan :code:`Setujui` untuk menyetujui pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses persetujuan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Setujui` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses persetujuan.


  .. figure:: images/sf-setuju.png
     :width: 600
     :alt: gambar 4. Detail Pengguna

.. note::
    Ketika menolak suatu pengajuan, pastikan untuk memberikan note alasan penolakan, agar mempermudah Mahasiswa dalam merevisi pengajuan. Ketika menyetujui pengajuan, pastikan untuk melampirkan surat izin persetujuan.


4. Staff Jurusan
=================================================
  
Staff Jurusan mempunyai peran untuk merespon pengajuan layanan akademik di tingkat Jurusan yang diajukan oleh Mahasiswa. Staff Jurusan juga dapat melakukan rekapitulasi terhadap semua layanan yang diajukan Mahasiswa di tingkat Jurusan sebagai bentuk laporan dan kontrol.


**1. Memperbarui akun**

 1. Staff Jurusan melakukan proses otentikasi melalui halaman Login.

  
  .. figure:: images/login.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi sesuai, Staff Fakultas akan diarahkan ke halaman Dashboard.
 3. Pilih menu :code:`Kelola Akun Saya`. Sistem akan mengarahkan ke halaman detail akun pengguna.

  
  .. figure:: images/sj-profil.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Isikan data pada kolom isian yang ingin diperbarui.
 5. Tekan tombol :code:`Perbarui`.
 6. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa data berhasil disimpan. 

 
 .. figure:: images/sj-ok.png
    :width: 600
    :alt: gambar 1. halaman login


 7. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/sj-error.png
     :width: 600
     :alt: gambar 1. halaman login


Mereview pengajuan layanan akademik
--------------------------------------

**1. Pengajuan judul skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Judul Skripsi`.Sistem akan menampilkan daftar pengajuan Judul Skripsi yang sudah dibuat oleh Mahasiswa. 


  .. figure:: images/sf-prop.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Untuk mengecek apakah ada duplikasi atau kesamaan judul dan rangkuman proposal, Staff Jurusan dapat memanfaatkan fitur pencarian berdasarakan kata kunci dari judul atau rangkuman proposal. Sebagai contoh kita akan mengecek apakah pengajuan dengan judul, Pengaruh Pendapatan Bunga dan Fees Base Income terhadap Laba Operasional pada Bank Rakyat Indonesia (Persero) Tbk Cabang Yogyakarta terdapat dupliasi atau tidak, maka kita cukup memasukkan kata kunci dengan judul tersebut ke kolom pencarian.
 3. Selanjutnya tekan :code:`Detail` pada baris pengajuan Judul Skripsi yang akan direview. Sistem akan menampilkan detail pengajuan Judul Skripsi. Tekan :code:`Setujui` untuk menyetujui pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses persetujuan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Setujui` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses persetujuan.


  .. figure:: images/sf-approve.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


4. Tekan :code:`Tolak` untuk menolak pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses penolakan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Tolak` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses penolakan.


  .. figure:: images/sf-reject.png
     :width: 600
     :alt: gambar 4. Detail Pengguna

.. note::
    Ketika menolak suatu pengajuan, pastikan untuk memberikan note alasan penolakan, agar mempermudah Mahasiswa dalam merevisi pengajuan. Ketika menyetujui pengajuan, pastikan untuk melampirkan surat izin persetujuan.


**2. Pengajuan ujian proposal**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Proposal`.Sistem akan menampilkan daftar pengajuan Ujian Proposal yang sudah dibuat oleh Mahasiswa. 


  .. figure:: images/prop-list.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Selanjutnya tekan :code:`Detail` pada baris pengajuan Ujian Proposal yang akan direview. Sistem akan menampilkan detail pengajuan Ujian Proposal.


  .. figure:: images/prop-detail.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


3. Tekan :code:`Setujui` untuk menyetujui pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses persetujuan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Setujui` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses persetujuan.


  .. figure:: images/prop-ok.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


4. Tekan :code:`Tolak` untuk menolak pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses penolakan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Tolak` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses penolakan.


  .. figure:: images/prop-no.png
     :width: 600
     :alt: gambar 4. Detail Pengguna

.. note::
    Ketika menyetujui pengajuan, pastikan untuk melampirkan surat izin persetujuan, memilih tanggal ujian proposal dan menentukan dosen penguji untuk ujian proposal yang bersangkutan.


**3. Pengajuan ujian skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Pendadaran`.Sistem akan menampilkan daftar pengajuan Ujian Skripsi yang sudah dibuat oleh Mahasiswa. 


  .. figure:: images/skripsi-lists.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Selanjutnya tekan :code:`Detail` pada baris pengajuan Ujian Skrupsi yang akan direview. Sistem akan menampilkan detail pengajuan Ujian Skripsi.


  .. figure:: images/skripsi-detail.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


3. Tekan :code:`Setujui` untuk menyetujui pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses persetujuan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Setujui` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses persetujuan.


  .. figure:: images/skripsi-ok.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


4. Tekan :code:`Tolak` untuk menolak pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses penolakan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Tolak` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses penolakan.


  .. figure:: images/skripsi-no.png
     :width: 600
     :alt: gambar 4. Detail Pengguna

.. note::
    Ketika menyetujui pengajuan, pastikan untuk melampirkan surat izin persetujuan, memilih tanggal ujian skripsi dan menentukan dosen penguji untuk ujian skripsi yang bersangkutan.


**4. Pengajuan SKPI**

 1. Pada panel menu di sebelah kiri, pilih :code:`SKPI`.Sistem akan menampilkan daftar pengajuan SKPI yang sudah dibuat oleh Mahasiswa. 


  .. figure:: images/skpi-list.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


 2. Selanjutnya tekan :code:`Detail` pada baris pengajuan SKPI yang akan direview. Sistem akan menampilkan detail pengajuan SKPI.


  .. figure:: images/skpi-detail.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


3. Tekan :code:`Setujui` untuk menyetujui pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses persetujuan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Setujui` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses persetujuan.


  .. figure:: images/skpi-ok.png
     :width: 600
     :alt: gambar 4. Detail Pengguna


4. Tekan :code:`Tolak` untuk menolak pengajuan. Sistem akan menampilkan jendela konfirmasi apakah proses penolakan pengajuan akan diteruskan atau tidak. Tekan :code:`Ya, Tolak` untuk melanjutkan dan tekan :code:`Batal` untuk membatalkan proses penolakan.


  .. figure:: images/skpi-no.png
     :width: 600
     :alt: gambar 4. Detail Pengguna
