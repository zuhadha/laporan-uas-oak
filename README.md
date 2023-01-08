# Latar Belakang Praktikum
&emsp;&emsp;Perkembangan teknologi elektronika saat ini sudah sedemikian pesatnya yang kadang-kadang berawal dari rangkaian angkaian sederhana yang biasa kita jumpaidalam buku- buku hobby elektronika.Rangkaian lampu malam otomatis berfungsi untuk mengendalikan nyalalampu pada malam hari secara otomatis. Lampu otomatis yang dapat menyala padamalam hari yang dapat kita temui adalah lampu taman, lampu jalan dan lainnya.Lampu tersebut dapat menyala secara otomatis pada malam hari karena dikontrol menggunakan rangkaian yang dapat membedakan siang dan malam. <br />
&emsp;&emsp;Rangkaian lampu otomatis adalah suatu rangkaian yang dapat menghidupkan dan mematikan lampu secara otomatis. Rangkaian lampu otomatis ini umumnya dapat menyala dan mati pada siang dan malam hari. Lampu otomatis yang sering di jumpai yaitu lampu taman, lampu jalan, lampu tidur dan lampu lainnya. Lampu ini dapat menyala kapan saja berdasarkan intensitas cahaya di luar dimana sensor ditempatkan, maka dari itu lampu ini menggunakan sensor cahaya yaitu LDR (Light Dependent Resistor). LDR adalah sebuah sensor yang dapat berubah hambatannya berdasarkan cahaya yang mengenainya. Semakin besar intensitas cahaya yang terkena LDR maka akan semakin kecil resistansinya, begitupun sebaliknya semakin kecil intensitas cahaya yang terkena LDR maka akan besar resistansinya.

# Tujuan Praktikum
&emsp;&emsp;Adapun tujuan dari diakan praktikum ini yaitu untuk: <br />
1. Mengetahui prinsip kerja dari sensor cahaya LDR.<br /> 
2. Mengetahui prinsip kerja relay.<br />
4. Mampu memahami cara kerja lampu tidur otomatis cahaya arus AC.<br />
5. Mampu membuat rangkai hardware lampu tidur otomatis arus AC.<br />

# Transistor
&emsp;&emsp;Transistor merupakan alat semikonduktor yang dipakai sebagai sirkuit pemutus dan penyambung, stabilisasi tegangan, penguat, dan sebagainya. Berdasarkan arus inputnya (BJT) atau tegangan inputnya (FET), memungkinkan pengaliran listirk yang sangat akurat dari sirkuit sumber listriknya, oleh karena itu, transistor dapat berfungsi sebagai kran listrik.<br /><br />
Jenis Jenis Transistor<br />
1. BJT (bipolar Junction Transistor)<br />
Transistor jenis ini mempunyai dua buah dioda, terminal positif atau negatif berdempet sehingga terdapat tiga terminal. Ketiga terminal tersebut adalah emitor (E), kolektor (C) dan basis (B). Perubahan kecil arus pada terminal basis dapat mengakibatkan perubahan besar arus pada terminal kolektor. Prinsip ini mendasari penggunaan transistor sebagai penguat elektronik.<br />
&emsp;a) Transistor NPN<br />
Sambungan steker positif (+) diperlukan pada kaki basis untuk memungkinkan arus mengalir melalui transistor NPN. Cara kerja NPN adalah ketika tegangan mencapai kaki basis, ia menginduksi arus dari kolektor ke emitor hingga mencapai titik jenuh. Dan transistor masuk ke logika 1 (aktif). Ketika arus yang mengalir melalui basis berkurang, maka arus yang mengalir dari kolektor ke emitor akan berkurang hingga titik cutoff.<br />
&emsp;b) Transistor PNP<br />
Di sisi lain, untuk PNP, ketika arus mengalir melalui kaki basis, transistor berlogika 0 (mati). Arus mengalir ketika kaki basis terhubung ke ground (-). Ini menginduksi arus dari emitor ke kolektor, tidak seperti NPN di mana arus mengalir dari kolektor ke emitor.<br />
2. FET (Field Effect Transistor)<br />
Jenis transistor ini dapat dibagi menjadi dua jenis: Junction FET (JFET) dan Insulated Gate FET (IGFET) / Metal Oxide Silicon FET (MOSFET). Berbeda dengan IGFET, terminal gerbang JFET membentuk dioda dengan saluran bahan semikonduktor antara sumber dan saluran. Secara fungsional, ini mengubah N- channel JFET menjadi versi solid-state dari tabung vakum, juga membentuk dioda antara grid dan katoda.

