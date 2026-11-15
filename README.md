# 🦎 3D Bukalemun Saklambaç

Birinci şahıs 3D saklambaç oyunu. Sen **arayan**sın; yapay zekâ bukalemunlar saklandıkları eşyanın rengine bürünüyor. Fenerini tut, gözünü dört aç, renk tonundaki küçük farkı yakala ve lazerle vur. Ama dikkat et: **boşa ateş edersen silahın kilitlenir!** Sahte bukalemunlar, mürekkep tüküren dikenliler ve her haritanın sonunda bekleyen **Kral Bukalemun** da var.

### ▶️ Hemen oyna: **https://process631.github.io/bukalemun-saklambac/**

Kurulum gerekmez. Oyun tek bir `index.html` dosyası ve internet olmadan da çalışır (Three.js içine gömülü).

![Ana menü](screenshots/title.png)

## 🆕 Yenilikler

- **4 yeni harita:** 🏛️ Gece Müzesi, 🧺 Pazar Yeri, ❄️ Buz Sarayı ve 🏗️ Şantiye Kulesi. Toplam **7 harita, 28 bölüm** var.
- **Kral Bukalemun:** Her haritanın 4. bölümü bir boss bölümü.
- **4 zorluk seviyesi:** Kolay, Normal, Zor ve Kâbus.
- **4 yeni bukalemun türü:** Sinsi, Dikenli, Prizma ve 🪤 Sahte.
- **Mermi baskısı:** Yedek şarjör sınırlı ve ıskaların puan/süre cezası var.
- **Yeni modlar:** ♾️ Sonsuz, ⏱️ Zaman Yarışı ve 📅 Günlük Meydan Okuma (tohumlu).
- **Aletler:** 🌡️ Termal gözlük, 📯 Sonar bombası ve 🎨 Boya bombası.
- **Yeni küreler:** 🛡️ Kalkan, 🐌 Ağır çekim ve 🎒 Alet şarjı.
- **Atölye ve ödüller:** 6 yeni atölye geliştirmesi, 11 silah kaplaması, 18 başarım ve yerel rekor tablosu.

## 📸 Ekran görüntüleri

| Gece Müzesi (karanlık, fener şart) | Pazar Yeri |
|---|---|
| ![Gece Müzesi](screenshots/map-museum.png) | ![Pazar Yeri](screenshots/map-market.png) |
| **Buz Sarayı (kaygan zemin)** | **Şantiye Kulesi (çok katlı)** |
| ![Buz Sarayı](screenshots/map-ice.png) | ![Şantiye Kulesi](screenshots/map-construction.png) |
| **🌡️ Termal gözlük** | **📯 Sonar bombası** |
| ![Termal](screenshots/thermal.png) | ![Sonar](screenshots/sonar.png) |
| **🎨 Boya bombası** | **👑 Kral Bukalemun** |
| ![Boya](screenshots/paint.png) | ![Kral](screenshots/king.png) |
| **🪤 Sahteler taramada kırmızı** | **🦑 Mürekkep saldırısı** |
| ![Sahte](screenshots/decoy-scan.png) | ![Mürekkep](screenshots/ink.png) |
| **♾️ Sonsuz mod** | **⏱️ Zaman yarışı ve başarım** |
| ![Sonsuz](screenshots/endless-wave4.png) | ![Zaman yarışı](screenshots/race-result.png) |
| **📅 Günlük meydan okuma** | **🏆 Rekor tablosu** |
| ![Günlük](screenshots/menu-daily.png) | ![Rekorlar](screenshots/leaderboard.png) |
| **🏅 Başarımlar** | **🎨 Silah kaplamaları** |
| ![Başarımlar](screenshots/achievements.png) | ![Kaplamalar](screenshots/skins.png) |
| **Renkli Malikane** | **Renk Taraması (Q)** |
| ![Kamuflaj](screenshots/gameplay-camo.png) | ![Tarama](screenshots/scan.png) |
| **Sera Bahçesi** | **Oyuncak Fabrikası** |
| ![Sera Bahçesi](screenshots/map-garden.png) | ![Oyuncak Fabrikası](screenshots/map-factory.png) |

Mobilde alet butonları ekranın alt ortasında:

![Mobil](screenshots/mobile-thermal.png)

## 🎮 Kontroller

| Bilgisayar | Mobil | Ne yapar |
|---|---|---|
| `W A S D` / ok tuşları | Sol joystick (ekranın sol yarısı) | Hareket |
| Fare | Ekranın sağ yarısında sürükle | Etrafa bakış |
| `Shift` | 🏃 butonu (aç/kapa) | Koşma (kondisyon harcar) |
| `Boşluk` | ⤒ butonu | Zıplama (eşyaların ve iskelelerin üstüne çıkabilirsin) |
| Sol tık / `F` | 🔫 butonu | Lazer |
| `Q` / sağ tık | `Q` butonu | Renk taraması |
| `R` | `R` butonu | Şarjörü doldur (yedek bataryadan) |
| **`1`** | 🌡️ butonu | **Termal gözlük** |
| **`2`** | 📯 butonu | **Sonar bombası fırlat** |
| **`3`** | 🎨 butonu | **Boya bombası fırlat** |
| `Esc` / `P` | ❚❚ butonu | Duraklat |
| Hazırlıkta `Boşluk` | Ekrana dokun | Hazırlık süresini hızlandır |
| Menüde `Enter` |  | Seçili modu başlat |

