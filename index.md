# Pengantar Pengolahan Citra

- Citra sering disebut juga gambar pada bidang dwimatra (2-D).
- Citra adalah sinyal dwimatra yang bersifat menerus (continue) yang dapat diamati oleh sistem visual manusia
- Secara matematis, citra adalah fungsi dwimatra yang menyatakan intensitas cahaya pada bidang dwimatra. f x y ( , ) (x, y) : koordinat pada bidang dwimatra

> f(x, y) : intensitas cahaya (brightness) pada titik (x, y)

Data atau informasi tidak hanya disajikan dalam bentuk teks, tetapi juga dapat berupa gambar, audio (bunyi, suara, musik), dan video. Keempat macam data atau informasi ini sering disebut multimedia. Era teknologi informasi saat ini tidak dapat dipisahkan dari multimedia. Situs web (website) di internet dibuat semenarik mungkin dengan menyertakan visualisasi berupa gambar atau video yang dapat diputar. Beberapa waktu lalu istilah SMS (Short Message Service) begitu populer bagi pengguna telepon genggam (handphone atau HP). Tetapi, saat ini orang tidak hanya dapat mengirim pesan dalam bentuk teks, tetapi juga dapat mengirim pesan berupa gambar maupun video, yang dikenal dengan layanan MMS (Multimedia Message Service).

Citra (image) adalah istilah lain untuk gambar. Sebagai salah satu komponen multimedia memegang peranan sangat penting sebagai bentuk informasi visual. Citra mempunyai karakteristik yang tidak dimiliki oleh data teks, yaitu citra kaya dengan informasi. Ada sebuah peribahasa yang berbunyi “sebuah gambar bermakna lebih dari seribu kata” (a picture is more than a thousand words). Maksudnya tentu sebuah gambar dapat memberikan informasi yang lebih banyak daripada informasi tersebut disajikan dalam bentuk kata-kata (tekstual).

Image processing, image analysist, image understanding, computer vision Keempat istilah diatas sering dijumpai dalam mempelajari pengolahan citra digital. Belum ada keterangan yang jelas tentang batasan pengolahan dengan aplikasi citra lainnya seperti analisiscitra, deskripsi citra, dan visi computer. Namun keempat istilah diatas sering kali dibedakan dariinput dan outputnya.Image processing memiliki input dan outputnya berupa citra. Sebagai contoh, suatu citraditransformasi ke bentuk citra yang lainnya.Input analysist memiliki input berupa citra dengan output bukan citra akan tetapi berupa hasilpengukuran terhadap citra tersebut. Sebagai contoh, suatu citra wajah dianalisis untuk mendapatkan fitur wajah seperti jarak kedua mata dan jarak mata dengan hidung.

Pengolahan citra (Image Processing) adalah salah satu cabang dari ilmu informatika. Pengolahan citra berkutat pada usaha untuk melakukan transformasi suatu citra/gambar menjadi citra lain dengan menggunakan teknik tertentu.

Analisis Citra (Image Analysis), Operasi ini bertujuan untuk menghitung besaran kuantitatif citra untuk menghasilkan deskripsinya. Teknik analisis citra mengekstraksi ciri-ciri tertentu yang membantu dalam identifikasi obyek. Proses segmentasi kadangkala diperlukan untuk melokalisasi obyek yang diinginkan dari sekelilingnya.

Pemahaman Data Citra (Image Understanding), Pada bagian ini akan melibatkan kajian tentang teknikteknik artificial intelligent. Understanding berkaitan dengn template matching yang ada dalam sebuah scene. Metoda ini menggunakan program pencarian (search program)dan teknik penyesuaian pola (pattern matching techniques).

Computer Vision adalah ilmu dan teknologi mesin yang melihat, di mana lihat dalam hal ini berarti bahwa mesin mampu mengekstrak informasi dari gambar yang diperlukan untuk menyelesaikan tugas tertentu. Sebagai suatu disiplin ilmu, visi komputer berkaitan dengan teori di balik sistem buatan bahwa ekstrak informasi dari gambar. Data gambar dapat mengambil banyak bentuk, seperti urutan video, pandangan dari beberapa kamera, atau data multi-dimensi dari scanner medis.

