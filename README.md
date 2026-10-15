# Protez Kol

Windows için DarkOrbit Unity ve Flash yardımcı uygulaması. v0.6.7, Flash desteğini ve otomatik güncellemeyi aynı kuruluma ekler; oyuncu adı üzerindeki beyaz bilgi kutusunu kaldırır. Kullanım için geçerli müşteri lisansı gerekir; lisans satın almak için [Discord sunucumuza](https://discord.gg/yTcYZxEQdC) katıl.

## İndir ve kur

[Windows için kurulum paketini indir](https://github.com/smhguler/protez-kol/releases/latest/download/Protez-Kol-Kurulum.exe)

1. `Protez-Kol-Kurulum.exe` dosyasını açıp kurulum sihirbazını tamamla. İlk indirmede Windows çalıştırma onayı gösterebilir.
2. Sonraki açılışlarda masaüstündeki **Protez Kol** kısayolunu kullan.
3. İlk kullanımda müşteri lisans anahtarını gir ve **Etkinleştir** düğmesine bas.
4. DarkOrbit'i açıp oyun haritasına gir. Protez Kol'da **Bağlan** düğmesine bas. Oyun seçimi sorulursa Unity veya Flash istemcisini seç.

Kurulum Windows kullanıcı hesabına yapılır; yönetici yetkisi istemez. Güncellemeden önce açık Protez Kol'u kapatıp yeni kurulum paketini çalıştır. Lisansın ve ayarların korunur. Kaldırmak için Windows Ayarları > Uygulamalar bölümünü kullan.

Kurulumsuz kullanmak istersen [ZIP paketini indir](https://github.com/smhguler/protez-kol/releases/latest/download/Protez-Kol.zip), bir klasöre çıkar ve `ProtezKol.exe` dosyasını aç.

64 bit Windows ve internet bağlantısı gerekir. Ek .NET kurulumu gerekmez. Desteklenen istemciler **DarkOrbit Unity 1.1.112, 1.1.113, 1.1.114** ve **resmî Flash 1.6.9**. Tek açık istemci otomatik tanınır; iki istemci açıksa veya oyun henüz açık değilse seçim ekranı gösterilir. Lisans ortaktır, Unity ve Flash ayarları ayrı saklanır. Oyun güncellenirse yeni bir Protez Kol sürümü gerekebilir.

Kurulumla yüklenen uygulama her açılışta yeni kararlı sürümü denetler. Yeni sürüm varsa önce sana sorar; onaylamadan hiçbir şey indirilmez. **Evet** dersen resmî GitHub paketini indirip doğrular, komutları durdurur ve güncellemeden sonra yeniden açılır. Şimdi istemezsen daha sonra uygulamanın üst kısmındaki güncelleme bağlantısına tıklayabilirsin. Lisansın ve ayarların korunur. İnternet yoksa mevcut sürüm açılır. Otomatik güncellemeyi kullanmak için kurulum paketini bir kez yükle; ZIP kullanımı elle güncellenir.

## Kullanım

F6 en yakın NPC'yi, F7 en yakın oyuncuyu, F8 başka bir oyuncunun en yakın PET'ini seçer. Tuşları uygulamadan değiştirebilirsin. Hedef değiştirme, seçimden sonra saldırı isteği, daha yakın aynı tür hedefe geçiş ve NPC/oyuncu için ayrı RSB cephaneleri isteğe bağlıdır. Kendi klanın ve ittifaklarının oyuncuları/PET'leri hedeflemeden elenir.

Otomatik ateşleme için **Tuşla seçince saldır** kutusunu aç. Saldırı, oyunda seçili cephaneyle başlar. **RSB otomatik geçiş** açıksa devam eden saldırıda RSB kullanılınca ayarladığın bekleme cephanesine döner. Geçici oyun hatalarında döngü açık kalır; kapatmak için kutunun işaretini kaldır.

**NPC takibi: yeni hedefe geç ve saldır** açıksa menzildeki uygun NPC'ye saldırır, hedef bitince sonraki NPC'ye geçer ve NPC yoksa yenisini bekler. **NPC ateş mesafesi** değerini oyundaki menziline göre ayarla. **NPC öncelikleri** penceresinde üst satırdaki ad önce seçilir; öncelikli NPC'ye saldırırken daha yakın normal NPC'ye dönülmez. Klan, ittifak ve saldırmazlık anlaşması olan gemiler/PET'ler korunur. Aynı şirketteki bütün oyuncuları elemek için **Yalnız farklı şirket** kutusunu aç.

**F9**, uygulamanın yeni komutlarını durdurur; oyunda başlamış ateşi durdurmaz. Ayrıntılı kullanım paket içindeki **ONCE-OKU.txt** dosyasındadır.

## Lisans ve destek

Lisans çevrimiçi doğrulanır. Anahtarını paylaşma. Lisansına tanımlanan bilgisayar sınırı geçerlidir; sınırsız lisans birden fazla bilgisayarda etkinleştirilebilir. Bilgisayar sınırın dolarsa [Discord](https://discord.gg/yTcYZxEQdC) üzerinden bize yaz.

Lisans bağlantısı hatası alırsan internetini kontrol et ve birkaç dakika sonra tekrar dene. Sorun sürerse hata mesajını [Discord](https://discord.gg/yTcYZxEQdC) üzerinden bize ilet. Lisans anahtarını Discord kanallarında veya başka herkese açık bir yerde paylaşma.

## Bilmen gerekenler

Bigpoint oyun otomasyonunu kullanım şartlarında yasaklar; hesabın engellenebilir. Protez Kol, Bigpoint ürünü değildir ve Bigpoint tarafından onaylanmamıştır.
