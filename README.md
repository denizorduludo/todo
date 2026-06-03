# Yapılacaklar · To-Do

Toprak tonları + Color Series paletiyle, sade ve ferah bir yapılacaklar listesi.
Saf HTML/CSS/JS ile yazıldı; veritabanı olarak **Supabase** kullanır.

## Özellikler

- 🔐 E-posta + şifre ile **kayıt / giriş** (Supabase Auth) — e-posta doğrulamalı
- 👤 Görevler **kullanıcıya özel** (RLS ile herkes yalnızca kendi görevlerini görür)
- ✅ Görev ekleme / tamamlama / silme
- 📅 Booking tarzı takvimden **başlangıç ve bitiş tarihi** seçme
- 🕐 Başlangıç ve bitiş **saati** ekleme
- ↕️ Sıralama: eklenme tarihi · A→Z · başlangıç tarihi
- 🔎 Filtreler: Tümü · Aktif · Bitti
- ☁️ Veriler Supabase bulut veritabanında saklanır

## Çalıştırma

`index.html` dosyasını bir tarayıcıda açmak yeterli. Yerel sunucu için:

```bash
npx serve -l 4173 .
```

## Teknolojiler

- HTML / CSS / Vanilla JS (ES modules)
- [Supabase](https://supabase.com) (PostgreSQL + REST)
