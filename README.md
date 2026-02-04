<h1>JavaScript Standard Library</h1>
<p>
JavaScript Standard Library adalah kumpulan fitur bawaan yang sudah tersedia secara
default di dalam bahasa JavaScript. Library ini menyediakan berbagai objek, fungsi,
dan method yang dapat langsung digunakan tanpa perlu mengimpor library tambahan.
Tujuan utama dari standard library adalah untuk membantu pengembang dalam mengelola
data, menjalankan logika program, serta membangun aplikasi yang efisien, konsisten,
dan mudah dipelihara.
</p>

<h4>1. ARRAY</h4>
<p>
Array merupakan struktur data yang digunakan untuk menyimpan banyak nilai dalam satu
variabel dengan urutan tertentu. JavaScript Standard Library menyediakan berbagai method
pada Array seperti <code>map</code>, <code>filter</code>, <code>reduce</code>, <code>forEach</code>, dan
<code>find</code> yang memungkinkan pengolahan data secara fungsional. Dengan Array, pengembang
dapat mengelola kumpulan data secara lebih rapi, menghindari penggunaan variabel
berulang, serta meningkatkan keterbacaan kode.
</p>

<h4>2. BIGINT</h4>
<p>
BigInt adalah tipe data khusus yang digunakan untuk menangani bilangan bulat dengan
ukuran sangat besar, melebihi batas aman tipe data Number. Dalam JavaScript, Number
memiliki keterbatasan presisi, sehingga BigInt hadir sebagai solusi untuk perhitungan
numerik berskala besar, seperti perhitungan kriptografi, data keuangan, atau sistem
yang membutuhkan akurasi tinggi pada bilangan bulat.
</p>

<h4>3. BOOLEAN</h4>
<p>
Boolean adalah tipe data logika yang hanya memiliki dua nilai, yaitu <code>true</code> dan
<code>false</code>. Boolean sangat penting dalam pengambilan keputusan di dalam program,
seperti percabangan kondisi, validasi input, dan pengendalian alur program. Hampir
seluruh logika aplikasi bergantung pada evaluasi nilai Boolean untuk menentukan
tindakan yang akan dijalankan.
</p>

<h4>4. DATE</h4>
<p>
Object Date digunakan untuk menangani data yang berhubungan dengan waktu dan tanggal.
Dengan Date, pengembang dapat mengambil waktu saat ini, menampilkan tanggal tertentu,
menghitung selisih waktu, serta memformat tanggal sesuai kebutuhan aplikasi. Object ini
sangat penting dalam aplikasi yang berhubungan dengan jadwal, log aktivitas, dan sistem
berbasis waktu.
</p>

<h4>5. ENCODE</h4>
<p>
Fungsi encode dalam JavaScript, seperti <code>encodeURI</code> dan
<code>encodeURIComponent</code>, digunakan untuk mengamankan data yang akan dikirim melalui URL.
Proses encoding memastikan bahwa karakter khusus tidak menyebabkan kesalahan saat data
ditransmisikan melalui jaringan, sehingga komunikasi data antara client dan server
menjadi lebih aman dan stabil.
</p>

<h4>6. EVAL</h4>
<p>
Eval adalah fungsi yang digunakan untuk mengeksekusi string sebagai kode JavaScript.
Meskipun eval memberikan fleksibilitas tinggi, penggunaannya sangat tidak disarankan
dalam praktik pengembangan modern karena berisiko terhadap keamanan dan performa.
Eval dapat membuka celah terhadap serangan injeksi kode dan membuat program sulit
dipelihara.
</p>

<h4>7. JSON</h4>
<p>
JSON (JavaScript Object Notation) adalah format pertukaran data yang ringan dan mudah
dibaca oleh manusia maupun mesin. JSON sangat umum digunakan dalam komunikasi antara
client dan server, terutama pada aplikasi web dan API. JavaScript menyediakan object
JSON dengan method <code>stringify</code> dan <code>parse</code> untuk mengubah data antara
object JavaScript dan format teks JSON.
</p>

