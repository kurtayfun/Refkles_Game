# ⚡ Refleks

Mobil dikey ekranlar için tasarlanmış, tek dosyalık bir HTML5 refleks/reaksiyon oyunu. Kurulum yok, derleme yok — dosyayı açtığın an oynanır.

**[▶ Oyna](https://Kurtayfun.github.io/Refleks/index.html)**

> Yukarıdaki linki GitHub Pages'te yayına aldıktan sonra kendi kullanıcı adın ve repo adınla güncelle.

---

## Nasıl oynanır

Ekranın üstünde 10 top sıralı duruyor. Bu toplardan rastgele ikisi, aralarında kısa bir gecikmeyle aşağı düşmeye başlıyor. Amaç, top tabana değmeden ona dokunup yakalamak.

- Bir seviyede toplam **10 top** düşer (5 çift halinde).
- 10 top da yakalanınca yeni bir seviye başlar — üstteki 10 slot yeniden dolar.
- Hangi iki topun ne zaman düşeceği belli değil; toplar azaldıkça hangi ikisinin kaldığı netleşir ama sırası hâlâ sürpriz.
- Seviye ilerledikçe düşüş hızı ve toplar arası gecikme kademeli olarak artar (ani sıçrama yok, yumuşak bir eğri).

### 🛡 Kalkan hakkı
Seviye 3'ü tamamladığında (skor 30) bir kerelik bir **kalkan hakkı** kazanılır. Bir topu kaçırdığında bu hak otomatik devreye girer: top kırılıp kaybolur (skor almaz), ekrandaki tüm toplar kısa bir an donar, "KALKAN DEVREDE!" bildirimi çıkar ve oyun kaldığı yerden devam eder — seviye baştan başlamaz. Bu hak oyun boyunca **sadece bir kez** kullanılabilir.

---

## Özellikler

- 📱 Mobil dikey ekranlara uygun tek sayfalık tasarım
- 🎧 Tüm ses efektleri Web Audio API ile kodla üretiliyor — dış ses dosyası yok
- 🔊 Sesli 3-2-1 geri sayımı ve başlama sesi
- 🏆 `localStorage` ile cihazda kalıcı en yüksek skor takibi
- ✨ Neon dark-mode arayüz, rekor kırma anında altın parlama efekti, taban çizgisinde "yanma" efekti
- 🛡 Tek seferlik kalkan hakkı ve adil bir "kurtarma" mekaniği
- 🎯 Görsel olarak üstteki sıradaki toplarla birebir aynı, sadece dokunma alanı biraz daha geniş

---

## Teknik

Tek dosya: `refleks-oyunu.html` — HTML, CSS ve JavaScript hepsi bu dosyanın içinde. Harici kütüphane, build adımı veya sunucu tarafı kod yok.

## GitHub Pages ile yayınlama

1. Bu dosyaları bir repoya yükle (`refleks-oyunu.html` ve bu `README.md`).
2. Repo **Settings → Pages** kısmından `main` dalını ve kök dizini (`/root`) kaynak olarak seç.
3. Birkaç dakika içinde `https://KULLANICI_ADIN.github.io/REPO_ADIN/refleks-oyunu.html` adresinden erişilebilir olur.

## Geri bildirim

Bu proje aktif test aşamasında. Hız, zorluk eğrisi veya kalkan mekaniğiyle ilgili geri bildirimlerin memnuniyetle karşılanır.
