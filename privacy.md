---
title: Privacy Policy
permalink: /privacy.html
---

<p class="lang-switch"><a href="#en">English</a> · <a href="#tr">Türkçe</a> · <a href="#hu">Magyar</a></p>

<p><a href="{{ '/' | relative_url }}">Support</a> · <a href="{{ '/privacy' | relative_url }}">Privacy</a> · <a href="{{ '/terms' | relative_url }}">Terms</a></p>

<h2 id="en">Privacy Policy (English)</h2>

**Effective date: 9 October 2026**

### 1. The short version

- Your photos, image vectors, recognized text and searches never leave your phone.
- No account. No ads. No tracking.
- The network is used only for store purchases and one download of the search model.
- On Android, Google's text and face recognition (ML Kit) may send anonymous performance diagnostics to Google Play services. They never include your photos, the text found in them, or your searches. Section 4 explains.
- If you write to us or visit this website, a little data is processed for that (section 9).

### 2. Who we are

WhichToKeep (called HangisiKalsın in Turkish) is published by **Coditive**. Contact for privacy questions: **kasim@mitrabilisim.com.tr**.

The app itself sends us nothing: Coditive runs no server that receives your photos, your analysis results or your decisions from the app. Outside the app a small amount of data is processed when you contact us or visit this website; section 9 lists it.

### 3. What stays on your device

The app looks through the photos and videos in your library, with your permission, to find duplicates, similar shots, screenshots, blurry photos, large videos and things you describe. To do that it keeps, in the app's private storage on your phone:

- file facts: size, date, dimensions, folder or album, favorite flag, and small thumbnails used for analysis and display;
- analysis results: image fingerprints for duplicates, sharpness and brightness numbers, and <!-- MODEL-HOST --> an image vector (a list of numbers describing what is in the image) produced by an image–text model that runs on your device;
- for photos with faces, four values: how many faces there are, a face-quality score, whether eyes are open and whether the person smiles. They are used to suggest the best shot among similar photos and to show the reasons ("eyes open", "smiling") in the head-to-head. The app does not identify anyone and does not store face templates;
- for images that look like greeting cards, text is read to spot greeting phrases. The text is held in memory only while it is checked and is **not stored or logged**; what is kept is which kind of greeting phrase matched (Friday, holiday or good morning). This version does not look for ID cards, bank cards or other sensitive documents;
- your decisions (keep, trash, not sure), the app's trash list, the albums you protect, your saved filters (including the words you typed) and your settings.

None of this is uploaded. Analysis may continue in the background while the phone is charging, when the phone allows it; it runs on the device and you can turn it off in Settings. On Android the app's data is excluded from cloud backup and device transfer. On iPhone the app's database (analysis, image vectors, decisions and saved filters), its size cache and the downloaded search model are excluded from iCloud Backup; small app settings, such as language, theme and mode, can be part of your own iCloud Backup. You decide how long any of this is kept (section 11).

### 4. Permissions and platform components

**Photos and videos.** The app asks for access only after you tap "Allow access and scan" on an explanation screen, never at launch. If you allow only some photos (Limited access on iPhone, Selected photos on Android 14+), the app works on those photos and lets you change the selection later. Nothing is deleted silently: every decision goes to an in-app trash first, and your phone shows its own confirmation before any deletion. Albums you protect are never suggested; on iPhone, favorites are never suggested either.

**Notifications.** Optional. The app offers the weekly reminder once, after your first successful clean-up, and you can turn it on or off in Settings. Reminders are scheduled on the phone; there is no push server.

**Android: Google ML Kit.** On Android the app uses Google's ML Kit (bundled) for text recognition and face detection. The recognition runs on your phone; the photo and the text are not sent anywhere. Google documents that the ML Kit SDK collects technical diagnostics "for diagnostics and usage analytics": device information (manufacturer, model, OS version and build), app information (package name and version), performance metrics such as latency, API configuration such as image format and resolution, input and output size, feature version, event types and error codes. In this app we have switched off the parts of ML Kit that upload these events directly from the app. What remains is handed to Google Play services on your phone, which may send it to Google. It does **not** include the image, the text found in it, any face data, or your searches. Coditive does not receive this data and cannot see it. Google states that it encrypts the data in transit and does not transfer it to third parties (<https://developers.google.com/ml-kit/android-data-disclosure>). On Google Play we declare it as "App info and performance: Diagnostics", collected, not shared, for analytics. There is no switch for it in the app; only the text detection for greeting cards and the face analysis behind the best-shot suggestion and its reasons use these two ML Kit features.

**iPhone: Vision and Photos.** Text recognition and face analysis use Apple's Vision framework on the device. The app reads the library through Apple's Photos framework and never downloads iCloud-only originals. If iCloud Photos is on, deleting a photo also removes it from iCloud and your other devices; that is Apple's sync of your own action, and the app tells you before your first deletion. Deleted photos stay in Recently Deleted for about 30 days. The App Store privacy label is **Data Not Collected**.

### 5. What uses the network