# Light Dependent Resistor
&emsp;&emsp;LDR merupakan komponen elektronika yang resistansinya akan menurun ketika ada cahaya yang mengenainya. LDR terbuat dari film cadmium sulfide (semikonduktor) yang mempunyai resistensi tinggi ketika tidak ada cahaya dan sebaliknya. Ketika semikonduktor menyerap cahaya/foton dengan frekuensi yang cukup tinggi, akan menyebabkan elektron berpindah ke pita konduksi. Elektron bebas yang dihasilkan akan mengalirkan listrik. Nilai resistansi LDR pada keadaan lingkungan terang bisa mencapai 1 ohm dan ketika pada keadaan lingkungan gelap bisa mencapai 1M ohm.<br />
1. Prinsip Kerja LDR<br />
Pada sisi bagian atas LDR terdapat suatu garis atau jalur melengkung yang menyerupai bentuk kurva.Jalur tersebut terbuat dari bahan cadmium sulphidayang sangat sensitiv terhadap pengaruh dari cahaya.Jalur cadmium sulphida yang terdapat pada LDR.Jalur cadmium sulphida dibuat melengkung menyerupai kurvaagar jalur tersebut dapat dibuat panjang dalam ruang (area) yang sempit. Cadmiumsulphida (CdS) merupakan bahan semi-konduktor yang memiliki gap energiantara elektron konduksi dan elektron valensi. Ketika cahaya mengenai cadmiumsulphida, maka energi proton dari cahaya akan diserap sehingga terjadi perpindahan dari band valensi ka band konduksi. perpindahan elektrontersebut mengakibatkan hambatan dari cadmium sulphida berkurang denganhubungan kebalikan dari intensitas cahaya yang mengenai LDR.Lihat gambar dibawah ini.<br />
2. Karakteristik LDR<br />
&emsp;a) Laju Recovery<br />
Bila sebuah LDR dibawa dari suatu ruangan dengan level kekuatan cahayatertentu kedalam suatu ruangan yang gelap sekali, maka bisa kita amati bahwa nilai resistansi dari LDR tidak akan segera berubah resistansinya pada keadaan ruangan gelap tersebut. Namun LDR tersebut hanya akan bisa mencapai harga dikegelapan setelah mengalami selang waktu tertentu. dan suatu kenaikan nilai resistansi dalam waktu tertentu. Harga ini ditulis dalam K Ω /detik. untuk LDR type arus harganya lebih besar dari 200 K Ω /detik (selama 20 menitpertama mulai dari level cahaya 100 lux), kecepatan tersebut akan lebih tinggi pada arah sebaliknya, yaitu pindah dari tempat gelap ke tempat terang yang memerlukan waktukurang dari 10 ms untuk mencapai resistansi yang sesuai dengan level cahaya 400 lux.<br />
&emsp;b) Respon Spektral<br />
LDR tidak mempunyai sensitivitas yang sama untuk setiap panjang gelombang cahaya yang jatuh padanya (yaitu warna). Bahan yang biasa digunakan sebagai penghantar arus listrik yaitu tembaga, alumunium, baja, emas, dan perak.Dari kelima bahan tersebut tembaga merupakan penghantar yang paling banyak digunakan karena mempunyai daya hantar yang baik.Sensor ini sebagai pengindera yang merupakan eleman yang pertama – tama menerima energi dari media untuk memberi keluaran berupa perubahan energi.Sensor terdiri berbagai macam jenis serta media yang digunakan untuk melakukan perubahan. Media yang digunakan misalnya: panas, cahaya, air, angin, tekanan, dan lain sebagainya. Sedangkan pada rangkaian ini menggunakan sensor LDR yang menggunakan intensitas cahaya, selain LDR dioda foto juga menggunakan intensitas cahaya atau yang peka terhadap cahaya ( photoconductivecell).Pada rangkaian elektronika, sensor harus dapat mengubah bentuk – bentuk energi cahaya ke energi listrik, sinyal listrik ini harus sebanding dengan besar energi sumbernya.<br />
Pada karakteristik diatas dapat dilihat bila cahaya mengenai sensor itu maka harga tahanan akan berkurang. Perubahan yang dihasilkan ini tergantung dari bahan yang digunakan serta dari cahaya yang mengenainya.<br />
&emsp;c) Op Amp<br />
Operasional amplifier (Op-Amp) adalah suatu penguat berpenguatan tinggi yang terintegrasi dalam sebuah chip IC yang memiliki dua input inverting dan non- inverting dengan sebuah terminal output, dimana rangkaian umpan balik dapat ditambahkan untuk mengendalikan karakteristik tanggapan keseluruhan pada operasional amplifier (Op-Amp). Pada dasarnya operasional amplifier (Op-Amp) merupakan suatu penguat diferensial yang memiliki 2 input dan 1 output. Op-amp ini digunakan untuk membentuk fungsi-fungsi linier yang bermacam-mcam atau dapat juga digunakan untuk operasi-operasi tak linier, dan seringkali disebut sebagai rangkaian terpadu linier dasar. Penguat operasional (Op-Amp) merupakan komponen elektronika analog yang berfungsi sebagai amplifier multiguna dalam bentuk IC dan memiliki simbol, yaitu:<br />
Symbol Operasional Amplifier (Op-Amp)<br />
Prinsip kerja sebuah operasional Amplifier (Op-Amp) adalah membandingkan nilai kedua input (input inverting dan input non- inverting), apabila kedua input bernilai sama maka output Op-amp tidak ada (nol) dan apabila terdapat perbedaan nilai input keduanya maka output Op-amp akan memberikan tegangan output. Operasional amplifier (Op-Amp) dibuat dari penguat diferensial dengan 2 input. Sebagai penguat operasional ideal, opeasional amplifier (Op-Amp) memiliki karaterisktik sebagai berikut : Impedansi Input (Zi) besar = ∞ V0 = 0 apabila V1 = V2 dan tidak tergantung pada besarnya V1. Karaerisktik operasional amplifier (OP-Amp) tidak tergantung temperature / suhu.<br />

