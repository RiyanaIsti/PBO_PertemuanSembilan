## Deskripsi
Project ini merupakan implementasi JasperReports dalam aplikasi Java Swing yang terhubung ke database PostgreSQL. Aplikasi ini memungkinkan pengguna untuk menampilkan dan mencetak laporan data secara dinamis langsung dari GUI. Laporan dibuat menggunakan file .jrxml sebagai template, kemudian dikompilasi menjadi .jasper untuk diisi data dari database. Integrasi JasperReports dengan Java Swing dilakukan melalui JasperViewer agar laporan bisa ditampilkan dan dicetak dari aplikasi tanpa perlu mengekspor manual

## Pengertian
JasperReports adalah library open-source berbasis Java yang digunakan untuk membuat laporan profesional dari berbagai sumber data. Laporan dapat ditampilkan dalam aplikasi Java, dicetak, atau diekspor ke berbagai format seperti PDF, HTML, Excel, dan CSV. JasperReports cocok untuk membuat laporan dinamis dengan layout yang fleksibel, grafik, subreport, dan pengelompokan data.

Proses pembuatan laporan dimulai dari file template dengan ekstensi .jrxml, yang berisi definisi layout, field data, parameter, dan query untuk mengambil data. File .jrxml ini kemudian dikompilasi menjadi file .jasper, yaitu format binary yang siap digunakan oleh aplikasi Java. Selanjutnya, data diisi ke dalam laporan menggunakan JasperFillManager sehingga menghasilkan objek JasperPrint. Objek ini bisa ditampilkan langsung di aplikasi menggunakan JasperViewer atau diekspor ke format lain sesuai kebutuhan. Integrasi JasperReports dengan Java Swing memungkinkan pengguna mencetak laporan secara langsung dari aplikasi, mengatur parameter laporan, dan menyesuaikan tampilan laporan secara dinamis.

## Fitur Utama
- Mendukung parameter dan query database untuk laporan dinamis.
- Bisa mengintegrasikan laporan ke aplikasi Java Swing atau Java Web.
- Menyediakan berbagai output: PDF, HTML, Excel, CSV, dan XML.
- Mendukung grafik, subreport, dan pengelompokan data.
- Mempermudah pembuatan laporan tanpa harus menulis layout secara manual di Java.

## Komponen Penting
- .jrxml: File template laporan berbasis XML, berisi layout, field, dan query data.
- .jasper: File hasil kompilasi .jrxml yang siap dipakai di Java.
- JasperReport: Objek laporan yang dikompilasi dari .jrxml.
- JasperPrint: Objek laporan yang telah diisi data, siap ditampilkan atau dicetak.
- JasperViewer: Digunakan untuk menampilkan laporan di aplikasi Java.

## Cara Instalasi
1. Klik tab Tools
2. Pilih Plugins
3. Pilih Downloaded
4. Add Plugins...
5. Pilih iReport dan org jdesktop layout
6. Lakukan install
7. Tambahkan JasperReports Library ke project Java: jasperreports-x.x.x.jar
8. Tambahkan Dependensi: groovy-all-x.x.x.jar, commons-logging.jar, commons-collections.jar, dll.
9. Tambahkan driver JDBC sesuai database yang digunakan (PostgreSQL).