Fare kilitlenemiyorsa (ör. bir iframe içinde) basılı tutup sürükleyerek de bakabilirsin.

## 🗺️ Haritalar

| Harita | Özellik |
|---|---|
| 🏰 Renkli Malikane | Renkli odalar, halılar, kutular |
| 🌻 Sera Bahçesi | Çit labirenti, çiçek tarhları, gölet |
| 🧸 Oyuncak Fabrikası | Neon ışıklar, blok kalesi, konveyörler |
| 🏛️ **Gece Müzesi** | Zifiri karanlık ve sis, fener hayati. Galeriler, heykeller, vitrinler, dinozor iskeleti. **Lazer alarmına** basarsan -5 sn kaybedersin ve bukalemunlar yer değiştirir. |
| 🧺 **Pazar Yeri** | Gün ışığında çizgili tente altında tezgâhlar, asılı halılar, saat kulesi, varil ve kafe |
| ❄️ **Buz Sarayı** | Yarı saydam buz blokları, neon kristaller, iglolar, kardan adamlar, donmuş göl. **Zemin kaygan**, hızlı dönemezsin. |
| 🏗️ **Şantiye Kulesi** | Çok katlı iskeleler ve merdivenler. Bukalemunlar **duvara tırmanıp** üst katlarda saklanır. |

Her haritada 3 bölüm ve bir **👑 Kral Bukalemun** bölümü var. Bir haritayı bitirince sonraki açılır. Bölümler ilerledikçe süre kısalır, bukalemun ve sahte sayısı artar, özel türler çoğalır.

## 🎮 Modlar