- **Purchases.** Plus can be bought as a yearly subscription or a lifetime purchase through Google Play or the Apple App Store. The store handles payment and shows you the price; we never see your card or payment details. The app keeps the purchase status on your phone and re-checks it with the store when the last check is more than a day old (on iPhone, only if you have Plus or your yearly Plus ended in the last 30 days). Restore purchases asks the store again. We run no purchase server.
- <!-- MODEL-HOST --> **The search model (one download).** The app uses an image–text model that runs on your device. Searching in your own words needs its text part, which is optional (about 45 MB, plus a 2 MB tokenizer file): if you use Plus and type your first search, the app offers to download it once and downloads it only after you confirm. It comes from our public file release on GitHub (github.com, delivered from githubusercontent.com), at a fixed version, and the app checks its SHA-256 fingerprint before use. The request contains no personal data, only the file name: no account, no identifier from us, nothing from your gallery and none of the words you typed. GitHub sees your IP address like any web request. You can remove the model in Settings.
- **Links.** Links you tap (support, privacy policy, terms, our other apps, managing your subscription) open in your browser or in the store, outside the app. The licenses page is part of the app and needs no network.
- **Nothing else.** No analytics, no advertising, no tracking, no update pings of our own. Everything else works offline.
- **This website.** It uses no cookies, no analytics and no external scripts. It is hosted on GitHub Pages (section 9).

### 6. What we do not do

We have not added any analytics, advertising, tracking or crash-reporting service of our own. There is no account and no advertising identifier. We do not sell or share personal data, do not build profiles, and do not send images or text to any cloud vision or OCR service.

### 7. Sharing your result

The gallery report and the "I freed …" cards are images drawn on your phone. They contain no photos from your gallery. If you share one, it goes where you send it through your phone's share sheet.

### 8. Children

The app is meant for adults, including adults tidying a parent's phone. It is not directed at children, and we do not knowingly process personal data of children.

### 9. Data processed when you contact us or visit this site

Outside the app, as the controller, we process a small amount of personal data:

- **E-mails to kasim@mitrabilisim.com.tr:** your e-mail address, your name if you give it, your message and any attachment you send, such as a screenshot. Purpose: to answer you and handle your request. Legal basis: performance of a contract where the message concerns your use or purchase of the app (GDPR Art. 6(1)(b); KVKK Art. 5(2)(c)); otherwise our legitimate interest in answering enquiries (Art. 6(1)(f); KVKK Art. 5(2)(f)). Retention: we keep a conversation as long as we need it to answer you and delete it 2 years after its last message. Recipient: our e-mail provider, as processor.
- **Website visits:** this site is hosted on GitHub Pages by GitHub, Inc. (USA). When you visit it, GitHub may log your IP address for security purposes; see GitHub's privacy statement (<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>). Transfers to the USA rely on the EU–US Data Privacy Framework. We do not control those logs and do not receive them. The site uses no cookies, no analytics and no external scripts.
- **Store sales reports:** Apple and Google handle all payments. We never receive your card or payment details and we hold no payment records. Apple and Google show us sales reports in our developer accounts (product, country, date and amounts; Google's reports also show the order number and the buyer's state and postal code). We use them only to follow our sales and to answer your support questions about a purchase. Legal basis: legitimate interest (Art. 6(1)(f); KVKK Art. 5(2)(f)). Apple and Google are the sources of this data and independent controllers for their own store data.

**International transfers.** If a provider processes this data outside the EU/EEA, the transfer rests on an EU adequacy decision (such as the EU–US Data Privacy Framework) or the EU standard contractual clauses (GDPR Art. 13(1)(f) and Chapter V). If you are in Türkiye, personal data transferred abroad is subject to Article 9 of the KVKK. Apple and Google handle their own store data under their own policies.

We do not sell this data and do not use it for advertising.

### 10. Your rights

For the data in section 9 you have, under the GDPR, the right of access (Art. 15), rectification (Art. 16), erasure (Art. 17), restriction of processing (Art. 18), to have recipients told about such changes (Art. 19), data portability (Art. 20) and objection to processing that rests on our legitimate interest (Art. 21). We take no decisions about you by automated means. Write to kasim@mitrabilisim.com.tr; we answer within one month. The data on your phone is under your control (section 11). For the Google diagnostics on Android, Google is an independent controller: see Google's privacy policy.

You can complain to your local data-protection authority, for example the NAIH in Hungary (naih.hu) or the Personal Data Protection Board (KVKK, kvkk.gov.tr) in Türkiye. If you are in Türkiye, your rights are also set out in Article 11 of Law No. 6698 (KVKK).

<a id="data-deletion"></a>

### 11. Data deletion

Everything the app stores stays on your phone until you remove it; we cannot see it or delete it for you. Uninstalling the app deletes all of it. Settings → "Reset scan data" deletes the analysis, your decisions and the trash list without uninstalling; it does not touch your photos, and your settings, Plus status, protected albums, saved filters, clean-up history and the downloaded search model stay. You can remove the downloaded search model in Settings → "Smart filter model". For the data in section 9, write to kasim@mitrabilisim.com.tr and we delete it. Deletion requests for Google's ML Kit diagnostics go to Google.

### 12. Changes and contact

If this policy changes we will publish the new version on this page with a new effective date, and tell you in the app when we can. Questions: kasim@mitrabilisim.com.tr (Coditive).

---

<h2 id="tr">Gizlilik Politikası (Türkçe)</h2>

**Yürürlük tarihi: 9 Ekim 2026**

### 1. Kısa özet