Computer Vision didefinisikan sebagai salah satu cabang ilmu pengetahuan yang mempelajari bagaimana komputer dapat mengenali obyek yang diamati/ diobservasi. Cabang ilmu ini bersama Intelijensia Semu (Artificial Intelligence) akan mampu menghasilkan sistem intelijen visual (Visual Intelligence System).Perbedaannya adalah computer vision lebih mempelajari bagaimana komputer dapat mengenali obyek yang diamati/ diobservasi. Namun komputer grafika lebih ke arah pemanipulasian gambar (visual) secara digital. Bentuk sederhana dari grafika komputer adalah grafika komputer 2D yang kemudian berkembang menjadi grafika komputer 3D, pemrosesan citra (image processing), dan pengenalan pola (pattern recognition). Grafika komputer sering dikenal juga dengan istilah visualisasi data.

Computer Vision adalah kombinasi antara :

- Pengolahan Citra (Image Processing), bidang ini berhubungan dengan proses transformasi citra/gambar (image). Proses ini bertujuan untuk mendapatkan kualitas citra yang lebih baik.
- Pengenalan Pola (Pattern Recognition), bidang ini berhubungan dengan proses identifikasi obyek pada citra atau interpretasi citra. Proses ini bertujuan untuk mengekstrak informasi/pesan yang disampaikan oleh gambar/citra.

### Kategori Pengolahan Citra

Pengolahan citra dapat dibagi kedalam tiga kategori yakni kategori rendah, menengah, dan tinggi.

- Kategori rendah melibatkan operasi-operasi sederhana seperti prapengolahan citra untuk mengurangi derau, pengaturan kontras, dan pengaturan ketajaman citra. Pengolahan kategori rendah ini memiliki input dan output berupa citra.
- Pengolahan kategori menengah melibatkan operasi-operasi seperti segmentasi dan klasifikasi citra. Proses pengolahan citra menengah ini melibatkan input berupa citra dan output berupa atribut (fitur) citra yang dipisahkan dari citra input. Pengolahan citra kategori melibatkan proses pengenalan dan deskripsi citra.
- Pengohalan kategori tinggi ini termasuk menjadikan objek-objek yang sudah dikenali menjadi lebih berguna, berkaitan dengan aplikasi, serta melakukan fungsi-fungsi kognitif yang diasosiasikan dengan vision.

### Penerapan Pengolahan Citra

1. Bidang Biomedis (Boimedical)
Pengolahan citra digital mengalami kemajuan penting dalam bidang kedokteranketika ditemukannya omografi terkomputerisasi (Computer Terized Tomography/CT) padatahun 1970-an dan kini teknologi tomografi tersebut sudah maju sangat pesat. Pengolahancitra digital dapat digunakan untuk deteksi tumor atau kanker rahim, identifikasi penyakitparu-paru, identifikasi penyakit hati, identifikasi penyakit tulang, segmentasi tulang dari ototyang lainnya, klasifikasi gigi, dan analisis citra mikroskopis. Beberapa dari kemajuan pada bidang kedokteran tersebut karena kemampuanpengolahan citra digital mampu menginterpretasikan sinar x (x ray). Kemajuan pentinglainnya adalah aplikasi volumetric 3D Magnetic Resonance Imaging (MRI) yang mampumendapatkan pencitraan organ dalam tubuh secara jelas dengan menggunakan scanner MRI. 

2. Penginderaan Jauh
Informasi penting dari sumber-sumber alam seperti pertanian, perairan, kelautan, mineral dan geologi dapat diperoleh dengan melakukan analisis citra terhadap citra satelitnya. Pencemaran air laut, kerusakan wilayah, dan pencemaran atrau polusi udara dapat dilakukan dengan menganalisis citra satelitnya. Aplikasi ini digunakan untuk mengetahui kapal laut yang melewati perbatasan wilayah laut Negara.