- **🗺️ Kampanya:** 28 bölüm. Her bölüm 3 yıldız üzerinden değerlendirilir (kazan, sürenin %40'ı kalsın, %70 isabet).
- **♾️ Sonsuz Hayatta Kalma:** Dalga dalga bukalemun gelir. Her yakalama +5 sn, her dalga +25 sn kazandırır. Her 3 dalgada harita değişir, her 5. dalgada Kral gelir. Süre biterse oyun biter; en iyi dalga ve skor kaydedilir.
- **⏱️ Zaman Yarışı:** Seçtiğin haritada 8 bukalemunu en kısa sürede yakalamaya çalışırsın. Süre ileri sayar, her ıska +5 sn ceza ekler. Rekor süreler harita başına tutulur.
- **📅 Günlük Meydan Okuma:** Tarihten üretilen tohumla herkes aynı haritada aynı bukalemunlara ve aynı saklanma yerlerine karşı oynar. 8 kuraldan 2'si rastgele seçilir: Zifiri Karanlık, Ürkek Sürü, Kısıtlı Batarya, Tuzak Cenneti, Kral Ziyareti, Altın Yağmuru, Cam Top, Tarama Arızası. Günün ilk tamamlanması +150 altın kazandırır.

## 💀 Zorluk

| | Kolay | Normal | Zor | Kâbus |
|---|---|---|---|---|
| Süre | x1.3 | x1 | x0.85 | x0.7 |
| Şarjör | +4 | ±0 | -2 | -4 |
| Yedek şarjör | sınırsız | 3 | 2 | 1 |
| Iska cezası | yok | -25 puan | -50 puan, -3 sn | -100 puan, -5 sn |
| Sahte bukalemun | yok | x1 | x1.5 | x2 |
| Bukalemun göçü (tur ortasında yer değiştirme) | yok | 1 kez (2. haritadan itibaren) | 2 kez | 2 kez |
| Puan / altın | x0.75 / x0.8 | x1 | x1.35 / x1.25 | x1.8 / x1.6 |

Zor ve Kâbus'ta bukalemunlar fenerden daha çabuk kaçar, kamuflajları daha kusursuz olur ve dikenliler daha sık saldırır. Kâbus'ta Kral 4 isabet ister.

## 🦎 Bukalemun Türleri

| Tür | Davranış |
|---|---|
| 🟠 Sıradan | 100 puan |
| 🔵 Kaçak | Yaklaşınca ya da fenerle üstüne tutunca hızla kaçar |
| 🟣 Usta | Şapkalı. Kamuflajı neredeyse kusursuz. |
| 🟢 **Sinsi** | Sen bakmazken sessizce yer değiştirir, kamuflajının bir kısmını korur |
| 🔴 **Dikenli** | Yakınına gelip fenerle uzun süre bakarsan şişer (💢) ve **mürekkep tükürür**: ekranın kararır, kısa süre sersemlersin. Kaçarak ya da kalkanla kurtulabilirsin. |
| 💗 **Prizma** | Rengini sürekli yeniden ayarlar. Taramada çok zayıf parlar. |
| 👑 **Kral Bukalemun** | 3 isabet ister (Kâbus'ta 4). Her isabette kaçar, 2 sahte kopya bırakır ve mürekkep tükürür. |
| 🪤 **Sahte** | Nefes almaz, göz kırpmaz ve taramada kırmızı görünür. Vurursan **-8 sn** ve puan kaybedersin. |

## 🎒 Aletler ve Küreler

- **🌡️ Termal gözlük (`1`):** Dünya soğuk mavi görünür, bukalemunlar parlak turuncu parlar, sahteler soğuk kalır. Süresi 4 sn (atölyeyle 7 sn).
- **📯 Sonar bombası (`2`):** Fırlatılır. Düştüğü yerin 14 m çevresindeki bukalemunları 6 sn boyunca mesafeleriyle işaretler, sahteleri "SAHTE" diye gösterir.
- **🎨 Boya bombası (`3`):** Fırlatılır. 7 m içindeki bukalemunları 12 sn boyunca pembeye boyar, sahteleri griye.
- Her bölümde her aletten 1 şarj gelir. Alet Çantası ve Kolay zorluk ek şarj verir. Sonsuz modda her iki dalgada bir şarj eklenir.
- **Güç küreleri:** ⚡ Hız · ⏱ +12 sn · 🔓 Yenileme · 📡 Radar · ❄️ Dondurucu · ✖2 Çift puan · 🔋 Yedek mermi · **🛡️ Kalkan** (bir mürekkebi engeller) · **🐌 Ağır çekim** (bukalemunlar yavaşlar) · **🎒 Alet şarjı**.

## 🏅 İlerleme

- **Atölye (14 geliştirme):** Geniş Şarjör, Soğutucu, Tarama Çipi, Uzun Tarama, Spor Ayakkabı, Güçlü Fener, Ekstra Süre, Şans Küresi. Yeni olanlar: **Yedek Batarya, Kombo Zinciri, Altın Mıknatısı, Mürekkep Gözlüğü, Alet Çantası, Termal Pil**.
- **🎨 Silah kaplamaları (11):** Klasik, Neon Pembe, Buz Kristali, Lav, Zümrüt (altınla alınır), Altın Kral, Gece Bekçisi, Kâbus, Galaksi, Bukalemun, Hanedan (başarımla açılır). Kaplama lazerin rengini de değiştirir; bazıları renk döngüsü yapar.
- **🏅 18 başarım:** Her biri altın verir, bazıları kaplama açar. Örnekler: Kral Avcısı, Hanedan Yıkıcı, Keskin Nişancı, Tuzağa Düşmeyen, Dalga Sörfçüsü, Şimşek, Boyacı.
- **🏆 Yerel rekor tablosu:** Kampanya, Sonsuz, Zaman Yarışı (harita başına) ve Günlük için ilk 10. Oyuncu adını Ayarlar'dan değiştirebilirsin.
- İlerlemenin tamamı tarayıcıda (`localStorage`) saklanır. Eski sürümdeki kayıtlar yeni bölüm düzenine otomatik taşınır.

## ✨ Temel özellikler

- **Akıllı kamuflaj:** Bukalemunlar etraflarına ışın atıp en yakın yüzeyin rengini okur ve yumuşak bir geçişle o renge bürünür. Kamuflajda hafif bir ton farkı kalır; nefes alır, göz kırparlar.
- **Yapay zekâ:** Izgara tabanlı A* yol bulma kullanılıyor. Dikey haritada tırmanarak yükseğe çıkabiliyorlar. Fenerde kalırlarsa ya da ıska yanlarından geçerse panikleyip kaçıyorlar.
- **Yönlü kıkırdamalar** (stereo) ve 🔥 sıcak/soğuk göstergesi.
- **Akıcı oynanış:** Yumuşatılmış bakış, ivmeli hareket, kafa sallanması, FOV efekti, geri tepme ve konfeti.
- **Ses:** Web Audio ile üretilir; hiçbir ses dosyası yok.

## ⚠️ Bilinen sınırlamalar

- Rekor tablosu ve günlük skorlar **yalnızca bu cihazda** tutulur. Çevrimiçi bir sıralama yok.
- Günlük meydan okuma, saklanma yerlerini aynı tohumdan üretir. Kaçan ya da göç eden bukalemunların sonraki yerleri oyuncunun hareketine göre değişebilir.
- Grafikler low-poly ve prosedürel. Çok eski telefonlarda "Düşük" kalite ayarı önerilir. Termal gözlük açıkken sahne iki kez çizildiği için çok zayıf cihazlarda kısa süre FPS düşebilir.
- Çarpışma kutuları silindirler ve küreler için yaklaşık hesaplanıyor.
- iOS Safari'de fare kilidi yok; dokunmatik kontroller kullanılıyor.

## 📦 Teknik

- Tek dosya: `index.html` (≈800 KB, Three.js r128 dahil, MIT lisanslı)
- Üçüncü taraf API ya da sunucu yok.
