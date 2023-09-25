---
layout: post
title:  "Arabada istenilen müziği dinlemenin en kolay yolu"
date:   2023-09-25 14:00:00 +0300
categories: car music
---

Merhabalar,

Bu gönderimde aracında müzik dinlemeyi seven herkes için arabada istenilen müziği dinlemenin en kolay yolunu açıklamaya çalışacağım.
Bu yolun, içinde Android sistemi olan bir arabada test edildiğini belirtmeliyim.

Son model araçlarda bile herkesin şikayet ettiği bir konu vardır:
İstediği zaman istediği müziği dinleyememek.
Sözgelimi radyoda çalan yeni bir şarkıyı beğendiniz ve tekrar tekrar dinlemek istediniz.
Akla gelen ilk yol şüphesiz YouTube, Spotify, vb. bir müzik dinleme uygulamasından bu şarkıyı bulmak, telefonu araca AUX, Bluetooth, vb. bir yolla bağlamak ve şarkıyı çalmak.
Eğer araçta CarPlay ya da Android Auto varsa, telefonunuzdan sadece HotSpot'u açmak ve şarkıyı aracın tablet ekranında bulmak daha kolay olacaktır elbette.

Bu yollar şimdiye kadar icat edilmiş en kolay yollar olarak görünse de bazı dezavantajlara sahipler:

- Kablolar hep bir yerlere dolaşır.
- Kablosuz bağlantıda şarkıların sesi kablolu bağlantı ve USB'ye göre daha kalitesizdir.
- YouTube, Spotify, vb. uygulamalar sürekli internet kotanızı tüketir.

Arabada müzik dinlemeyi çok seven biri olarak bu sorunlara sahip olmayan ve yine de istenilen müziği istenilen zamanda dinlemeyi sağlayacak bir sistem geliştirdim.
Adımlar şunlar:

- YouTube, vb. birçok platformdan çalma listelerini kolaylıkla indirebileceğiniz şu program ile sevdiğiniz şarkıları bir USB'ye indirin:
  https://github.com/yt-dlp/yt-dlp
  Eğer bu program size fazla karmaşık geldiyse herhangi başka bir program da kullanabilir ya da birisinden yardım alabilirsiniz.
- Araçtaki Android ya da CarPlay'den **VLC Player**'ı indirin:
  https://www.videolan.org/vlc/
  Bu oynatıcının oynatamayacağı bir video ya da müzik olduğunu sanmıyorum.
  Yalnız sisteminizin kapasitesi 4k videolar izlemenize izin vermeyebilir.
- Araçtaki Android'e **F-Droid**'i indirip kurun:
  https://f-droid.org/
  Bu programı bir sonraki uygulamayı indirmek için kullanacağız.
- F-Droid uygulamasında _com.junkfood.seal_ ismiyle arama yaparak Seal uygulamasını bulun, indirin ve kurun.
- USB'nizi Android sistemine takın ve Seal uygulamasından _İndirme Dizini_ olarak USB'nizi seçin.
- Şimdi herhangi bir şarkıyı indirip dinlemek istediğinizde tek yapmanız gereken YouTube'da bu şarkıyı bulmak, _Paylaş_ tuşu ile video'nun bağlantısını bulup kopyalamak ve Seal uygulamasına yapıştırarak indirmek.
- Şarkıyı hatta klibi artık VLC Player'da görüp oynatabiliyor olmalısınız.
  En kaliteli müziğe, kotanızdan çok yemeden ve kablo ile uğraşmadan ulaştınız!

Herkese iyi günler dilerim...
