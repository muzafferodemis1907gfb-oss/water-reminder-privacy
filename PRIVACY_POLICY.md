# Gizlilik Politikası — Water Reminder Hydrate Daily

**Son güncelleme:** 3 Ekim 2026

## Uygulama ve iletişim

Water Reminder Hydrate Daily (com.waterreminder.hydratedaily), Victorium Soft tarafından sunulan su tüketimi ve günlük aktivite takip uygulamasıdır. Gizlilik soruları için muzafferodemis1907gfb@gmail.com adresine yazabilirsiniz.

## SAĞLIK VERİLERİ: ERİŞİM, TOPLAMA, KULLANIM VE PAYLAŞIM

**Hangi sağlık verilerine erişiyoruz?** Uygulama, kullanıcının kaydettiği su ve içecek miktarları ile tüketim tarih/saatlerine, günlük su hedeflerine ve isteğe bağlı kilo/aktivite düzeyi ayarlarına erişir. Kullanıcı adım takibini açarsa `android.permission.ACTIVITY_RECOGNITION` ile cihazın adım sensöründen günlük adım sayısı ve zaman aralıklarına göre hareket bilgisi alınır. Kullanıcı Health Connect izni verirse `android.permission.health.READ_STEPS` ile adım sayısı ve kayıt zamanı okunur.

**Nasıl erişiliyor ve hangi amaçla kullanılıyor?** Su kayıtları ve isteğe bağlı hedef ayarları kullanıcı tarafından girilir. Adımlar, kullanıcı etkinleştirdiğinde cihaz sensöründen ve kullanıcı ayrıca izin verdiğinde Health Connect'ten okunur. Veriler cihazda günlük/haftalık/aylık su ve adım grafikleri, hedef ilerlemesi, su-adım karşılaştırması, aktivite özeti, hidrasyon skoru, akıllı hatırlatıcı ve kişiselleştirilebilir hedef için işlenir. Tıbbi teşhis veya tedavi amacıyla kullanılmaz.

**Toplama, paylaşım ve aktarım:** Geliştirici bu sağlık verilerini kendi sunucularına toplamaz. Su, kilo/aktivite ve adım verileri AdMob'a, reklam hedefleme ortaklarına veya veri aracılarına aktarılmaz ya da satılmaz. İsteğe bağlı Wear OS senkronizasyonunda su/adım özetleri eşleştirilmiş cihazlar arasında Google Play Hizmetleri Data Layer ile aktarılabilir. Kullanıcı isteğe bağlı CSV/JSON dışa aktarmayı kullanırsa yalnızca kendi seçtiği hedefe dosya gönderilir. AdMob'un sağlık kayıtlarından ayrı olarak işlediği reklam/cihaz verileri aşağıdaki reklam bölümünde açıklanır.

**Saklama, silme ve izinler:** Uygulamanın tuttuğu kayıtlar cihazdaki uygulamaya özel yerel depolamada kalır. Kullanıcı bunları uygulamanın veri silme özelliğiyle veya Android uygulama verilerini temizleyerek ya da uygulamayı kaldırarak silebilir. ACTIVITY_RECOGNITION izni Android ayarlarından, READ_STEPS izni Health Connect ayarlarından geri alınabilir. Uygulama verilerini silmek Health Connect'in özgün kayıtlarını veya dışa aktarılmış dosyaları otomatik silmez.

## HEALTH DATA DISCLOSURE (ENGLISH)

Water Reminder Hydrate Daily accesses user-entered water/beverage intake amounts and timestamps, hydration goals and optional weight/activity settings. When the user enables step tracking, the app accesses step counts and time-binned activity through the device step sensor using `ACTIVITY_RECOGNITION`; if the user separately authorizes Health Connect, it reads step counts and record times through `android.permission.health.READ_STEPS`. These data are processed on-device for daily/weekly/monthly charts, step and hydration targets, activity summaries, water-step comparisons, reminder scheduling and nonmedical wellness scores. The developer does not collect this health data on developer-operated servers or sell/provide it to AdMob or advertising partners. Optional Wear OS synchronization transfers water/step summaries between paired devices through Google Play services; user-directed CSV/JSON export sends selected data to destinations chosen by the user. App-stored data can be deleted in the app or by clearing app storage/uninstalling. Health Connect permission can be revoked in Health Connect settings; deleting local data does not delete original Health Connect records or exported files. AdMob independently processes advertising/device data disclosed below.

## Cihazda işlenen bilgiler

Su ve içecek kayıtları, günlük hedef, geçmiş, hatırlatıcı saatleri, kullanıcının girdiği yaş, kilo ve aktivite düzeyi gibi akıllı hedef ayarları, adımlar, rozetler, tema ve bildirim tercihleri özellikleri sunmak amacıyla cihazda işlenebilir. Bu kayıtlar geliştiricinin sunucusuna gönderilmez.

CSV/JSON dışa aktarma ve yedekleme yalnızca kullanıcı başlattığında çalışır. Paylaşılan dosya, kullanıcının seçtiği hedefin gizlilik şartlarına tabidir.

