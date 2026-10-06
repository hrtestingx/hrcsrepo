# 📋 HRCS Repo — GitHub Issue (Konu Açma) Kuralları

Bu depo, CloudStream 3 Türkçe eklenti topluluğuna açık kaynaklı olarak hizmet vermektedir. Sorunların hızlı çözülebilmesi ve taleplerin düzenli takip edilebilmesi için lütfen konu (Issue) açmadan önce aşağıdaki kuralları dikkatlice okuyun.

---

## 📌 1. Genel Kurallar

1. **Arama Yapın:** Bir konu açmadan önce mutlaka [Açık ve Kapanmış Sorunlar (Issues)](https://github.com/hrtestingx/hrcsrepo/issues?q=is%3Aissue) sekmesinde arama yapın. Aynı başlık altında zaten açık olan veya çözülmüş konular **yinelenen (duplicate)** olarak doğrudan kapatılır.
2. **Şablonları Eksiksiz Doldurun:** Konu açarken GitHub formundaki alanları boş bırakmayın veya şablonu silmeyin. Yetersiz bilgi içeren konular ("video açılmıyor", "hata verdi" gibi detay içermeyen bildirimler) kapatılır.
3. **Nezaket ve Saygı:** Bu proje gönüllü olarak geliştirilmektedir. Lütfen iletişimde yapıcı, kibar ve açıklayıcı bir dil kullanın.

---

## 🐛 2. Hata Bildirimi (Bug Reports) Kuralları

Eğer bir sitede video oynamıyor, içerikler listelenmiyor veya eklenti çöküyorsa:

* **Önce DNS / VPN Deneyin:** Türkiye'deki ISS kısıtlamaları nedeniyle çoğu video sunucusu yerel DNS adreslerinde engellidir. Cihazınızda **Cloudflare DNS (1.1.1.1)** veya **Google DNS (8.8.8.8)** kurulu olduğundan emin olun.
* **Eklenti ve CloudStream Güncelliği:** Depo otomatik güncellenir. CloudStream ayarlarından eklentinin en güncel sürümde olup olmadığını kontrol edin.
* **Tek Konu - Tek Hata:** Birden fazla farklı eklentideki sorunları aynı başlık altına yığmayın; her eklenti veya site için ayrı konu açın.
* **Log (Hata Kaydı) Ekleyin:** Çökme veya oynatma hatalarında `Settings ➔ Debug ➔ Export Logs` yolunu izleyerek veya Logcat alarak hatanın çıktısını paylaşmanız çözümü 10 kat hızlandırır.

---

## 🌐 3. Yeni Site & Eklenti İstekleri Kuralları

Eklentilere yeni bir web sitesi veya depoya tamamen yeni bir eklenti paketi eklenmesini önerirken:

1. **Aktiflik ve Çalışırlık:** Önerdiğiniz sitenin tarayıcıda stabil çalıştığını ve videolarının oynatılabilir durumda olduğunu teyit edin.
2. **Yasaklı İçerikler:** 
   * Yetişkin (+18) içerikli siteler,
   * Yasa dışı bahis / kumar odaklı siteler,
   * Agresif ve zararlı reklam yazılımları barındıran kontrolsüz siteler **kesinlikle kabul edilmez**.
3. **Kategori Uyumu:** Önerdiğiniz site depodaki mevcut paketlerle örtüşmelidir:
   * **HR Anime:** Yalnızca anime ve donghua siteleri.
   * **HR AsianDrama:** Yalnızca Asya (Kore, Çin, Japon, Tayland) dizileri/filmleri.
   * **HR ShortDrama:** Dikey mini drama (Reels formatı) siteleri.
   * **HR Kids:** Çizgi film, animasyon ve eğitici çocuk içerikleri.
4. **Site Değişiklikleri:** Sitenin alan adı (domain) değiştiyse yeni site isteği yerine *"Domain Güncellemesi"* olarak belirtin (ayrıca eklenti ayarlarından domain adresini kendiniz de güncelleyebilirsiniz).
5. **Tamamen Yeni Eklenti Paketleri:** Eğer mevcut kategorilerin dışına çıkan bağımsız bir konsept öneriyorsanız (örn: *Belgesel, Sinema vb.*), *"Yeni Eklenti İsteği"* şablonunu kullanın ve en az 2-3 adet aktif örnek web kaynağı belirtin.

---

## ❓ 4. Soru & Bilgi Alma (Yardım Talebi) Kuralları

Kurulum, eklenti ayarları veya özellikler hakkında bilgi almak istediğinizde:

1. **Önce S.S.S. Bölümüne Bakın:** Ana sayfadaki Sıkça Sorulan Sorular bölümünde DNS, eklenti güncelleme ve kaynak ayarları gibi en temel soruların yanıtları verilmiştir.
2. **Hata Bildirimlerini Ayırın:** Eğer bir içerik açılmıyor veya uygulama çöküyorsa burayı değil, *"Hata Bildirimi"* şablonunu kullanın.
3. **Açık ve Net Olun:** Neyi merak ettiğinizi veya hangi ayarı yapılandırmakta zorlandığınızı açıkça ifade edin.

---

## 📺 5. Canlı TV Yayınları İçin Özel Not

* Canlı yayın linkleri doğası gereği geçici adresler, yoğunluklar veya kaynak sunucu kaynaklı anlık kesintilere maruz kalabilir.
* Anlık 5-10 dakikalık yayın donmaları için issue açmayınız; kaynak tamamen ölmüş veya kanal uzun süredir çalışmıyorsa bildiriniz.

---

## ⛔ Doğrudan Kapatılacak Başlıklar

Aşağıdaki durumlara sahip konular uyarılmaksızın etiketlenip kapatılacaktır:
* ❌ *"Neden çalışmıyor mk?", "Açılmıyor", "Hata var"* gibi tek cümlelik, açıklamasız konular.
* ❌ Şablon formunun doldurulmadığı veya boş bırakıldığı konular.
* ❌ Zaten bildirilmiş ve üzerinde çalışılan mükerrer konular.
* ❌ Eklenti dışı, CloudStream'in kendi temel yazılım hatalarıyla ilgili genel Android sorunları (bu sorunlar [CloudStream Resmi Deposu](https://github.com/recloudstream/cloudstream)'na iletilmelidir).