# Resistor
&emsp;&emsp;Resistor merupakan komponen elektronika yang memiliki nilai resistansi. Resistor berfungsi untuk membatasi dan mengatur arus listrik dalam suatu rangkaian. Resistansi resistor memiliki satuan Ohm yang diambil dari nama penemunya yaitu Georg Simon Ohm.<br />
&emsp;&emsp;Warna gelang pada resistor menunjukan nilai resistansi yang dimiliki resistor. Resistor memiliki karakteristik resistansi dan toleransi, serta resistor tidak memiliki kutub. Nilai resistansi resistor dapat diubah dengan merangkainya secara seri atau paralel.<br />

# Relay
&emsp;&emsp;Relay adalah Saklar (Switch) yang dioperasikan secara listrik dan merupakan komponen Electromechanical (Elektromekanikal) yang terdiri dari 2 bagian utama yakni Elektromagnet (Coil) dan Mekanikal (seperangkat Kontak Saklar/Switch). Relay menggunakan Prinsip Elektromagnetik untuk menggerakkan Kontak Saklar sehingga dengan arus listrik yang kecil (low power) dapat menghantarkan listrik yang bertegangan lebih tinggi. Sebagai contoh, dengan Relay yang menggunakan Elektromagnet 5V dan 50 mA mampu menggerakan Armature Relay (yang berfungsi sebagai saklarnya) untuk menghantarkan listrik 220V 2A.

# Lampu
&emsp;&emsp;Lampu adalah sebuah peranti yang memproduksi cahaya. Kata "lampu" dapat juga berarti bola lampu. Lampu pertama yang di produksi adalah lampu pijar. Lampu pijar adalah sumber cahay buatan yang dihasilkan melalui penyaluran arus listik melalui filamen kemudian memanas dan menghasilkan cahaya. Kaca yang menyelubungi filamen panas tersebut menghalangi udara untuk berhubungan dengannya sehingga filamen tidak akan langsung rusak akibat teroksidasi. Komponen utama dari lampu pijar adalah bola lampu yang terbuat dari kaca. Filamen yang terbuat dari wolfram, dasar kampu yang terdiri dari filamen, bola lampu, gas pengisi, dam kaki lampu.

# Alat dan Bahan Praktikum
1. Transistor TIP41C (1 buah)<br />
2. Papan PCB (2 buah)<br />
3. Relay 5V (1 buah)<br />
4. Baterai 9V (1 buah)<br />
5. Dudukan Baterai (1 buah)<br />
6. Resistor 10.000 Ohm (1 buah)<br />
7. Lampu AC (1 buah)<br />
8. Kabel Jumper (4 buah)<br />
9. Kabel (1 meter)<br />
10. Header (+- 10 buah)<br />
11. Solder (1 buah)<br />
12. Timah (30 cm)<br />
13. Steker Lampu (1 buah)<br />
14. Terminal Blok (1 buah)<br />

# Tempat dan Waktu Praktikum
1. Tempat<br />
Praktikum perancangan dilakukan di salah satu kediaman anggota kelompok di Cipadung. Praktikum dilakukan selama 2 hari belum termasuk proses pengumpulan alat dan bahan.<br />
3. Waktu<br />
Pelaksanaan praktikum dilakukan pada tanggal 10 - 14 Desember 2022 di jam yang relatif fleksibel pagi hingga sore hari.<br />

# Prosedur Percobaan
![Alt text](https://github.com/zuhadha/laporan-uas-oak/blob/main/prosedur%20pelaksanaan.png "Prosedur Percobaan")
# Langkah Kerja
Berikut beberapa langkah kerja dari prose pembuatan program lampu tidur otomatis:
1. Persipakan Alat dan Bahan
2. Cek keadaan alat dan bahan dan pastikan dalam kondiis baik
3. Perhatikan keselatan dan Kesehatan kerja
4. Rangkailah percobaan sesuai dengan gambar berikut
5. Masukkan sumber tegangan DC
6. Atur nilai hambatan pada LDR
7. Amati perubahan pada output rangkaian
8. Tulis hasil percobaan
9. Konsultasikan pada asisten praktikum jika ada kesulitan
10. Jika percobaaan di rasa cukup , rapikan alat dan bahan, kemudian kembalikan ke
tempat semula
11. Berikan hasil percobaan pada asisten praktikum
12. Buat laporan mengenai percobaan yang sudah di lakukan
 























