# İSG Kimya Sınavı PWA - Kurulum Talimatları 📱

## PWA (Progressive Web App) Nedir?
Bu uygulama, telefonunuzda normal bir uygulama gibi çalışır ancak mağazadan indirmeye gerek yoktur. İnternet olmadan bile kullanabilirsiniz!

## 📲 Android'de Kurulum

### Yöntem 1: Tarayıcı Üzerinden (Chrome/Edge)
1. **Dosyaları web sunucusuna yükleyin** (aşağıda detaylar var)
2. Chrome veya Edge tarayıcınızla siteyi açın
3. Sağ alt köşede "📱 Uygulamayı Yükle" butonuna tıklayın
4. "Yükle" veya "Ekle"ye basın
5. Uygulama ana ekranınıza eklenecek! 🎉

### Yöntem 2: Manuel Ekleme
1. Siteyi Chrome'da açın
2. Sağ üst köşedeki ⋮ (üç nokta) menüsüne tıklayın
3. "Ana ekrana ekle" seçeneğini seçin
4. İsmi onaylayın ve "Ekle"ye basın

## 🍎 iOS (iPhone/iPad)'de Kurulum

1. Safari tarayıcısında siteyi açın
2. Alt kısımdaki "Paylaş" butonuna (⎙) dokunun
3. "Ana Ekrana Ekle" seçeneğini bulun ve dokunun
4. İsmi onaylayın ve "Ekle"ye basın
5. Ana ekranınızda uygulama simgesi görünecek!

## 🌐 Dosyaları Web'e Yükleme

PWA'nın çalışması için dosyaların bir web sunucusunda olması gerekir. İşte ücretsiz seçenekler:

### Seçenek 1: GitHub Pages (Ücretsiz, Kolay)
1. GitHub hesabı oluşturun (github.com)
2. Yeni bir repository (depo) oluşturun
3. Bu 3 dosyayı yükleyin:
   - `isg_kimya_sinav_pwa.html`
   - `manifest.json`
   - `service-worker.js`
4. Settings > Pages > Branch: main seçin
5. Siteniz şu adreste yayında: `https://kullaniciadi.github.io/depo-adi/isg_kimya_sinav_pwa.html`

### Seçenek 2: Netlify (Ücretsiz, Çok Kolay)
1. netlify.com'a gidin ve ücretsiz hesap açın
2. "Add new site" > "Deploy manually"
3. 3 dosyayı sürükle-bırak yapın
4. Netlify otomatik bir URL verecek

### Seçenek 3: Firebase Hosting (Ücretsiz)
1. firebase.google.com > Console
2. Yeni proje oluşturun
3. Hosting bölümünden "Get started"
4. Firebase CLI ile dosyaları yükleyin

### Seçenek 4: Vercel (Ücretsiz)
1. vercel.com'a gidin
2. GitHub hesabınızla giriş yapın
3. Dosyaları içeren repository'yi deploy edin

## 📁 Gerekli Dosyalar
Toplam 3 dosya:
1. ✅ `isg_kimya_sinav_pwa.html` - Ana uygulama
2. ✅ `manifest.json` - Uygulama ayarları
3. ✅ `service-worker.js` - Offline çalışma

## ⚡ Özellikler

✨ **Offline Çalışma**: İnternet olmadan da kullanabilirsiniz
📱 **Ana Ekranda**: Normal uygulama gibi
🎨 **Tam Ekran**: Tarayıcı çubukları olmadan
🔄 **Otomatik Güncelleme**: Sayfa yenilendiğinde güncellenir
💾 **Hızlı Yükleme**: Veriler önbellekte saklanır

## 🚨 Sorun Giderme

**"Uygulamayı Yükle" butonu görünmüyor:**
- HTTPS bağlantısı gerekli (localhost hariç)
- Chrome veya Edge kullanın
- Zaten yüklü olabilir, kontrol edin

**Offline çalışmıyor:**
- İlk açılışta internet gerekli
- Service worker kaydı başarılı mı kontrol edin
- Tarayıcı konsolunda hata var mı bakın

**iOS'ta çalışmıyor:**
- Safari kullanın (Chrome değil)
- "Ana Ekrana Ekle" özelliğini kullanın
- Service worker iOS'ta sınırlı desteklenir

## 🎓 Kullanım

Uygulama yüklendikten sonra:
1. Ana ekrandaki simgeye dokunun
2. Sınav otomatik başlar (20 rastgele soru)
3. Soruları cevaplayın
4. "Sınavı Tamamla" ile sonuçları görün
5. "Sınavı Yeniden Başlat" ile yeni sorular

## 💡 İpuçları

- Her yeniden başlatmada 50 sorudan 20 tanesi rastgele seçilir
- İnternet olmadan da çalışır (ilk yüklemeden sonra)
- Sonuçlarınız kaydedilmez (gizlilik için)
- Telefonu döndürerek daha rahat okuyabilirsiniz

## 🆘 Yardım

Sorun yaşarsanız:
1. Uygulamayı ana ekrandan silin
2. Tarayıcı önbelleğini temizleyin
3. Siteyi yeniden ziyaret edin
4. Yeniden ana ekrana ekleyin

---

**Not:** Bu bir Progressive Web App'tir, Google Play veya App Store'da değildir. Doğrudan web üzerinden yüklenir.

Başarılar! 🎉