- Fotoğrafların, görsel vektörlerin, okunan yazılar ve aramaların telefondan çıkmaz.
- Hesap yok. Reklam yok. Takip yok.
- İnternet yalnızca mağaza satın alımları ve arama modelinin bir kez indirilmesi için kullanılır.
- Android'de Google'ın yazı ve yüz tanıma bileşeni (ML Kit), Google Play hizmetlerine anonim performans tanılamaları iletebilir. Bunlara fotoğraflarının, içlerinde bulunan yazıların ya da aramalarının içeriği dahil değildir. Ayrıntı 4. bölümde.
- Bize yazarsan ya da bu web sitesini ziyaret edersen bunun için az miktarda veri işlenir (9. bölüm).

### 2. Biz kimiz

HangisiKalsın (diğer dillerde WhichToKeep), **Coditive** tarafından yayımlanır. Gizlilik soruları için: **kasim@mitrabilisim.com.tr**.

Uygulamanın kendisi bize hiçbir şey göndermez: Coditive'in, fotoğraflarını, analiz sonuçlarını ya da kararlarını uygulamadan alan bir sunucusu yoktur. Uygulamanın dışında, bize ulaştığında ya da bu web sitesini ziyaret ettiğinde az miktarda veri işlenir; 9. bölümde listelenmiştir.

### 3. Cihazında kalanlar

Uygulama, iznin ile, kütüphanendeki fotoğraf ve videolara bakarak kopyaları, benzer kareleri, ekran görüntülerini, bulanık fotoğrafları, büyük videoları ve senin anlattıklarını bulur. Bunun için telefonundaki uygulamaya özel alanda şunları tutar:

- dosya bilgileri: boyut, tarih, çözünürlük, klasör ya da albüm, favori işareti ve analiz ile gösterim için küçük resimler;
- analiz sonuçları: kopyalar için görsel parmak izleri, netlik ve parlaklık sayıları ve <!-- MODEL-HOST --> cihazında çalışan bir görsel–metin modelinin ürettiği görsel vektörü (görselde ne olduğunu anlatan bir sayı listesi);
- yüz içeren fotoğraflar için dört değer: kaç yüz olduğu, yüz kalite puanı, gözlerin açık olup olmadığı ve kişinin gülüp gülmediği. Bunlar benzer fotoğraflar arasında önerilen en iyi kareyi seçmek ve düellodaki gerekçeleri ("gözler açık", "gülüyor") göstermek için kullanılır. Uygulama kimseyi tanımaz ve yüz şablonu saklamaz;
- tebrik kartına benzeyen görsellerde tebrik ifadelerini yakalamak için yazı okunur. Yazı yalnızca kontrol edilirken bellekte tutulur, **saklanmaz ve günlüğe yazılmaz**; kalan tek şey hangi tür tebrik ifadesinin eşleştiğidir (cuma, bayram ya da günaydın). Bu sürüm kimlik, banka kartı ya da benzeri hassas belgeleri aramaz;
- kararların (sakla, çöp, emin değilim), uygulamanın çöp listesi, koruduğun albümler, kayıtlı filtrelerin (yazdığın kelimeler dahil) ve ayarların.

Bunların hiçbiri yüklenmez. Analiz, telefon şarjdayken ve telefon izin verdiğinde arka planda sürebilir; cihazda çalışır ve Ayarlar'dan kapatabilirsin. Android'de uygulamanın verisi bulut yedeğine ve cihazdan cihaza aktarıma dahil edilmez. iPhone'da uygulamanın veritabanı (analiz, görsel vektörleri, kararlar ve kayıtlı filtreler), boyut önbelleği ve indirilen arama modeli iCloud Yedekleme'ye dahil edilmez; dil, tema ve mod gibi küçük uygulama ayarları kendi iCloud yedeğinde yer alabilir. Bunların ne kadar tutulacağına sen karar verirsin (11. bölüm).

### 4. İzinler ve platform bileşenleri

**Fotoğraflar ve videolar.** Uygulama erişimi yalnızca bir açıklama ekranında "İzin ver ve tara"ya dokunduktan sonra ister, açılışta asla. Yalnızca bazı fotoğraflara izin verirsen (iPhone'da Sınırlı erişim, Android 14+'ta Seçili fotoğraflar) uygulama o fotoğraflarla çalışır ve seçimi sonradan değiştirmene izin verir. Hiçbir şey sessizce silinmez: her karar önce uygulama içi çöp sepetine gider ve silmeden önce telefonun kendi onay penceresi çıkar. Koruduğun albümler asla önerilmez; iPhone'da favoriler de asla önerilmez.

**Bildirimler.** İsteğe bağlı. Uygulama haftalık hatırlatmayı ilk başarılı temizliğinden sonra bir kez önerir; Ayarlar'dan istediğin zaman açıp kapatabilirsin. Hatırlatmalar telefonda zamanlanır; push sunucusu yoktur.