<h4>8. MAP</h4>
<p>
Map adalah struktur data key-value yang memungkinkan penggunaan berbagai tipe data
sebagai key, tidak terbatas pada string saja. Map lebih fleksibel dan terstruktur
dibandingkan object biasa, serta memiliki performa yang lebih baik untuk operasi
penyimpanan dan pencarian data dalam jumlah besar.
</p>

<h4>9. MATH</h4>
<p>
Object Math menyediakan berbagai fungsi matematika bawaan seperti perhitungan akar
kuadrat, pembulatan angka, nilai maksimum dan minimum, serta bilangan acak. Math sangat
berguna dalam aplikasi yang membutuhkan perhitungan numerik, simulasi, statistik, dan
pengolahan data berbasis angka.
</p>

<h4>10. NUMBER</h4>
<p>
Object Number menyediakan berbagai utilitas untuk bekerja dengan angka, termasuk
validasi tipe data, konversi nilai, serta pengecekan kondisi tertentu seperti apakah
sebuah nilai merupakan bilangan bulat atau bukan. Dengan Number, pengembang dapat
menghindari kesalahan logika yang berkaitan dengan tipe data numerik.
</p>

<h4>11. OBJECT</h4>
<p>
Object adalah struktur data utama dalam JavaScript yang digunakan untuk menyimpan
pasangan properti dan nilai. Hampir seluruh konsep OOP di JavaScript dibangun di atas
object. Standard library Object menyediakan berbagai method untuk mengelola properti,
menyalin object, serta melakukan introspeksi terhadap struktur data.
</p>

<h4>12. PROXY</h4>
<p>
Proxy memungkinkan pengembang untuk menyisipkan perilaku khusus saat terjadi interaksi
terhadap sebuah object, seperti membaca, menulis, atau menghapus properti. Proxy sering
digunakan untuk validasi data, logging, keamanan, dan penerapan konsep enkapsulasi dalam
OOP secara lebih kuat.
</p>

<h4>13. REFLECT</h4>
<p>
Reflect menyediakan sekumpulan method standar untuk melakukan operasi terhadap object,
seperti membaca, menulis, dan menghapus properti secara eksplisit. Reflect sering
digunakan bersama Proxy untuk menciptakan kode yang lebih konsisten, aman, dan mudah
dipahami.
</p>

<h4>14. REGEXP</h4>
<p>
RegExp (Regular Expression) digunakan untuk pencarian, pencocokan, dan validasi teks
berdasarkan pola tertentu. Dengan RegExp, pengembang dapat memeriksa format input,
melakukan pencarian kompleks dalam string, serta memanipulasi teks secara efisien.
</p>

<h4>15. SAMPLE JSON</h4>
<p>
Sample JSON merupakan contoh struktur data dalam format JSON yang sering digunakan
untuk menyimpan dan mengirim data. Struktur ini mendukung tipe data dasar seperti
string, number, boolean, array, dan object, sehingga sangat fleksibel untuk berbagai
kebutuhan aplikasi.
</p>

<h4>16. SET</h4>
<p>
Set adalah struktur data yang menyimpan nilai unik tanpa duplikasi. Set sangat berguna
ketika aplikasi membutuhkan daftar data yang tidak boleh memiliki nilai ganda, seperti
daftar ID, kategori unik, atau hasil pengolahan data tertentu.
</p>

<h4>17. STRING</h4>
<p>
String digunakan untuk mengelola data teks. JavaScript menyediakan banyak method String
untuk manipulasi teks, seperti pengubahan huruf besar dan kecil, pemotongan teks,
pencarian karakter, serta penggabungan string. String merupakan elemen penting dalam
pengolahan input dan output pengguna.
</p>

<h4>18. SYMBOL</h4>
<p>
Symbol adalah tipe data primitif yang digunakan untuk membuat identifier unik. Symbol
sering digunakan sebagai key object untuk mencegah konflik nama properti, terutama pada
aplikasi besar atau library yang saling berinteraksi.
</p>

<h4>KESIMPULAN</h4>
<p>
JavaScript Standard Library menyediakan berbagai fitur bawaan yang sangat penting dalam
pengembangan aplikasi modern. Dengan memahami dan memanfaatkan standard library secara
optimal, pengembang dapat menulis kode yang lebih efisien, aman, terstruktur, serta
mudah dikembangkan dan dirawat.
</p>
