# Schengen-Visa-Appointment-Tracker-Bot
Schengen vizesi randevularını düzenli olarak kontrol eden ve Telegram üzerinden bildirim gönderen bir Python botu.

Özellikler
Belirli aralıklarla (örneğin, 1 saatte bir) Schengen vize randevularını kontrol eder.
Uygun randevu bulunduğunda veya mevcut olmadığında Telegram üzerinden bilgilendirme yapar.
Kolayca özelleştirilebilir API URL'si ve zamanlama ayarları.

Kullanılan Teknolojiler
Python: Ana programlama dili.
requests: HTTP isteklerini göndermek için.
python-telegram-bot: Telegram bot entegrasyonu için.
apscheduler: Görev zamanlayıcı.

API URL: Yeni bir API için API_URL değişkenini güncelleyebilirsiniz.
Kontrol Sıklığı: Zamanlayıcıyı scheduler.add_job fonksiyonunda interval ayarlarını değiştirerek özelleştirebilirsiniz.
