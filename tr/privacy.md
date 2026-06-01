---
title: Gizlilik Politikası — Dycers
---

# Gizlilik Politikası — Dycers

**Son güncelleme:** 28 Mayıs 2026
**Yürürlük tarihi:** 28 Mayıs 2026

Bu Gizlilik Politikası, „**Dycers**" mobil uygulamasının (bundan böyle „**Uygulama**" olarak anılacaktır) kişisel verilerinizi nasıl topladığını, kullandığını, paylaştığını ve koruduğunu açıklamaktadır. AB Genel Veri Koruma Yönetmeliği („**GDPR**") ve eşdeğer yerel kurallara uygun şekilde hazırlanmıştır.

---

## 1. Veri sorumlusu

Veri sorumlusu, Avrupa Birliği'nde yerleşik bireysel bir yayıncı olan **Quentin Ameline**'dir.

Gizlilikle ilgili herhangi bir soru veya haklarınızı kullanmak için: **dycersofficial@gmail.com**

---

## 2. Topladığımız kişisel veriler

### 2.1 Bize sağladığınız veriler

| Veri | Ne zaman toplarız | Amaç |
|------|------------------|------|
| **E-posta adresi** | Kayıt, giriş, e-posta değişikliği, şifre sıfırlama | Hesap kimliği, kimlik doğrulama, işlemsel e-postalar |
| **Şifre (hash'li)** | Kayıt, şifre değişikliği | Kimlik doğrulama. Şifreleri hiçbir zaman düz metin olarak saklamıyoruz — bcrypt ile hash'leniyor. |
| **Doğrulama kodları** | Kayıt, şifre sıfırlama, e-posta değişikliği | Kimlik doğrulama |
| **Seçilen bahis şirketleri** | Katılım ve ayarlar | Arbitraj uyarılarını filtreleme |
| **Seçilen sporlar / ligler** | Katılım ve ayarlar | Uyarıları filtreleme |
| **Kaydedilen bahisler** | Bahis eklendiğinde | Aktif bahisleri takip etme, geçmiş ve istatistikler |
| **Abonelik seviyesi** | Satın alma veya geri yükleme sonrası | İlgili özelliklerin kilidini açma |

### 2.2 Üçüncü taraflardan alınan veriler

| Veri | Kaynak | Amaç |
|------|--------|------|
| **Apple kullanıcı tanımlayıcısı + e-posta + ad** | Apple ile Oturum Aç | Hesap oluşturma / giriş |
| **Google hesap kimliği + e-posta + ad** | Google ile Oturum Aç | Hesap oluşturma / giriş |
| **Satın alma makbuzu + abonelik durumu** | App Store, Google Play, RevenueCat | Aboneliği doğrulama |
| **Mobil reklam tanımlayıcısı (IDFA / GAID)** | Cihazınız, yalnızca izinle | Reklam gösterme (yalnızca ücretsiz kademe) |
| **Push bildirimi token'ı** | Cihazınız, izinle | Arbitraj uyarıları gönderme |

### 2.3 Otomatik olarak toplanan veriler

| Veri | Amaç |
|------|------|
| **Yaklaşık dil / bölge** | Uygulamayı dilinizde görüntüleme |
| **Uygulama sürümü, işletim sistemi türü ve sürümü** | Teknik tanılama |
| **Sunucu erişim günlükleri** (IP, zaman damgası, uç nokta, HTTP durumu) | Güvenlik, kötüye kullanımı önleme. 30 gün saklanır. |
| **Çökme ve hata günlükleri** (kişisel içerik olmaksızın) | Kararlılık izleme |

---

## 3. İşlemenin hukuki dayanakları (GDPR Madde 6)

| Amaç | Hukuki dayanak |
|------|---------------|
| Hesap oluşturma ve yönetimi, temel özellikler | **Sözleşmenin ifası** (Madde 6(1)(b)) |
| Abonelik işleme | Sözleşmenin ifası |
| Güvenlik e-postaları | Sözleşmenin ifası |
| Arbitraj push bildirimleri | **Rıza** (Madde 6(1)(a)) |
| Kişiselleştirilmiş reklamlar (ücretsiz kademe) | **Rıza** (Madde 6(1)(a)) |
| Kişiselleştirilmemiş reklamlar (ücretsiz kademe) | **Meşru menfaat** (Madde 6(1)(f)) |
| Güvenlik ve kötüye kullanımı önleme | **Meşru menfaat** (Madde 6(1)(f)) |
| Yasal yükümlülüklerin yerine getirilmesi | **Yasal yükümlülük** (Madde 6(1)(c)) |

---

## 4. Verilerinizi kimlerle paylaşıyoruz

Kişisel verilerinizi hiçbir zaman satmıyoruz. Yalnızca aşağıdaki hizmet sağlayıcılarla paylaşıyoruz:

| Sağlayıcı | Rol | Paylaşılan veriler | Konum |
|-----------|-----|-------------------|-------|
| **Railway** | Backend sunucu barındırma | Tüm hesap verileri, bahisler, ayarlar | ABD (Standart Sözleşme Maddeleri) |
| **Yönetilen PostgreSQL** (Railway aracılığıyla) | Veritabanı | Yukarıdakiyle aynı | ABD |
| **Brevo** | İşlemsel e-posta | E-posta adresi ve tek kullanımlık kodlar | Fransa / AB |
| **Apple** | Apple ile Oturum Aç, App Store, IAP, APNs | Apple kimliği, makbuzlar, push token'ları | ABD |
| **Google** | Google ile Oturum Aç, Google Play, FCM, AdMob | Google kimliği, makbuzlar, push token'ları, reklam kimliği | ABD / İrlanda |
| **RevenueCat** | Abonelik yetkilendirme yönetimi | Anonim kullanıcı kimliği, makbuzlar | ABD |
| **The Odds API** | Oran verileri | Hiçbiri — yalnızca giden | Birleşik Krallık |
| **Futbol istatistik sağlayıcısı** | Maç istatistikleri ve H2H | Hiçbiri — yalnızca giden | AB / Birleşik Krallık |
| **Google AdMob** | Ücretsiz kademe reklamcılığı | Mobil reklam kimliği (izin verilirse) | ABD / AB |
| **Expo** | Push bildirim altyapısı | Push token'ı, bildirim içeriği | ABD |

---

## 5. Uluslararası aktarımlar

AEA dışına yapılan aktarımlar için Standart Sözleşme Maddelerine, AB-ABD Veri Gizliliği Çerçevesine veya eşdeğer güvencelere dayanıyoruz. **dycersofficial@gmail.com** adresine yazarak ilgili güvencelerin bir kopyasını talep edebilirsiniz.

---

## 6. Reklamcılık ve izleme

**Ücretsiz kademede**, Uygulama **Google AdMob** aracılığıyla reklam gösterebilir. Tercihlerinizi istediğiniz zaman cihaz ayarlarından değiştirebilirsiniz. Ücretli kullanıcılar (Pro / Max) reklam görmez.

---

## 7. Veri saklama süreleri

| Veri | Saklama süresi |
|------|---------------|
| Hesap verileri | Hesabınız aktif olduğu sürece. Hesabın silinmesinden 30 gün içinde siliniyor. |
| Aktif bahisler | Bahis aktif olduğu sürece. |
| Bahis geçmişi | Hesabınız aktif olduğu sürece veya manuel silmeye kadar. |
| Doğrulama / sıfırlama kodları | En fazla 15 dakika. |
| Sunucu erişim günlükleri | 30 gün. |
| Ücretli abonelikler için muhasebe kayıtları | Geçerli vergi mevzuatına göre (genellikle 10 yıla kadar). |
| Push bildirim token'ları | İzin iptal edilene veya Uygulama kaldırılana kadar. |

---

## 8. Haklarınız

GDPR kapsamında şu haklara sahipsiniz: **Erişim**, **Düzeltme**, **Silme** (Uygulamada **Ayarlar → Hesap → Hesabı sil** bölümünde mevcuttur), **İşlemenin kısıtlanması**, **Veri taşınabilirliği**, **İtiraz** ve **Rızayı geri çekme**.

Bu hakları kullanmak için, hesabınıza bağlı e-posta adresinizden **dycersofficial@gmail.com** adresine yazın. Bir (1) ay içinde yanıt vereceğiz.

---

## 9. Güvenlik

Uygun teknik ve organizasyonel önlemler uyguluyoruz: **TLS (HTTPS)** şifreleme, şifreler için **bcrypt** hash'leme, platform güvenli depolamada **JWT** token'ları (`expo-secure-store`) ve üretim sistemlerine kısıtlı erişim.

---

## 10. Çocuklar

Uygulama **çocuklara yönelik değildir**. 18 yaşın altındaki kişilerden bilerek veri toplamıyoruz. Bir küçüğün bize kişisel veri sağladığını düşünüyorsanız **dycersofficial@gmail.com** adresinden bize ulaşın.

---

## 11. Çerezler ve benzer teknolojiler

Uygulama yerel bir mobil uygulamadır ve geleneksel web çerezleri kullanmaz. Oturumunuzu, dilinizi ve tercihlerinizi hatırlamak için cihazınızda yerel depolama (`expo-secure-store`, `AsyncStorage`) kullanır.

---

## 12. Üçüncü taraf gizlilik politikaları

- Apple — <https://www.apple.com/legal/privacy/>
- Google — <https://policies.google.com/privacy>
- Railway — <https://railway.com/legal/privacy>
- Brevo — <https://www.brevo.com/legal/privacypolicy/>
- RevenueCat — <https://www.revenuecat.com/privacy/>
- Expo — <https://expo.dev/privacy>
- The Odds API — <https://the-odds-api.com/privacy.html>

---

## 13. Bu Politikadaki değişiklikler

Önemli değişiklikler yaparsak, yürürlüğe girmeden en az on beş (15) gün önce Uygulama içinde veya e-posta yoluyla sizi bilgilendireceğiz.

---

## 14. İletişim

**dycersofficial@gmail.com**

---

*„Kabul ediyorum" düğmesine dokunarak veya Dycers'ı kullanmaya devam ederek, bu Gizlilik Politikasını okuduğunuzu ve anladığınızı onaylıyorsunuz.*
