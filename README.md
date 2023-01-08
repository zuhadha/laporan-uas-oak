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
&emsp;&emsp;Transistor merupakan alat semikonduktor yang dipakai sebagai sirkuit pemutus dan penyambung, stabilisasi tegangan, penguat, dan sebagainya. Berdasarkan arus inputnya (BJT) atau tegangan inputnya (FET), memungkinkan pengaliran listirk yang sangat akurat dari sirkuit sumber listriknya, oleh karena itu, transistor dapat berfungsi sebagai kran listrik.<br />
Jenis Jenis Transistor<br />
1. BJT (bipolar Junction Transistor)<br />
Transistor jenis ini mempunyai dua buah dioda, terminal positif atau negatif berdempet sehingga terdapat tiga terminal. Ketiga terminal tersebut adalah emitor (E), kolektor (C) dan basis (B). Perubahan kecil arus pada terminal basis dapat mengakibatkan perubahan besar arus pada terminal kolektor. Prinsip ini mendasari penggunaan transistor sebagai penguat elektronik.<br />
&emsp;a) Transistor NPN<br />
Sambungan steker positif (+) diperlukan pada kaki basis untuk memungkinkan arus mengalir melalui transistor NPN. Cara kerja NPN adalah ketika tegangan mencapai kaki basis, ia menginduksi arus dari kolektor ke emitor hingga mencapai titik jenuh. Dan transistor masuk ke logika 1 (aktif). Ketika arus yang mengalir melalui basis berkurang, maka arus yang mengalir dari kolektor ke emitor akan berkurang hingga titik cutoff.<br />
&emsp;b) Transistor PNP<br />
Di sisi lain, untuk PNP, ketika arus mengalir melalui kaki basis, transistor berlogika 0 (mati). Arus mengalir ketika kaki basis terhubung ke ground (-). Ini menginduksi arus dari emitor ke kolektor, tidak seperti NPN di mana arus mengalir dari kolektor ke emitor.<br />
2. FET (Field Effect Transistor)
Jenis transistor ini dapat dibagi menjadi dua jenis: Junction FET (JFET) dan Insulated Gate FET (IGFET) / Metal Oxide Silicon FET (MOSFET). Berbeda dengan IGFET, terminal gerbang JFET membentuk dioda dengan saluran bahan semikonduktor antara sumber dan saluran. Secara fungsional, ini mengubah N- channel JFET menjadi versi solid-state dari tabung vakum, juga membentuk dioda antara grid dan katoda.
