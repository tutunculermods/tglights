# TG LIGHTS 1.1.0

**Tütüncüler Garaj · Live for Speed**  
Türkçe / English · Windows 10 ve 11 · LFS 0.7E veya üzeri

## Türkçe

### Kurulum ve ilk sürüş

1. ZIP dosyasını bir klasöre ayıkla. Kurulum için **TG-LIGHTS-Setup.exe**, taşınabilir kullanım için **TG-LIGHTS.exe** aç. Kurulu sürümü Windows **Ayarlar → Uygulamalar** üzerinden kaldırabilirsin.
2. TG LIGHTS yerel LFS oturumunu **127.0.0.1:29999** adresinde otomatik arar. Ekranda “LFS bekleniyor” kalırsa LFS sohbetine **`/insim 29999`** yaz. Alternatif olarak oyunu **`LFS.exe /insim=29999`** ile başlat.
3. **Polis**, **Ambulans** veya **İtfaiye** profilini seç. Pitten piste çıktığında kontrol panelinde araç ve çakar kanalı görünür.

| Varsayılan tuş | İşlev |
|---|---|
| Page Down | Çakarları aç / kapat |
| Page Up | Sireni Kapalı → Wail → Yelp → Kapalı sırasıyla değiştir |
| End | Çakarları ve sireni birlikte kapat |

Kısayollar LFS ön plandayken çalışır. **Tuşlar** bölümünde bir atamayı seçip yeni tuşa basabilirsin. Sunucuda siren için sürücüye izin verilmesi gerekebilir.

### Desenler ve araç ayarları

**Desenler** sekmesinde sekiz ritim, %60–160 hız ayarı ve beş saniyelik önizleme bulunur. Yeni ritimler **Eşzamanlı çift**, **İki kısa bir uzun**, **Çapraz final** ve **Yavaş devriye**. Desen ve hız seçili hizmet profiline kaydedilir.

**FEND INTERCEPTOR** ve **FZ60 LIGHTBAR** için Polis profili varsayılan olarak ön ve arka sis kanallarını sürer. Diğer araçlarda hangi kanalın tepe lambasına bağlandığını modun yapımcısı belirler. **Ayarlar → Çakar bağlantısı** bölümünden kanal seçip **Seçili kanalı 2 sn yak** düğmesini kullan. Hangi lambanın yandığına dış kameradan bak. Seçim aktif araç, konfigürasyon ve hizmet profili için saklanır. Far, selektör ve dörtlü komutu gönderilmez. Tepe lambası yalnızca sinyallere bağlı bir konfigürasyonda bu uygulama o lambayı bağımsız yakamaz.

**Ayarlar → Sürüş ve pencere** bölümünde sirenle çakarları açmayı, çakarlar kapanınca sireni susturmayı ve pencereyi üstte tutmayı ayrı ayrı seçebilirsin. Üçü de ilk kurulumda kapalıdır.

### Güncelleme ve iletişim

TG LIGHTS her açılışta resmi GitHub deposunun son kararlı sürümünü kontrol eder. Daha yeni sürüm varsa indirme teklifi ekrana gelir. **Ayarlar → Güncellemeleri kontrol et** düğmesiyle aynı kontrolü elle başlatabilirsin. İndirme kabul edilince paket SHA-256 ile doğrulanır ve kurucu açılır. Taşınabilir kullanıyorsan kurucuda **Taşınabilir EXE kaydet** seçeneğiyle mevcut uygulama dosyanı yenileyebilirsin.

- [Resmi sürümler](https://github.com/tutunculermods/tglights/releases)
- [Discord sunucusu](https://discord.gg/e5VMUzP5wK)

## English

### Quick start

Extract the ZIP. Run **TG-LIGHTS-Setup.exe** to install, or **TG-LIGHTS.exe** for portable use. To uninstall an installed copy, use **Windows Settings → Apps**. TG LIGHTS reconnects to **127.0.0.1:29999** automatically. If it keeps waiting, type **`/insim 29999`** in LFS chat. Choose a service profile and leave the pits.

With LFS in focus, **Page Down** toggles flashers, **Page Up** cycles Off → Wail → Yelp → Off, and **End** stops both. Change keys in **Shortcuts**. Server permission may be required for siren audio.

Choose from eight patterns and set speed per service profile. In **Settings**, you can link flashers to siren activation, mute the siren when flashers stop, or keep the window on top. For an unfamiliar vehicle, select a lightbar channel and use the two-second test while watching the car from outside. Channel overrides are saved per vehicle, configuration and service profile. The app sends no headlight, high-beam flash or hazard commands.

Every launch checks the official GitHub release feed. A newer version triggers a download prompt. You can also select **Settings → Check for updates**. Downloads are checked against GitHub’s SHA-256 digest before opening the installer. For a portable update, choose **Save portable EXE** in the installer. The Discord invite is under **Settings → Contact**.

Gelecek sürümlerde uygulamanın ve kurucunun sürüm numarasını birlikte artır. Örneğin **1.1.1** derlemesi için etiketi **`v1.1.1`**, arşiv adını **`TG-LIGHTS-1.1.1.zip`** yap. Güncelleme bildirimi yalnızca kurulu sürümden daha yüksek bir kararlı sürüm için gösterilir. **1.0.x** kullananlar sabit depolu güncelleyiciye geçmek için bu paketi bir kez elle kurabilir.