## Adım sensörü ve Health Connect

Kullanıcı adım sayacını açtığında ACTIVITY_RECOGNITION izniyle cihazın adım sensörü kullanılabilir. Etkin arka plan adım takibi Android ön plan hizmeti ve görünür bildirimle sürdürülür.

Kullanıcı izin verirse android.permission.health.READ_STEPS aracılığıyla Health Connect'ten adım toplamları okunabilir. Veriler günlük/haftalık aktivite ve su-adım analizi için cihazda işlenir; geliştirici sunucusuna gönderilmez. İzin Health Connect ayarlarından geri alınabilir. Health Connect'teki kaynak kayıtlar yerel veri silme işleminden bağımsızdır.

## Reklamlar ve üçüncü taraflarla veri işleme

Uygulama Google AdMob reklam hizmeti kullanır. Google Mobile Ads SDK, reklam sunumu, ölçüm, analiz ve sahtekârlığı önleme amacıyla IP adresi (yaklaşık konum çıkarımı için kullanılabilir), uygulama ve reklam etkileşimleri, tanılama bilgileri ve cihaz/uygulama tanımlayıcılarını Google'a otomatik iletebilir. Reklam kimliğinin kullanımı cihaz ayarlarına ve uygulamanın SDK yapılandırmasına bağlıdır.

Uygulamanın çocukları da içerebilen hedef kitlesi nedeniyle reklam istekleri çocuklara yönelik işlem sinyali ve en fazla G içerik derecesiyle yapılandırılır. Bu ayarlar Google'ın veri işlemesini tamamen ortadan kaldırmaz. Geliştirici kullanıcının su, profil veya adım kayıtlarını AdMob'a reklam hedefleme için doğrudan göndermez ve bu kayıtları satmaz.

## Google Play Billing ve Premium

Reklamsız Premium satın alma Google Play üzerinden yapılır. Uygulama Premium hakkını yönetmek için satın alma durumunu ve işlem tanımlayıcılarını işleyebilir; geliştirici ödeme kartı veya banka hesabı bilgilerini doğrudan almaz. Google Play'in kendi veri işleme kuralları geçerlidir.

## Wear OS

Eşleştirilmiş Wear OS saati kullanılırsa su ve adım özetleri ile uygulama durumu Google Play Hizmetleri Data Layer aracılığıyla telefon ve saat arasında aktarılabilir. Geliştirici bu veriler için ayrı bir sunucu işletmez.

## Kullanılan izinler

ACTIVITY_RECOGNITION ve FOREGROUND_SERVICE_HEALTH, etkinleştirilmiş adım takibi için; READ_STEPS, izinli Health Connect adım okuma için; POST_NOTIFICATIONS, su/aktivite bildirimleri için; INTERNET, ACCESS_NETWORK_STATE ve AD_ID, AdMob, Google Play Billing ve desteklenen hizmetler için; RECEIVE_BOOT_COMPLETED, etkin hatırlatıcıları yeniden kurmak için kullanılabilir.

## Güvenlik, saklama ve silme

Uygulamanın kendi kayıtları Android'in uygulamaya özel yerel depolamasında tutulur ve Android sistem yedeklemesi kapalıdır. Google, Mobile Ads SDK verilerini ağ üzerinden TLS ile aktardığını belirtir. Hiçbir yöntem mutlak güvenlik garantisi sunmaz.

Yerel veriler uygulama içindeki “Tüm yerel verileri sil” işlevi, Android uygulama verilerini temizleme veya uygulamayı kaldırma ile silinebilir. Dışa aktarılan dosyaların ve Health Connect kaynak kayıtlarının ayrıca silinmesi gerekebilir. Google'ın reklam/satın alma verilerinin saklama ve silinmesi kendi gizlilik politikasına tabidir.

## Çocukların gizliliği

Uygulama çocukları da içerebilen bir kitleye sunulabilir. Geliştirici su, profil ve adım kayıtlarını kendi sunucusunda toplamaz. Reklam isteklerinde çocuklara yönelik işlem sinyali ve G içerik derecesi sınırı kullanılır. Ebeveynler ve kullanıcılar cihaz izinlerini yönetebilir.

## Sağlık uyarısı

Uygulama tıbbi cihaz değildir. Su hedefleri, hidrasyon skoru, adım, tahmini mesafe ve su-aktivite ilişkisi gibi çıktılar genel iyi yaşam ve kişisel takip içindir; teşhis, tedavi veya profesyonel sağlık tavsiyesi değildir.

## Değişiklikler

Uygulamanın özellikleri veya veri işleme uygulamaları değiştiğinde bu politika güncellenebilir. Güncelleme tarihi sayfanın başında gösterilir.

Gizlilik iletişimi: muzafferodemis1907gfb@gmail.com

Google Gizlilik Politikası: https://policies.google.com/privacy

Google Mobile Ads SDK veri açıklaması: https://developers.google.com/admob/android/privacy/play-data-disclosure
