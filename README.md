# ReserveApp

ReserveApp
Reservasi adalah proses pemesanan yang dilakukan sebelum calon pelanggan tiba di 
suatu layanan jasa. Salah satu layanan yang sering menyediakan layanan reservasi adalah 
restoran. Tujuan dari sebuah restoran menyediakan layanan reservasi adalah agar calon 
pelanggan dapat memastikan ketersediaan restoran maupun makanan yang diinginkan. 

Seringkali setelah menempuh perjalanan yang jauh ke restoran yang diinginkan, calon 
pelanggan masih harus menunggu dan mengantri untuk mendapatkan meja di restoran.
Menyikapi permasalahan tersebut, sudah banyak restoran yang menyediakan layanan 
reservasi bagi calon pelanggan mereka yang dapat dilakukan melalui telepon atau dengan 
mendatangi restoran secara langsung (walk- in). Namun, hal ini sering dinilai tidak praktis 
dan tidak efisien bagi pelanggan. Oleh karena itu, untuk mengatasi permasalahan ini, 
dibuatlah sebuah aplikasi berbasis mobile dengan nama ReserveApp yang dapat digunakan 
oleh pengguna untuk melakukan reservasi secara berbayar di berbagai restoran yang mereka 
inginkan secara mudah dan praktis. Tak hanya itu, pengguna juga dapat memberikan review 
dari restoran yang telah dikunjungi dan review tersebut dapat dilihat oleh seluruh pengguna 
ReserveApp. Berikut adalah proses bisnis dari aplikasi ReserveApp.
Pengguna yang ingin mengakses fitur-fitur pada aplikasi ReserveApp harus 
mengunduh aplikasi melalui AppStore atau PlayStore terlebih dahulu. Setelah aplikasi 
terunduh, pengguna yang sudah memiliki akun dapat menekan tombol sign in dan melakukan 
sign in menggunakan akun yang sudah terdaftar. Namun apabila pengguna belum memiliki 
akun, maka pengguna harus melakukan sign up terlebih dahulu. Pada halaman sign up, 
pengguna akan diminta untuk mengisi data diri berupa nama lengkap, username, email, 
tanggal lahir, nomor handphone, dan password. Jika sudah yakin dengan data diri yang telah 
diisi, maka pengguna dapat menekan tombol sign up dan aplikasi akan menyimpan data diri 
pengguna ke dalam sistem.
Selanjutnya, sistem akan mengarahkan pengguna ke halaman sign in. Pada halaman 
sign in, pengguna yang sudah memiliki akun dapat memasukkan username dan password 
yang telah didaftarkan dan menekan tombol sign in. Kemudian sistem akan memverifikasi 
data yang dimasukkan oleh pengguna, dan pengguna yang berhasil terverifikasi akan 
langsung diarahkan ke halaman home. Sedangkan pengguna yang tidak berhasil terverifikasi 
oleh sistem akan diminta untuk meng-input data sign in kembali.
Pada halaman home, terdapat berbagai rekomendasi list restoran yang telah berafiliasi 
dengan aplikasi ReserveApp dan dibagi berdasarkan jenis restoran, yaitu American, Korean, 
European, dan lainnya. Setiap restoran dapat digolongkan dalam lebih dari 1 jenis restoran. 

