# 🩺 HELUNEXA

**Rutin kontrol ve kronik hastalık takibinin hızlı, kolay ve hekim kontrollü yolu.**

---

## 📌 Nedir?

HELUNEXA, rutin sağlık kontrolü ve kronik hastalık takibini dijital ortama taşıyan bir sağlık platformudur. Amaç, hastanın randevu, sıra, tetkik ve sonuç için tekrar hastaneye gitme yükünü azaltmak; hekim kontrolünü merkeze alarak süreci hızlandırmaktır.

---

## 🎯 Temel Değer Önerisi

> Rutin sağlık kontrolünüzü hastane randevusu, sıra ve tekrar başvuru yüküne takılmadan tamamlayın; gerektiğinde doğru sağlık hizmetine yönlendirilin.

---

## 🧭 Projenin İki Temel Ekseni

### Eksen 1 — Kolaylık ve Hız
HELUNEXA, kullanıcının sağlık hizmetine ulaşırken yaşadığı randevu, sıra, tetkik için yeniden gitme ve sonuç göstermek için tekrar başvurma yükünü azaltmayı hedefler.

### Eksen 2 — Rutin Kontrol ve Kronik Takip
Hizmet; rutin sağlık kontrolünü veya kronik hastalık takip sürecini tamamlamak isteyen, hastane sürecini daha düzenli ve daha az zaman kaybıyla yürütmeye ihtiyaç duyan kişilere yöneliktir.

---

## 🚨 Çözdüğümüz Problem

Sağlık hizmeti mevcut olsa bile süreç çoğu kullanıcı için parçalıdır:

- Kullanıcı hangi kontrolün gerektiğini bilemeyebilir
- Randevu bulmakta zorlanabilir
- Tetkik için ayrı, sonuç değerlendirmesi için ayrı başvuru yapmak zorunda kalabilir
- Kronik hastalığı bulunan kişilerde bu yük belirli aralıklarla tekrar eder ve takiplerin ertelenmesine yol açabilir

---

## 💡 Çözümümüz

HELUNEXA; ilk hekim değerlendirmesini, gerekli tetkiklerin planlanmasını, sonuçların hekim tarafından değerlendirilmesini ve gerekiyorsa doğru sağlık hizmetine yönlendirmeyi **tek hizmet akışında** birleştirir.

### Hizmet Akışı

1. **Başvuru:** Kullanıcı sağlık öyküsünü, mevcut hastalıklarını ve önceki sonuçlarını paylaşır.
2. **Ödeme:** Hizmet bedeli online olarak ödenir (demo aşamasında).
3. **Hekim Değerlendirmesi:** Rutin kontrol veya kronik takip ihtiyacı belirlenir; gerekli plan hazırlanır.
4. **Tetkik:** Gerekli testler anlaşmalı laboratuvarda (VitaLab) veya kullanıcının tercih ettiği kuruluşta yaptırılır.
5. **Sonuç Yükleme:** Laboratuvar sonucu sisteme yüklenir.
6. **Hekim Raporu:** Hekim sonuçları değerlendirir; dijital rapor + reçete hazırlar.
7. **Sonraki Adım:** İzlem zamanı belirlenir; gerekiyorsa kullanıcı doğru branşa yönlendirilir.

---

## 👥 Hedef Kullanıcı

Yaşla sınırlandırılmayan iki ana kullanıcı ihtiyacı vardır:

- Uzun süredir rutin sağlık kontrolü yaptırmamış ve nereden başlayacağını bilmeyen kişiler
- Diyabet, hipertansiyon, dislipidemi veya benzeri kronik hastalıkları için düzenli takip gereken kişiler

---

## 🎁 Kullanıcı Açısından Değer