**Android: Google ML Kit.** Android'de uygulama, yazı tanıma ve yüz algılama için Google'ın ML Kit bileşenini (uygulamaya gömülü) kullanır. Tanıma telefonunda çalışır; fotoğraf ve yazı hiçbir yere gönderilmez. Google, ML Kit SDK'sının "tanılama ve kullanım analitiği" için teknik tanılamalar topladığını belirtir: cihaz bilgisi (üretici, model, işletim sistemi sürümü ve derlemesi), uygulama bilgisi (paket adı ve sürüm), gecikme gibi performans ölçümleri, görüntü biçimi ve çözünürlüğü gibi API yapılandırması, girdi ve çıktı boyutu, özellik sürümü, olay türleri ve hata kodları. Bu uygulamada, ML Kit'in bu olayları doğrudan uygulamadan yükleyen kısımlarını kapattık. Geriye kalan, telefonundaki Google Play hizmetlerine verilir ve Google Play hizmetleri bunu Google'a iletebilir. Görüntünün kendisi, içindeki yazı, yüz verisi ya da aramaların **dahil değildir**. Coditive bu veriyi almaz ve göremez. Google, veriyi iletim sırasında şifrelediğini ve üçüncü taraflara aktarmadığını belirtir (<https://developers.google.com/ml-kit/android-data-disclosure>). Google Play'de bunu "Uygulama bilgisi ve performansı: Tanılama", toplanan, paylaşılmayan, analitik amaçlı olarak beyan ediyoruz. Uygulamada bunu kapatan bir anahtar yoktur; bu iki ML Kit özelliğini yalnızca tebrik kartları için yazı tespiti ile en iyi kare önerisinin ve gerekçelerinin arkasındaki yüz analizi kullanır.

**iPhone: Vision ve Fotoğraflar.** Yazı tanıma ve yüz analizi, cihazda Apple'ın Vision çerçevesiyle yapılır. Uygulama kütüphaneyi Apple'ın Fotoğraflar çerçevesiyle okur ve iCloud'da duran, cihazda olmayan orijinalleri asla indirmez. iCloud Fotoğrafları açıksa bir fotoğrafı silmek onu iCloud'dan ve diğer cihazlarından da siler; bu, kendi eyleminin Apple tarafından eşitlenmesidir ve uygulama ilk silmeden önce bunu söyler. Silinen fotoğraflar yaklaşık 30 gün Son Silinenler'de kalır. App Store gizlilik etiketi **Veri Toplanmıyor**'dur.

### 5. İnterneti ne kullanır

