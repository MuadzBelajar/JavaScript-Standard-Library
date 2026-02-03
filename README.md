<h3>JavaScript Standard Library</h3>
<p>
JavaScript Standard Library adalah kumpulan fitur bawaan JavaScript yang menyediakan
berbagai objek, fungsi, dan method untuk mempermudah pengolahan data, logika program,
serta interaksi dengan sistem tanpa perlu library tambahan.
</p>

<h4>1. ARRAY</h4>
<p>
Array digunakan untuk menyimpan banyak data dalam satu variabel. Standard library Array
menyediakan method seperti <code>map</code>, <code>filter</code>, dan <code>reduce</code> untuk memproses data
secara efisien dan bersih.
</p>

<pre><code>
&lt;script&gt;
const numbers = [1, 2, 3, 4];
const doubled = numbers.map(n => n * 2);
console.log(doubled);
&lt;/script&gt;
</code></pre>

<h4>2. BIGINT</h4>
<p>
BigInt digunakan untuk menangani bilangan bulat yang sangat besar dan tidak dapat
ditangani oleh tipe data Number biasa.
</p>

<pre><code>
&lt;script&gt;
const big = 9007199254740991n;
console.log(big + 1n);
&lt;/script&gt;
</code></pre>

<h4>3. BOOLEAN</h4>
<p>
Boolean hanya memiliki dua nilai, yaitu <code>true</code> dan <code>false</code>. Tipe data ini digunakan
untuk logika percabangan, kondisi, dan validasi program.
</p>

<pre><code>
&lt;script&gt;
const isLogin = true;
console.log(Boolean(isLogin));
&lt;/script&gt;
</code></pre>

<h4>4. DATE</h4>
<p>
Date digunakan untuk mengelola waktu dan tanggal, seperti menampilkan tanggal saat ini,
jam, dan melakukan perhitungan waktu.
</p>

<pre><code>
&lt;script&gt;
const now = new Date();
console.log(now.toDateString());
&lt;/script&gt;
</code></pre>

<h4>5. ENCODE</h4>
<p>
Encode digunakan untuk mengamankan data saat dikirim melalui URL agar karakter khusus
tidak menyebabkan error.
</p>

<pre><code>
&lt;script&gt;
const text = "Halo Dunia!";
console.log(encodeURIComponent(text));
&lt;/script&gt;
</code></pre>

<h4>6. EVAL</h4>
<p>
Eval berfungsi untuk menjalankan string sebagai kode JavaScript. Namun, penggunaannya
tidak disarankan karena dapat menimbulkan risiko keamanan.
</p>

<pre><code>
&lt;script&gt;
console.log(eval("5 + 5"));
&lt;/script&gt;
</code></pre>

<h4>7. JSON</h4>
<p>
JSON digunakan untuk pertukaran data antara client dan server. Data JSON dapat
diubah menjadi string atau object menggunakan <code>JSON.stringify</code> dan
<code>JSON.parse</code>.
</p>

<pre><code>
&lt;script&gt;
const user = { name: "Eko", age: 20 };
const json = JSON.stringify(user);
console.log(JSON.parse(json));
&lt;/script&gt;
</code></pre>

<h4>8. MAP</h4>
<p>
Map adalah struktur data key-value yang lebih fleksibel dibandingkan object biasa karena
key dapat berupa tipe data apa pun.
</p>

<pre><code>
&lt;script&gt;
const map = new Map();
map.set("name", "Eko");
console.log(map.get("name"));
&lt;/script&gt;
</code></pre>

<h4>9. MATH</h4>
<p>
Math menyediakan fungsi matematika bawaan seperti akar kuadrat, pembulatan, dan
bilangan acak.
</p>

<pre><code>
&lt;script&gt;
console.log(Math.sqrt(16));
console.log(Math.random());
&lt;/script&gt;
</code></pre>

<h4>10. NUMBER</h4>
<p>
Number menyediakan utilitas untuk mengelola dan memvalidasi angka, seperti mengecek
apakah sebuah nilai adalah bilangan bulat.
</p>

<pre><code>
&lt;script&gt;
const num = 10.5;
console.log(Number.isInteger(num));
&lt;/script&gt;
</code></pre>

<h4>11. OBJECT</h4>
<p>
Object digunakan untuk mengelola properti dan struktur data berbentuk objek.
</p>

<pre><code>
&lt;script&gt;
const person = { name: "Eko" };
console.log(Object.keys(person));
&lt;/script&gt;
</code></pre>

<h4>12. PROXY</h4>
<p>
Proxy digunakan untuk memantau, memodifikasi, atau mengontrol akses terhadap sebuah
object.
</p>

<pre><code>
&lt;script&gt;
const target = {};
const proxy = new Proxy(target, {
  get(obj, prop) {
    return prop in obj ? obj[prop] : "Not Found";
  }
});
console.log(proxy.name);
&lt;/script&gt;
</code></pre>

<h4>13. REFLECT</h4>
<p>
Reflect menyediakan method standar untuk melakukan manipulasi object secara aman
dan konsisten.
</p>

<pre><code>
&lt;script&gt;
const obj = { a: 1 };
Reflect.set(obj, "b", 2);
console.log(obj);
&lt;/script&gt;
</code></pre>

<h4>14. REGEXP</h4>
<p>
RegExp digunakan untuk pencarian dan validasi teks berdasarkan pola tertentu.
</p>

<pre><code>
&lt;script&gt;
const regex = /js/i;
console.log(regex.test("JavaScript"));
&lt;/script&gt;
</code></pre>

<h4>15. SAMPLE JSON</h4>
<p>
Contoh data JSON sederhana yang biasa digunakan dalam pertukaran data.
</p>

<pre><code>
{
  "name": "Eko",
  "age": 20,
  "isStudent": true
}
</code></pre>

<h4>16. SET</h4>
<p>
Set digunakan untuk menyimpan data unik tanpa adanya nilai duplikat.
</p>

<pre><code>
&lt;script&gt;
const set = new Set([1, 2, 2, 3]);
console.log(set);
&lt;/script&gt;
</code></pre>

<h4>17. STRING</h4>
<p>
String menyediakan berbagai method untuk manipulasi teks seperti perubahan huruf,
pemotongan, dan pencarian karakter.
</p>

<pre><code>
&lt;script&gt;
const text = "JavaScript";
console.log(text.toUpperCase());
&lt;/script&gt;
</code></pre>

<h4>18. SYMBOL</h4>
<p>
Symbol digunakan untuk membuat identifier unik pada object agar tidak terjadi konflik
dengan properti lain.
</p>

<pre><code>
&lt;script&gt;
const id = Symbol("id");
console.log(id);
&lt;/script&gt;
</code></pre>

<h4>KESIMPULAN</h4>
<p>
JavaScript Standard Library menyediakan berbagai fitur bawaan yang sangat membantu
dalam pengolahan data, logika program, dan penerapan prinsip OOP. Dengan memahami
standard library, program menjadi lebih efisien, aman, dan mudah dikembangkan.
</p>
