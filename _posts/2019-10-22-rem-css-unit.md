---
title         : "Belajar Satuan rem CSS Unit"
date          : 2019-10-22 0:10:00
description   : belajar menggunakan nilai satuan rem (root em) css units
---

setelah saya memposting [css satuan em sebelumnya](https://zulfkr.my.id/2019/belajar-nilai-satuan-em-css-unit/), kali ini saya akan membahas tentang nilai satuan **REM**.

pada mulanya **rem** ini masih sangat asing bagi saya karena saya belum tau cara menggunakanya dan pada saat tertentu saya tidak sengaja membaca sebuah artikel dari [sitepoint](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/) tentang **rem**

dan ternyata sangat mudah dipahami seperti pengunaan px (pixel). dan juga satuan ini sangat sering digunakan oleh developer luar negri dalam mendesain sebuah blog.

rem singkatan dari **root em**, satuan ini sangat berbeda dengan em yang dimana nilainya terpaku pada font-size didalam selektor yang sama atau diatas elementnya / induk (parent).

**nilai rem** hanya terpaku pada font-size di element root yaitu ```<html>```. dan nilai default ```1rem``` yaitu ```16px``` karena nilai default html adalah 16px.

![css rem units](https://zulfkr.my.id/assets/post/rem-css-units-1.png)

### Contoh Kasus Penggunaan rem

berikut contoh saya ingin mengatur nilai font-size pada **body 12px** tapi menggunakan rem. dan disini **root 16px**

```css 
html {
  font-size:16px;
}
body{
  font-size:0.75rem;
}
```

maka nilai **0.75rem** adalah **12px**. karena **12px / 16px = 0.75 rem**

kasus lain yang memiiki nilai terlalu banyak yaitu **root 17px** dan **body 13px**
```css 
html {
  font-size:17px;
}
body{
  font-size:0.7647058823529412‬rem;
}
```
tapi error, saya gak tau penyebabnya. invalid property valued. 

sehingga saya menyarankan menggunakan [rem calculator](https://offroadcode.com/rem-calculator)
dengan memiliki hasil yang berbeda dan lebih sedikit nilainya yaitu **13px = 0.7647rem**

### Rumus Konversi Nilai Rem ke Px atau Sebaliknya

berikut rumus yang saya buat yaitu cara mengetahui nilai px dari rem atau sebaliknya nilai rem ke px

**Menentukan Nilai Rem:**
```js
px / root = rem
```

**Menentukan Nilai Px**
```js
root * rem = px
```

Catatan :
* root = nilai font-size dari <html>
* px = nilai px
* rem = nilai rem

<br>
### Trick atau Solusi Rem Rasa Px

ada juga metode gampang bagi anda yang ingin menerapkan rem tapi seperti menggunakan px.

yaitu dengan cara mengatur nilai root / html menjadi **62.5%**
```css 
html {
  font-size:62.5%;
}
```
**62.5% bernilai 10px**

sekarang kita dapat menggunakan **rem** seperti menggunakan "**px**"
```css 
body {
  font-size:1.6rem; /* 16px */
}
h1 {
  font-size:2.2rem; /* 22px */
}
h2 {
  font-size:1.8rem; /* 18px */
}
h3 {
  font-size:1rem; /* 10px */
}
```

kesimpulannya seperti **16px** menjadi **1.6rem** atau **30px** menjadi **3.0rem**

sekian dari saya, semoga bermanfaat.
terima kasih.

Referensi :
- https://www.sitepoint.com/understanding-and-using-rem-units-in-css/
- https://sekolahkoding.com/forum/responsive-design-perbedaan-rem-em-vh-dan-vw
- https://www.kodingspace.com/css/satuan-em-dan-rem-di-css/
- https://webdesign.tutsplus.com/id/articles/7-css-units-you-might-not-know-about--cms-22573

<!--
nilai root / nilai px = persen rem
10 / 16 = 0.625
-------------------
nilai persen * nilai font = nilai rem
0.0625

20 px / 16 r = 1.25 rem (cocok)
-->