- **Satın alımlar.** Plus, Google Play ya da Apple App Store üzerinden yıllık abonelik ya da ömür boyu olarak alınabilir. Ödemeyi mağaza yürütür ve fiyatı sana gösterir; kart ya da ödeme bilgilerini asla görmeyiz. Uygulama satın alma durumunu telefonunda tutar ve son kontrol bir günden eskiyse mağazayla yeniden kontrol eder (iPhone'da yalnızca Plus'ın varsa ya da yıllık Plus'ın son 30 günde sona erdiyse). Satın alımları geri yükle, mağazaya yeniden sorar. Satın alma sunucusu işletmeyiz.
- <!-- MODEL-HOST --> **Arama modeli (tek indirme).** Uygulama, cihazında çalışan bir görsel–metin modeli kullanır. Kendi kelimelerinle aramak için bu modelin isteğe bağlı metin kısmı gerekir (yaklaşık 45 MB, artı 2 MB'lık bir sözcük dosyası): Plus kullanıyorsan ve ilk aramanı yazarsan uygulama onu bir kez indirmeyi önerir ve yalnızca sen onaylarsan indirir. Dosya, GitHub'daki herkese açık dosya sürümümüzden (github.com, githubusercontent.com üzerinden) sabit bir sürümden gelir; uygulama kullanmadan önce SHA-256 parmak izini kontrol eder. İstekte kişisel veri yoktur, yalnızca dosya adı vardır: hesap, bizden bir tanımlayıcı, galerinden hiçbir şey ve yazdığın kelimeler yoktur. GitHub, her web isteğinde olduğu gibi IP adresini görür. Modeli Ayarlar'dan kaldırabilirsin.
- **Bağlantılar.** Dokunduğun bağlantılar (destek, gizlilik politikası, kullanım şartları, diğer uygulamalarımız, aboneliğini yönetme) uygulamanın dışında, tarayıcında ya da mağazada açılır. Lisanslar sayfası uygulamanın içindedir ve internet gerektirmez.
- **Başka hiçbir şey.** Analitik yok, reklam yok, takip yok, kendi güncelleme bildirimlerimiz yok. Geri kalan her şey çevrimdışı çalışır.
- **Bu web sitesi.** Çerez, analitik ve harici betik kullanmaz. GitHub Pages üzerinde barındırılır (9. bölüm).

### 6. Yapmadıklarımız

Kendi analitik, reklam, takip ya da çökme raporlama hizmetimizi eklemedik. Hesap ve reklam kimliği yok. Kişisel veri satmayız ya da paylaşmayız, profil çıkarmayız, görsel ya da yazıyı hiçbir bulut görüntü ya da OCR hizmetine göndermeyiz.

### 7. Sonucunu paylaşmak

Galeri karnesi ve "… açtım" kartları telefonunda çizilen görsellerdir. Galerinden hiçbir fotoğraf içermez. Paylaşırsan telefonunun paylaşım menüsüyle seçtiğin yere gider.

### 8. Çocuklar

Uygulama, anne ya da babasının telefonunu toplayan yetişkinler dahil yetişkinler içindir. Çocuklara yönelik değildir ve bilerek çocukların kişisel verilerini işlemeyiz.

### 9. Bize yazdığında ya da siteyi ziyaret ettiğinde işlenen veriler

Uygulamanın dışında, veri sorumlusu olarak az miktarda kişisel veri işleriz:

- **kasim@mitrabilisim.com.tr adresine gelen e-postalar:** e-posta adresin, verirsen adın, mesajın ve eklediğin dosyalar (örneğin ekran görüntüsü). Amaç: sana yanıt vermek ve talebini yürütmek. Hukuki sebep: mesaj uygulamayı kullanmana ya da satın almana ilişkinse sözleşmenin ifası (GDPR m. 6/1-b); aksi hâlde soruları yanıtlamaktaki meşru menfaatimiz (m. 6/1-f). KVKK bakımından: mesaj sözleşmeyle ilgiliyse m. 5/2-c, aksi hâlde meşru menfaat (m. 5/2-f). Saklama: yazışmayı sana yanıt vermek için gerektiği sürece tutarız ve son mesajdan 2 yıl sonra sileriz. Alıcı: veri işleyen olarak e-posta sağlayıcımız.
- **Web sitesi ziyaretleri:** bu site GitHub, Inc. (ABD) tarafından GitHub Pages üzerinde barındırılır. Siteyi ziyaret ettiğinde GitHub, güvenlik amacıyla IP adresini kaydedebilir; GitHub'ın gizlilik bildirimine bakabilirsin (<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>). ABD'ye aktarım AB–ABD Veri Gizliliği Çerçevesi'ne (EU–US Data Privacy Framework) dayanır. Bu kayıtları biz denetlemeyiz ve bize iletilmez. Site çerez, analitik ve harici betik kullanmaz.
- **Mağaza satış raporları:** tüm ödemeleri Apple ve Google yürütür. Kart ya da ödeme bilgilerini hiçbir zaman almayız ve ödeme kaydı tutmayız. Apple ve Google, geliştirici hesaplarımızda bize satış raporları gösterir (ürün, ülke, tarih ve tutarlar; Google'ın raporlarında ayrıca sipariş numarası ile alıcının eyaleti/ili ve posta kodu). Bunları yalnızca satışlarımızı izlemek ve bir satın almayla ilgili destek sorularını yanıtlamak için kullanırız. Hukuki sebep: meşru menfaat (m. 6/1-f; KVKK m. 5/2-f). Apple ve Google bu verinin kaynağıdır ve kendi mağaza verileri için bağımsız veri sorumlularıdır.

**Yurt dışına aktarım.** Bir hizmet sağlayıcı bu veriyi AB/AEA dışında işliyorsa aktarım bir AB yeterlilik kararına (örneğin AB–ABD Veri Gizliliği Çerçevesi) ya da AB standart sözleşme hükümlerine dayanır (GDPR m. 13/1-f ve Bölüm V). Türkiye'deysen, yurt dışına aktarılan kişisel veriler KVKK'nın 9. maddesine tabidir. Apple ve Google kendi mağaza verilerini kendi politikalarına göre işler.

Bu veriyi satmayız ve reklam için kullanmayız.

### 10. Hakların

9. bölümdeki veriler için GDPR kapsamında erişim (m. 15), düzeltme (m. 16), silme (m. 17), işlemenin kısıtlanması (m. 18), bu değişikliklerin alıcılara bildirilmesi (m. 19), veri taşınabilirliği (m. 20) ve meşru menfaatimize dayanan işlemeye itiraz (m. 21) haklarına sahipsin. Hakkında otomatik yollarla karar vermeyiz. kasim@mitrabilisim.com.tr adresine yaz; bir ay içinde yanıtlarız. Cihazındaki veri senin denetimindedir (11. bölüm). Android'deki Google tanılamaları için Google bağımsız veri sorumlusudur: Google'ın gizlilik politikasına bakabilirsin.

Bulunduğun yerdeki veri koruma otoritesine şikâyette bulunabilirsin; örneğin Türkiye'de Kişisel Verileri Koruma Kurulu'na (KVKK, kvkk.gov.tr), Macaristan'da NAIH'e (naih.hu). Türkiye'deysen hakların ayrıca 6698 sayılı KVKK'nın 11. maddesinde düzenlenmiştir.

<a id="data-deletion-tr"></a>

### 11. Veri silme

Uygulamanın sakladığı her şey, sen kaldırana kadar telefonunda kalır; biz göremeyiz ve senin yerine silemeyiz. Uygulamayı kaldırmak hepsini siler. Ayarlar → "Tarama verisini sıfırla" uygulamayı kaldırmadan analizi, kararlarını ve çöp listesini siler; fotoğraflarına dokunmaz; ayarların, Plus durumun, korunan albümlerin, kayıtlı filtrelerin, temizlik geçmişin ve indirilen arama modeli kalır. İndirilen arama modelini Ayarlar → "Akıllı filtre modeli"nden kaldırabilirsin. 9. bölümdeki veriler için kasim@mitrabilisim.com.tr adresine yaz; sileriz. Google'ın ML Kit tanılamalarına ilişkin silme talepleri Google'a yapılır.

### 12. Değişiklikler ve iletişim

Bu politika değişirse yeni sürümü yeni bir yürürlük tarihiyle bu sayfada yayımlarız ve mümkün olduğunda uygulama içinden de haber veririz. Sorular: kasim@mitrabilisim.com.tr (Coditive).

---

<h2 id="hu">Adatvédelmi tájékoztató (Magyar)</h2>

**Hatályos: 2026. október 9-től**

### 1. Röviden

- A fotóid, a képvektorok, a felismert szövegek és a kereséseid nem hagyják el a telefonod.
- Nincs fiók. Nincs reklám. Nincs nyomkövetés.
- A hálózatot csak áruházi vásárlásokra és a keresőmodell egyszeri letöltésére használja az alkalmazás.
- Androidon a Google szöveg- és arcfelismerő összetevője (ML Kit) névtelen teljesítménydiagnosztikát küldhet a Google Play szolgáltatásoknak. Ebben soha nincs benne a fotóid, a bennük talált szöveg vagy a kereséseid tartalma. A részleteket a 4. pont írja le.
- Ha írsz nekünk, vagy meglátogatod ezt a weboldalt, ehhez kevés adat kezelése történik (9. pont).

### 2. Kik vagyunk

A WhichToKeep (törökül HangisiKalsın) kiadója a **Coditive**. Adatvédelmi kérdésekben: **kasim@mitrabilisim.com.tr**.

Maga az alkalmazás semmit nem küld nekünk: a Coditive-nak nincs olyan szervere, amely az alkalmazásból megkapná a fotóidat, az elemzési eredményeket vagy a döntéseidet. Az alkalmazáson kívül kevés adat kezelése történik, ha kapcsolatba lépsz velünk vagy meglátogatod ezt a weboldalt; ezeket a 9. pont sorolja fel.

### 3. Ami a készülékeden marad

Az alkalmazás az engedélyeddel átnézi a könyvtáradban lévő fotókat és videókat, hogy megtalálja a másolatokat, a hasonló képeket, a képernyőképeket, a homályos fotókat, a nagy videókat és azt, amit te leírsz. Ehhez a telefonod alkalmazás-magánterületén ezeket tárolja:

- fájladatok: méret, dátum, felbontás, mappa vagy album, kedvenc jelölés, valamint az elemzéshez és a megjelenítéshez használt kis bélyegképek;
- elemzési eredmények: képujjlenyomatok a másolatokhoz, élesség- és fényerőszámok, valamint <!-- MODEL-HOST --> egy képvektor (számok listája, amely leírja, mi van a képen), amelyet egy, a készülékeden futó kép–szöveg modell állít elő;
- arcot tartalmazó fotóknál négy érték: hány arc van a képen, egy arcminőségi pontszám, nyitva vannak-e a szemek, és mosolyog-e a személy. Ezekkel javasoljuk a legjobb képet a hasonló fotók közül, és ezekből jönnek a párbaj indoklásai („nyitott szemek”, „mosolyog”). Az alkalmazás senkit nem azonosít, és nem tárol arcsablont;
- az üdvözlőkártyához hasonló képeken szöveget olvas az üdvözlő fordulatok felismeréséhez. A szöveg csak az ellenőrzés idejére van a memóriában, **nem kerül tárolásra vagy naplózásra**; csak az marad meg, hogy melyik fajta üdvözlő fordulat egyezett (péntek, ünnep vagy jó reggelt). Ez a verzió nem keres személyi igazolványt, bankkártyát vagy más érzékeny dokumentumot;
- a döntéseid (marad, kuka, nem biztos), az alkalmazás kukalistája, a védett albumaid, a mentett szűrőid (a beírt szavakkal együtt) és a beállításaid.

Ebből semmi nem töltődik fel. Az elemzés folytatódhat a háttérben is, amíg a telefon töltődik és amikor a telefon engedi; az eszközön fut, és a Beállításokban kikapcsolhatod. Androidon az alkalmazás adatai nem kerülnek felhőmentésbe és készülékek közötti átvitelbe. iPhone-on az alkalmazás adatbázisa (elemzés, képvektorok, döntések és mentett szűrők), a méret-gyorsítótára és a letöltött keresőmodell nem kerül az iCloud-mentésbe; a kisebb alkalmazásbeállítások, például a nyelv, a téma és a mód, a saját iCloud-mentésed részei lehetnek. Te döntöd el, meddig maradnak meg (11. pont).

### 4. Engedélyek és platformösszetevők

**Fotók és videók.** Az alkalmazás csak azután kér hozzáférést, hogy egy magyarázó képernyőn a „Hozzáférés engedélyezése és átvizsgálás” gombra koppintasz, indításkor soha. Ha csak néhány fotót engedélyezel (iPhone-on korlátozott hozzáférés, Android 14-től kiválasztott fotók), az alkalmazás ezekkel dolgozik, és később módosíthatod a kijelölést. Semmi sem törlődik csendben: minden döntés először az alkalmazáson belüli kukába kerül, és törlés előtt a telefon saját megerősítő ablaka jelenik meg. A védett albumokat soha nem javasoljuk; iPhone-on a kedvenceket sem.

**Értesítések.** Nem kötelező. A heti emlékeztetőt az alkalmazás az első sikeres takarítás után egyszer felajánlja, és a Beállításokban bármikor be- vagy kikapcsolhatod. Az emlékeztetők a telefonon ütemeződnek; nincs push-szerver.

**Android: Google ML Kit.** Androidon az alkalmazás a Google ML Kit (beépített) összetevőjét használja szövegfelismeréshez és arcfelismeréshez. A felismerés a telefonodon fut; a fotó és a szöveg sehova sem kerül elküldésre. A Google közlése szerint az ML Kit SDK „diagnosztikai és használati elemzési” célból technikai diagnosztikát gyűjt: eszközadatok (gyártó, típus, operációs rendszer verziója és buildje), alkalmazásadatok (csomagnév és verzió), teljesítménymutatók, például késleltetés, API-konfiguráció, például képformátum és felbontás, bemeneti és kimeneti méret, funkcióverzió, eseménytípusok és hibakódok. Ebben az alkalmazásban kikapcsoltuk az ML Kit azon részeit, amelyek ezeket az eseményeket közvetlenül az alkalmazásból töltik fel. Ami megmarad, azt a telefonodon lévő Google Play szolgáltatások kapják meg, amelyek továbbíthatják a Google-nek. **Nem** tartalmazza a képet, a benne talált szöveget, arcadatot vagy a kereséseidet. A Coditive nem kapja meg ezeket az adatokat, és nem látja őket. A Google közlése szerint az adatot titkosítva továbbítja, és nem adja tovább harmadik félnek (<https://developers.google.com/ml-kit/android-data-disclosure>). A Google Play-ben ezt „Alkalmazásinformáció és teljesítmény: Diagnosztika” néven jelentjük be: gyűjtött, nem megosztott, elemzési célú. Az alkalmazásban nincs kapcsoló ehhez; ezt a két ML Kit funkciót csak az üdvözlőkártyák szövegfelismerése, valamint a legjobb kép javaslata és indoklásai mögötti arcelemzés használja.

**iPhone: Vision és Fotók.** A szövegfelismerés és az arcelemzés az eszközön, az Apple Vision keretrendszerével történik. Az alkalmazás az Apple Fotók keretrendszerén keresztül olvassa a könyvtárat, és az iCloudban lévő, az eszközön nem található eredetiket soha nem tölti le. Ha az iCloud-fotók be van kapcsolva, egy fotó törlése az iCloudból és a többi eszközödről is eltávolítja; ez a saját műveleted Apple általi szinkronizálása, és az alkalmazás az első törlés előtt szól erről. A törölt fotók nagyjából 30 napig a Nemrég törölt albumban maradnak. Az App Store adatvédelmi címkéje: **Adatot nem gyűjt**.

### 5. Mi használja a hálózatot

- **Vásárlások.** A Plus éves előfizetésként vagy örökös licencként vásárolható meg a Google Play-en vagy az Apple App Store-on keresztül. A fizetést az áruház kezeli és mutatja meg az árat; a kártyád vagy fizetési adataid sosem jutnak el hozzánk. Az alkalmazás a vásárlás állapotát a telefonodon tárolja, és akkor ellenőrzi újra az áruházban, ha az utolsó ellenőrzés több mint egy napos (iPhone-on csak akkor, ha van Plusod, vagy az éves Plusod az elmúlt 30 napban járt le). A vásárlások visszaállítása újra az áruházat kérdezi. Nem működtetünk vásárlási szervert.
- <!-- MODEL-HOST --> **A keresőmodell (egyszeri letöltés).** Az alkalmazás egy, a készülékeden futó kép–szöveg modellt használ. A saját szavaiddal való kereséshez ennek a nem kötelező szöveges része kell (kb. 45 MB, plusz egy 2 MB-os szótárfájl): ha Plus-előfizető vagy, és beírod az első keresésed, az alkalmazás felajánlja, hogy egyszer letölti, és csak a jóváhagyásod után tölti le. A fájl a GitHubon lévő nyilvános kiadásunkból érkezik (github.com, a githubusercontent.com-ról kézbesítve), rögzített verzióból, és az alkalmazás használat előtt ellenőrzi a SHA-256 ujjlenyomatát. A kérés nem tartalmaz személyes adatot, csak a fájl nevét: nincs benne fiók, tőlünk származó azonosító, semmi a galériádból és egyik beírt szavad sem. A GitHub, mint minden webes kérésnél, látja az IP-címedet. A modellt a Beállításokban eltávolíthatod.
- **Hivatkozások.** A megérintett hivatkozások (támogatás, adatvédelmi tájékoztató, felhasználási feltételek, további alkalmazásaink, az előfizetés kezelése) az alkalmazáson kívül, a böngészőben vagy az áruházban nyílnak meg. A licencek oldala az alkalmazás része, és nem kell hozzá hálózat.
- **Semmi más.** Nincs analitika, nincs reklám, nincs nyomkövetés, nincsenek saját frissítési jelzéseink. Minden más kapcsolat nélkül is működik.
- **Ez a weboldal.** Nem használ sütiket, analitikát és külső szkripteket. A GitHub Pages szolgáltatáson fut (9. pont).

### 6. Amit nem csinálunk

Nem építettünk be saját analitikai, reklám-, nyomkövető vagy összeomlás-jelentő szolgáltatást. Nincs fiók és nincs hirdetési azonosító. Személyes adatot nem adunk el és nem osztunk meg, profilt nem építünk, és képet vagy szöveget nem küldünk felhőalapú képfelismerő vagy OCR szolgáltatásnak.

### 7. Az eredményed megosztása

A galéria-bizonyítvány és a „felszabadítottam …” kártyák a telefonodon megrajzolt képek. Nem tartalmaznak fotót a galériádból. Ha megosztod, oda kerül, ahová a telefonod megosztás menüjében küldöd.

### 8. Gyermekek

Az alkalmazás felnőtteknek szól, beleértve azokat is, akik a szülők telefonját rendezik. Nem gyermekeknek készült, és tudatosan nem kezelünk gyermekek személyes adatait.

### 9. Az adatok, amelyeket akkor kezelünk, ha írsz nekünk vagy meglátogatod a weboldalt

Az alkalmazáson kívül, adatkezelőként kevés személyes adatot kezelünk:

- **A kasim@mitrabilisim.com.tr címre írt e-mailek:** az e-mail-címed, a neved, ha megadod, az üzeneted és a csatolt fájlok, például egy képernyőkép. Cél: hogy válaszoljunk, és kezeljük a kérésedet. Jogalap: szerződés teljesítése, ha az üzenet az alkalmazás használatával vagy megvásárlásával kapcsolatos (GDPR 6. cikk (1) b); török KVKK 5. cikk (2) c)); egyébként a megkeresések megválaszolásához fűződő jogos érdekünk (6. cikk (1) f); KVKK 5. cikk (2) f)). Megőrzés: a levelezést addig őrizzük, amíg a válaszadáshoz szükséges, és az utolsó üzenettől számított 2 év után töröljük. Címzett: az e-mail-szolgáltatónk, adatfeldolgozóként.
- **A weboldal látogatása:** ezt az oldalt a GitHub, Inc. (USA) GitHub Pages szolgáltatása tárolja. Látogatáskor a GitHub biztonsági célból naplózhatja az IP-címedet; lásd a GitHub adatvédelmi nyilatkozatát (<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>). Az USA-ba történő adattovábbítás az EU–USA adatvédelmi keretrendszeren (EU–US Data Privacy Framework) alapul. Ezeket a naplókat nem mi kezeljük, és nem kapjuk meg őket. Az oldal nem használ sütiket, analitikát és külső szkripteket.
- **Áruházi értékesítési jelentések:** minden fizetést az Apple és a Google kezel. A kártyád vagy fizetési adataid soha nem jutnak el hozzánk, és fizetési nyilvántartást nem vezetünk. Az Apple és a Google a fejlesztői fiókjainkban értékesítési jelentéseket mutat (termék, ország, dátum és összegek; a Google jelentései ezenkívül a rendelésszámot, valamint a vásárló államát/megyéjét és irányítószámát is). Ezeket csak az értékesítéseink követésére és a vásárlással kapcsolatos támogatási kérdéseid megválaszolására használjuk. Jogalap: jogos érdek (6. cikk (1) f); KVKK 5. cikk (2) f)). Az Apple és a Google ezen adatok forrása, és a saját áruházi adataikért önálló adatkezelők.