3. Tekhnologi Pengaman
Suatu system mengalami kemajuan pesat akibat dari pesatnya perkembangan pengolahan citra pada bidang biometrika. Sebagai contoh pemanfaatan sidik jari, iris, wajah, dan biometrika yang lainnya untuk system identifikasi seseorang.

3. Bidang Fotografi
Kemajuan dibidang fotografi membri dampak pada bidang-bidang astronomi, photogrametry, dan fisika partikel. Para astronom dapat melakukan pengukuran terhadap posisi dan jarak suatu bintang dari foto udara. Para fisikiawan menggunakan citra dari gelembung hydrogen untuk melakukan penelitian dan telah mengantarkan kepada penemuan berbagai partikel dasar. 

4. Bidang Visual
Dunia arsitektur dapat membuat desain visual suatu bangunan sebelum malakukan pembangunan yang sesungguhnya. Desain cisual akan sangat mempermudah para arsitek dalam memberikan penjelasan rinci terhadap suatu rancangannya. 

5. Identifikasi Objek
Pengolahan citra digital mampumengidentifikasi jenis atau banyak-nya objek-objek pada suatu citra. Contoh aplikasinya adalah menghitung jumlah sel darah merah yang rusak atau mengetahui kondisi sel darah, menghitung volume dari sampel citra gelembung yang diakibatkan air laut, menghitung jimlah gelembung pada citra gelembung sabun, dan menentukan jumlah penyebaran partikel pigmen pada citra kulit. 

6. Bidang Volumetrik
Salah satu kemajuan penting dalam dunia computer grafis adalah bidang volumetric yaitu untuk merekonstruksi suatu citra 3 dimendi dari citra 2 dimensi. 

7. Meneliti Proses Dinamis
Penelitian proses dinamis dapat dibantu dengan menggunakan rangkaian citra yang berurutan sesuai dengan perubahan yang terjadi. Aplikasi ini banyak dijumpai di berbagai ilmu pengetahuan seperti dalam ilmu botani. Ilmu botani mempelajari tentang pertumbuhan tanaman dan mekanisme untuk mengontrol pertumbuhan tersebutContoh lainnya dating dari disiplin ilmu oseanografi. Utuk meneliti proses mikro yang terjadi di permukaan laut dan daerah sekitarnya. Terkadang akan sangat sulit untuk melakukan perhitungan karena adanya pergerakan gelombang. Untuk itu diperlukan adanya citra urutan yang dapat menggambarkan setiap perubahan yang terjadi. Para ahli akan dapat melakukan pengukuran berdasarkan perbedaan citra-citra terurut tersebut.

8. OCR
Salah satu aplikasi yang penting dakam dunia pengolahan citra adalah pengenalan objek. Aplikasi yang paling banyak dijumpai adalah OCR (Optical Character Recognition). Aplikasi OCR sering digunakan untuk mengedintifikasi citra huruf untuk kemudian diubah kedalam bentuk file tulisan. Aplikasi ORC juga digunakan di dunia industri seperti industri elektronik untuk mengenali label-label yang ada pada circuit board.

9. Bidang Penerapan Citra dan Video
Tekhnolongu pemanfaatan citra dan video berkembang sangat pesat sekarang ini. Tekhnologi ini mampu memanfaatkan citra dan video dengan rasio yang tinggi. Dampak kemajuan tekhnologi ini sangat bermanfaat dan begitu terasa pada era internet ini di mana bandwidth menjadi sesuatu yang mahal.

10. Image Retrieval atau Image Querying
Adalah aplikasi pengolahan citra yang dapat membantu pengguna mengambil atau mencari dengan cepat suatu citra pada suatu database citra berdasarkan query atau permintaan pengguna. Database pada umumnya memiliki ukuran dalam skala besar. Seperti pada gambar di bawah pengguna memasukkan citra wajah dan telapak tangan kemudian system akan mencari dan menampilkan citra-citra yang mirip dengan query.