- Hangi kontrol ve tetkiklerin gerektiğini bilmek
- Randevu, sıra ve tekrar başvuru yükünü azaltmak
- Tetkik sonuçlarını hekim değerlendirmesi olmadan yalnız bırakmamak
- Kronik hastalık takiplerini zamanında ve düzenli tamamlamak
- Gerekli durumda doğru branşa temel sonuçlar ve kısa özetle başvurmak
- Sonraki kontrol zamanını tek bir yol haritasında görmek

---

## 🚀 Başlangıç Modeli

**İlk çekirdek:** Bir hekim, bir yetkili laboratuvar veya klinik ve hizmeti doğrudan satın alan bireysel kullanıcılar.

### Laboratuvar Yaklaşımı

İlk kullanıcılar mevcut sonuçlarıyla gelebilir veya tercih ettikleri yetkili kuruluşta tetkik yaptırabilir. Talep doğrulandıktan sonra fiyat, randevu ve sonuç formatını standartlaştırmak için tercih edilen, münhasır olmayan bir laboratuvar/klinik ortağı belirlenir.

**Aktif pilot laboratuvar:** VitaLab Sağlık Laboratuvarı (Kadıköy / İstanbul)

---

## 📱 İlk MVP

İlk MVP bir mobil uygulama değil, **standartlaştırılmış hizmet akışıdır.**

Basit başvuru sayfası, güvenli bilgi toplama, hekim görüşmesi, laboratuvar yönlendirmesi, dijital değerlendirme raporu ve takip görüşmesi yeterlidir.

---

## 🎯 İlk Doğrulama Hedefi

En az **10 bireysel kullanıcının** hizmet için gerçekten ödeme yapması, süreci tamamlaması ve hizmeti başkasına önermesi.

Rutin kontrol ve kronik takip kullanıcılarının ihtiyaçları ayrı ayrı gözlenir; hekim süresi, kullanıcı başına maliyet, laboratuvar ihtiyacı ve yönlendirme oranı ölçülür.

---

## ⚠️ Sınırlar

HELUNEXA hastanenin yerine geçmez ve bağımsız tanı koymaz. **Klinik karar hekimdedir.**

Amaç; rutin kontrol ve kronik takip sürecini hastane kuyruğundan mümkün olduğunca çıkarmak, hastane gerektiğinde ise kullanıcının doğru yere, doğru bilgiyle ve daha hazırlıklı gitmesini sağlamaktır.

---

## 🗺️ Yol Haritası

### ✅ Faz 1 — Çekirdek MVP (Tamamlandı)
- Hasta kayıt / giriş
- Başvuru formu + demo ödeme
- Hasta paneli
- Hekim / Admin paneli
- Laboratuvar paneli (VitaLab pilot)
- KVKK aydınlatma metni
- Supabase Auth + RLS güvenlik

### ✅ Faz 2 — Uzun Yaşam & Ruh Sağlığı Modülleri (Tamamlandı)
- **Longevity Paneli:** PhenoAge benzeri biyolojik yaş hesaplama
- **Psikolojik Destek Paneli:** GAD-7, PHQ-9, PSS-10, WHO-5 testleri + bileşik skor

### 🚧 Faz 3 — Planlanan
- E-posta bildirimleri (Resend API)
- PDF rapor çıktısı
- Çoklu laboratuvar desteği (`lab_id` + hasta seçim)
- Grafik geçmiş takip (Chart.js)
- Gerçek ödeme entegrasyonu (iyzico)
- Mobil PWA

### 🔮 Faz 4 — Uzun Vadeli
- **HELUNEXA Workplace** — Kurumsal çalışan sağlığı kanalı
- **HomeCare-AI-CDSS** — Klinik karar destek modülü

---

## 🛠️ Teknik Altyapı

| Katman | Teknoloji |
|--------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Backend** | Supabase (PostgreSQL + Auth + Storage) |
| **Hosting** | GitHub Pages |
| **CDN** | jsDelivr (Supabase JS) |
| **E-posta** | Resend API (planlandı) |
| **Ödeme** | iyzico (demo aşamasında) |