**Nemzetközi adattovábbítás.** Ha egy szolgáltató ezeket az adatokat az EU/EGT-n kívül kezeli, az adattovábbítás uniós megfelelőségi határozaton (például az EU–USA adatvédelmi keretrendszeren) vagy uniós általános szerződési feltételeken alapul (GDPR 13. cikk (1) f) és V. fejezet). Ha Törökországban élsz, a külföldre továbbított személyes adatokra a KVKK 9. cikke vonatkozik. Az Apple és a Google a saját áruházi adatait a saját szabályzatai szerint kezeli.

Ezeket az adatokat nem adjuk el, és nem használjuk reklámra.

### 10. Jogaid

A 9. pontban szereplő adatokra a GDPR alapján jogod van a hozzáféréshez (15. cikk), a helyesbítéshez (16. cikk), a törléshez (17. cikk), az adatkezelés korlátozásához (18. cikk), ahhoz, hogy a címzetteket értesítsük az ilyen változásokról (19. cikk), az adathordozhatósághoz (20. cikk), valamint a jogos érdekünkön alapuló adatkezelés elleni tiltakozáshoz (21. cikk). Rólad automatizált úton nem hozunk döntést. Írj a kasim@mitrabilisim.com.tr címre; egy hónapon belül válaszolunk. A készülékeden lévő adatok felett te rendelkezel (11. pont). Az Androidon a Google diagnosztikai adataiért a Google önálló adatkezelő: lásd a Google adatvédelmi tájékoztatóját.

