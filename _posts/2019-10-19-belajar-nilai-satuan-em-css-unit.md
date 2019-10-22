---
title         : "Belajar Satuan em CSS Unit"
date          : 2019-10-19 01:10:00
description   : belajar menggunakan nilai satuan em untuk blog atau web design
---

sebagai developer web kita pasti sering melihat nilai em pada css.
em merupakan presentase dari ukuran parent yaitu nilai dari font-size. 

em juga merupakan relative unit yaitu ukurannya bergantung dengan font-size element diatasnya (parent) atau didalam seletor yang sama (jika terdapat font-size didalamnya).

untuk menghitung em menurut saya sedikit rumit karena harus melakukan perkalian sama nilai pada font-size.

Contoh 1 :
{% highlight css %}
p {
  font-size:16px;
  border: 0.5em solid black;
}
{% endhighlight %}

maka nilai **0.5 em** adalah **0.5 x 16px = 8px**.

Contoh 2 :
{% highlight html %}
<body>
    <div class="wrapper">Isi Kontent</div>
</body>
{% endhighlight %}

{% highlight css %}
body{
    font-size:14px;
}
div {
    font-size:1.5em;
}
{% endhighlight %}

maka nilai dari **1.5em** adalah **1.5 x 14px = 21px**

sekian dari saya, semoga bermanfaat.
terima kasih.

Referensi :
- https://sekolahkoding.com/forum/responsive-design-perbedaan-rem-em-vh-dan-vw
- https://www.kodingspace.com/css/satuan-em-dan-rem-di-css/
- https://webdesign.tutsplus.com/id/articles/7-css-units-you-might-not-know-about--cms-22573