Selain itu, pengguna juga dapat melakukan pencarian restoran pada search box yang terdapat 
di bagian atas halaman home. Kemudian pengguna dapat memilih restoran yang diinginkan 
dan aplikasi akan menampilkan informasi detail dari restoran tersebut, yang terdiri dari nama, 
foto, alamat, jam buka dan tutup, deskripsi restoran, serta review dari pengguna lain. 
Pengguna juga dapat melihat menu yang disediakan oleh masing-masing restoran ketika 
melihat informasi detail dari restoran tersebut. Informasi menu yang tersedia yaitu foto, 
nama, dan harga. Meskipun pengguna dapat melihat menu yang disediakan oleh restoran, 
namun pengguna tidak dapat melakukan pemesanan menu pada aplikasi ReserveApp. 
Pengguna dapat melakukan reservasi restoran dengan cara menekan tombol reserve pada 
bagian bawah halaman detail restoran dan aplikasi akan menampilkan form reservasi
restoran. 
Pada halaman form reservasi restoran, pengguna diwajibkan untuk mengisi data 
berupa tanggal reservasi, jam reservasi, dan jumlah pengunjung. Selanjutnya, pengguna juga 
diminta untuk memilih posisi meja yang diinginkan. Pengguna dapat melakukan reservasi 
pada lebih dari satu meja dalam satu form reservasi restoran. Untuk melanjutkan proses 
reservasi restoran, pengguna akan diminta untuk melakukan pembayaran biaya deposit atas 
reservasi restoran yang dilakukan. Pembayaran biaya deposit akan dilakukan sebesar lima 
puluh ribu Rupiah per pengunjung, dimana nantinya biaya deposit ini akan menjadi nilai 
pengurang dari total harga makanan yang perlu dibayarkan oleh pengunjung restoran.
Setelah seluruh data form reservasi restoran terisi, maka pengguna dapat memilih 
tombol submit dan aplikasi akan menampilkan nomor virtual account dan jumlah deposit
yang harus dibayarkan. Jika dalam waktu 60 menit pengguna tidak melakukan pembayaran, 
maka reservasi akan dibatalkan secara otomatis. Apabila pengguna telah berhasil melakukan 
pembayaran, maka pembayaran akan diverifikasi secara otomatis oleh sistem dan sistem akan 
secara otomatis meng-update status pemesanan pengguna di aplikasi ReserveApp menjadi 
”waiting”.
Setelah pengguna datang ke restoran sesuai dengan waktu pesanan reservasi, maka 
staff restoran akan mengubah status reservasi menjadi “completed”. Restoran akan 
memberikan tagihan total pembayaran restoran kepada pengguna sesuai dengan jumlah 
pembelian makanan maupun minuman, kemudian dikurangi dengan jumlah deposit yang 
telah dibayarkan. Harga pembelian makanan maupun minuman yang dilakukan oleh 
pengguna harus lebih besar dari jumlah deposit yang dibayarkan. Batas keterlambatan 
kedatangan pengguna ke restoran adalah 15 menit dari jadwal reservasi. Apabila pengguna 
tidak datang ke restoran sesuai dengan jadwal reservasi, maka reservasi akan dibatalkan oleh 
staff restoran dan uang deposit tidak akan dikembalikan kepada pengguna. Kemudian status 
reservasi pengguna akan berubah menjadi “cancelled”. 
Setelah reservasi telah memiliki status “completed”, maka pengguna dapat 
memberikan review untuk restoran tersebut dengan mengakses menu reservation. Pengguna 
dapat memilih reservasi yang ingin diberikan review dan aplikasi akan menampilkan form 
review. Pengguna akan mengisi data form review berupa rating dan isi review untuk restoran. 
Setelah selesai, pengguna dapat menekan tombol submit dan aplikasi akan menampilkan hasil 
rating dan review yang diberikan oleh pengguna pada halaman detail restoran.
Apabila pengguna ingin membatalkan reservasi, maka pengguna dapat memilih 
pesanan yang memiliki status “upcoming” dan aplikasi akan menampilkan detail informasi 
dari pesanan yang dipilih. Setelah itu, pengguna dapat menekan tombol cancel yang terletak 
pada bagian bawah halaman, kemudian aplikasi akan menampilkan form cancel. Pada 
halaman ini, pengguna diwajibkan untuk mengisi alasan pembatalan. Setelah itu, pengguna 
dapat menekan tombol submit dan sistem akan secara otomatis meng-update status reservasi 
menjadi “cancelled”. Biaya deposit yang sudah dibayarkan pada saat melakukan reservasi 
tidak akan dikembalikan jika reservasi dibatalkan oleh pengguna. 
Pengguna juga dapat memberikan feedback untuk aplikasi ReserveApp dengan cara 
mengakses menu profile dan memilih tombol feedback. Selanjutnya, aplikasi akan 
menampilkan form feedback dan pengguna dapat mengisi kritik dan saran untuk aplikasi. 
Setelah selesai, maka pengguna dapat menekan tombol submit dan aplikasi akan menyimpan 
feedback yang telah diberikan oleh pengguna. 
Setiap bulannya, admin ReserveApp akan membuat laporan restoran paling diminati 
pada bulan tersebut yang berisi periode laporan, nama restoran, dan jumlah pengunjung. 
Laporan ini kemudian akan diserahkan kepada manajer ReserveApp sebagai bahan evaluasi 
bulanan