Panaszt tehetsz a lakóhelyed szerinti adatvédelmi hatóságnál, például Magyarországon a NAIH-nál (Nemzeti Adatvédelmi és Információszabadság Hatóság, naih.hu), Törökországban a Személyes Adatok Védelmi Testületénél (Kişisel Verileri Koruma Kurulu, kvkk.gov.tr). Ha Törökországban élsz, a jogaidat a 6698. számú török adatvédelmi törvény (KVKK) 11. cikke is tartalmazza.

<a id="data-deletion-hu"></a>

### 11. Adattörlés

Minden, amit az alkalmazás tárol, a telefonodon marad, amíg el nem távolítod; mi nem látjuk, és nem tudjuk helyetted törölni. Az alkalmazás eltávolítása mindent töröl. A Beállítások → „Átvizsgálási adatok törlése” eltávolítás nélkül törli az elemzést, a döntéseidet és a kuka listáját; a fotóidhoz nem nyúl, a beállításaid, a Plus állapota, a védett albumok, a mentett szűrők, a takarítási előzmények és a letöltött keresőmodell megmaradnak. A letöltött keresőmodellt a Beállítások → „Okosszűrő-modell” alatt távolíthatod el. A 9. pontban szereplő adatokért írj a kasim@mitrabilisim.com.tr címre, és töröljük őket. A Google ML Kit diagnosztikájával kapcsolatos törlési kérelmeket a Google-nek kell címezni.

### 12. Változások és kapcsolat

Ha ez a tájékoztató módosul, az új változatot új hatálybalépési dátummal közzétesszük ezen az oldalon, és ha tudjuk, az alkalmazásban is jelezzük. Kérdések: kasim@mitrabilisim.com.tr (Coditive).
