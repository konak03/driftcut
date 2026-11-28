# Driftcut

> **Beta (0.x):** Driftcut henüz beta; sürümler ilk tam sürüme (1.0) kadar 0.1, 0.2… diye artar.

Kick, YouTube ve Twitch yayınlarından dikey **Shorts / Reels / TikTok** videoları hazırlayan Windows masaüstü editörü.

## İndir

**[Son sürümü indir](https://github.com/konak03/driftcut/releases/latest)**: sayfadaki `Driftcut-Kurulum-x.y.z.exe` dosyası.

- Windows 10 / 11, 64 bit.
- Kurulum dosyası imzasız olduğu için Windows ilk açılışta *"Windows kişisel bilgisayarınızı korudu"* diyebilir:
  **Ek bilgi** > **Yine de çalıştır**.
- Eski sürümün üstüne kurulur: projeler, ayarlar ve dışa aktarma klasörü yerinde kalır.

## Güncelleme

- Program açıkken yeni sürümü buradan kendisi denetler (10 dakikada bir) ve sorar: **Şimdi güncelle** dersen indirir,
  dosyanın bozulmadığını denetler, kurar ve kendini yeniden açar; "Sonraki açılışta" dersen bir sonraki açılışta kurulur.
- **1.x sürümlerinden biri kuruluysa** (1.7 ve öncesi): bir kez yukarıdaki bağlantıdan son sürümü indirip elle kur.
  O sürümler numarayı yazıyla karşılaştırdığı için 0.x'i "eski" sanar; elle kurduktan sonra güncellemeler kendiliğinden gelir.

## Neler var

- Yayın bağlantısından ya da bilgisayardaki videodan klip seçme, kesme, birleştirme; masaüstünden sürükle bırak
- Premiere mantığında zaman çizelgesi: böl, kısalt, imleçten öncesini / sonrasını sil (Q / W), araya ekle (Insert),
  Ctrl ile üzerine yaz (Overwrite), boşluğu kapat, geri al; kesimler kareye oturur; sürüklerken ayraç çizgisi ve
  önizlemede kenar karesi (kırpmada son kalan kare)
- Katman 1, Katman 2…: her medya her katmana; video üst katmana çıkınca sesi Katman 1 sesi şeridinde yerinde kalır (bağlı)
- Hazır kamera / oyun şablonları ya da serbest kare: Short üzerinde kırp, ölçekle, döndür, taşı; kamera kutusu
  kenarlarından ve köşelerinden boyutlanır, ortasından taşınır, Short'ta görünen kısmı elle kaydırılıp yakınlaştırılır
- **Efekt Denetimleri (Premiere gibi keyframe):** konum, ölçek, döndürme, bağlantı noktası, opaklık, parlaklık,
  kontrast, doygunluk, ses; kronometre, geçiş türleri, hazır animasyonlar. Kaynak görüntüye uygulanır: Short'un
  çerçevesi yerinde kalır, içindeki görüntü kayar (kamera + oyun düzeninde yalnız oyuna da); tutamaçlar yayın karesinde
- **Hareket takibi:** nesneyi ya da yüzü seç, kare kare izlensin (60 fps'te saniyede 60 nokta). Nesneyi OpenCV'nin yapay zekâ izleyicisi bulur
  (programın içinde, internet gerekmez): dönen, koşan, gölgeye giren karakterde ve yaklaşıp uzaklaşan araçta kutu
  nesnenin üstünde kalır, boyu nesneyle değişir; kaybolunca yanlış nesneye geçmez, geri gelince yeniden bulur,
  düzeltilebilir;
  **Kadrajı Takip Ettir** ile dikey kırpma nesneyi izler, yazı / çıkartma nesneye bağlanır
- **Yeşil perde (Keylight)**
- **Altyazı:** otomatik (kararlı, dili seçilir; NVIDIA ekran kartında hızlı), zaman çizelgesinde altyazı şeridi, elle
  satır, salise hassasiyeti, hazır stiller
- **Konuşma / oyun sesi ayırma (AI, ekran kartında)**: iki ayrı ses katmanı
- Ses klibinde hız, kesme, solma; her parçanın kendi ayar paneli; elle yazılan hız (0,25 - 4×)
- 15 görüntü efekti, geçişler (her kesimde), çok katmanlı yazı / fotoğraf / ses / efekt
- 1080×1920 MP4 dışa aktarma, kaydedileceği klasör seçilebilir; **Akıcı 60 fps**: görüntüsü 60 fps'ten az olan klipte
  (Kick'te 60 fps kapta 30 fps oyun görüntüsü dahil, kendiliğinden anlaşılır) ara kareler hareketten üretilir (üst katman videolarında da);
  ekran kartı varsa yapay zekâyla (RIFE, DirectX 12'li NVIDIA / AMD / Intel), 8 sn'lik klip ~9 sn'de
- **Pencereler (Premiere paneli gibi):** Medya, Önizleme, Kaynak kadrajı, Özellikler, Zaman çizelgesi; aradaki çizgiyle
  boyutlanır, başlığa çift tıkla büyür, gizlenir; Shift + 1…5 pencereye geçer. **Çalışma alanları** (Kurgu, Altyazı,
  Efekt ve renk, Ses, Odak + kendi kaydettiklerin), **kompakt kip** ve **ultra geniş (32:9) düzen**: önizleme
  yukarıdan aşağıya uzanır; boyutlar her ekran genişliği için ayrı saklanır
- **Sade ekran:** açıklamalar başlıktaki **?** işaretinde; Özellikler'de **Seçili öğe | Kamera düzeni** ayrımı;
  **Ara (Ctrl + F)**: komut, ayar ya da bölüm adını yaz, Enter oraya götürür ya da komutu çalıştırır
- Kişiselleştirme: renk temaları, arka plan resmi, arayüz ölçeği, kısayolları değiştirme, ayarları başka bilgisayara taşıma

## Sürümler

Değişiklikler her sürümün [sürüm notlarında](https://github.com/konak03/driftcut/releases).