---

## 🔐 Güvenlik

- **Row Level Security (RLS):** Her kullanıcı sadece kendi verisini görür
- **Rol Bazlı Erişim:** Admin / Hekim / Laboratuvar / Hasta
- **Supabase Auth:** E-posta + şifre
- **HTTPS:** GitHub Pages üzerinden otomatik
- **KVKK Uyumlu:** Aydınlatma metni + açık rıza

### Rol Yapısı

| Rol | Panel | Yetki |
|-----|-------|-------|
| **Hasta** | `hasta-panel.html` | Kendi başvurularını görür |
| **Hekim** | `admin.html` | Tüm başvuruları görür, değerlendirir |
| **Admin** | `admin.html` | Hekim + kullanıcı yönetimi |
| **Laboratuvar** | `lab.html` | Sonuç yükler, numune işaretler |

---

## 📁 Dosya Yapısı
HELUNEXA/
├── index.html → Ana sayfa (landing)
├── hasta-kayit.html → Hasta kayıt
├── hasta-giris.html → Hasta giriş
├── hasta-panel.html → Hasta paneli
├── basvuru.html → Başvuru formu + demo ödeme
├── admin.html → Hekim / Admin paneli
├── lab.html → Laboratuvar paneli (VitaLab)
├── longevity.html → Longevity / Biyolojik yaş paneli
├── psikolojik.html → Psikolojik destek paneli
├── kvkk.html → KVKK aydınlatma metni
├── ornek-tahlil-sonuc.html → Örnek lab sonucu şablonu
├── logo.png → Logo
├── favicon.ico → Favicon
├── favicon-16x16.png → 16x16 favicon
├── favicon-32x32.png → 32x32 favicon
├── apple-touch-icon.png → Apple touch icon
├── android-chrome-192x192.png → Android ikonu
├── android-chrome-512x512.png → Android ikonu
├── site.webmanifest → PWA manifest
└── README.md → Bu dosya

---

## 🗄️ Veritabanı Şeması

### Supabase Tabloları

| Tablo | Açıklama |
|-------|----------|
| `auth.users` | Supabase otomatik kullanıcı tablosu |
| `user_roles` | Rol tanımları (admin/doctor/lab/patient) |
| `applications` | Hasta başvuruları |
| `longevity_results` | Longevity hesaplama sonuçları |
| `psych_results` | Psikolojik test sonuçları |

### Storage Bucket

| Bucket | Açıklama |
|--------|----------|
| `test-results` | Hasta tahlilleri + lab sonuçları |

---

## 🚦 Kurulum (Geliştirici için)

### 1. Supabase Projesi Oluştur
- https://supabase.com → yeni proje
- URL + Anon Key'i al

### 2. Tabloları Oluştur
- SQL Editor'de migration'ları çalıştır
- `user_roles`, `applications`, `longevity_results`, `psych_results`

### 3. RLS Policy'leri Ayarla
- Her tablo için `auth.uid() = user_id` policy'si

### 4. Storage Bucket
- `test-results` bucket oluştur (public read, authenticated write)

### 5. Auth URL Configuration
- **Site URL:** `https://KULLANICI.github.io/REPO`
- **Redirect URLs:** `https://KULLANICI.github.io/REPO/**`

### 6. HTML Dosyalarını Güncelle
- `SUPABASE_URL` ve `SUPABASE_ANON_KEY` değerlerini tüm HTML'lerde güncelle

### 7. GitHub Pages Aktifleştir
- Settings → Pages → `main` branch → root

---

## 📄 Lisans

Bu proje **özel mülkiyet** altındadır. Tüm hakları saklıdır.

---

## 📞 İletişim

- **E-posta:** info@helunexa.com
- **Web:** www.helunexa.com
- **GitHub:** github.com/neslihanakgul6116/helunexa

---

**© 2026 HELUNEXA. Tüm hakları saklıdır.**