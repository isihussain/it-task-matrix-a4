# 📋 IT Proje Görev ve Kritiklik Seviyesi Takip Şablonu (A4 Siyah-Beyaz Baskı)

Herhangi bir yazılım/IT projesinde **FRONTEND (İstemci / UI)** ve **ADMIN & BACKEND (Yönetim Paneli, API, DB & Servisler)** işlerini önem derecelerine göre sınıflandırmak, ekip içi görev dağılımı yapmak ve **A4 siyah-beyaz** çıktı alıp üzerinde çalışmak için tasarlanmış bağımsız web uygulaması ve baskı şablonu.

[ **English** ](README.md) | [ **Türkçe** ] | [ **Русский** ](README.ru.md) | [ **Azərbaycan** ](README.az.md)

**Canlı Demo:** [https://isihussain.github.io/it-task-matrix-a4/](https://isihussain.github.io/it-task-matrix-a4/)

---

## 🔗 İlgili Projeler

- **[Monthly Project & Calendar Planner (Printable A4)](https://github.com/isihussain/monthly-project-planner-a4)** — Minimalist, toner tasarruflu, tek sayfa A4 aylık proje ve takvim planlayıcı. [Canlı Demo](https://isihussain.github.io/monthly-project-planner-a4/)

---

## ✨ Özellikler

- 🖨️ **A4 Siyah-Beyaz Baskı Optimizasyonu:** Toner ve mürekkep israfını önleyen, fotokopide solmayan yüksek kontrastlı tasarım (`@page { size: A4 portrait; margin: 0; }`).
- 🌐 **4 Dil Desteği (i18n):** **Türkçe**, **English**, **Русский** ve **Azərbaycan dili** arasında tek tıkla anında geçiş.
- ✏️ **Doğrudan Tarayıcıda Düzenleme:** Proje adı, sprint, tarihler, görevler, sorumlular ve eforlar doğrudan tıkla-düzenle mantığıyla çalışır.
- 💾 **Otomatik Tarayıcı Kaydı (LocalStorage):** Sayfayı kapatsanız veya yenileseniz dahi girdiğiniz veriler kaybolmaz.
- 📦 **JSON İçe / Dışa Aktarma (Export / Import):** Farklı projeleriniz için şablonları JSON olarak kaydedebilir, ekip arkadaşlarınızla paylaşabilirsiniz.
- 📑 **Çoklu Görünüm Modu:**
  - **Tümü (2 Sayfa Önlü-Arkalı):** Sayfa 1: FRONTEND | Sayfa 2: ADMIN & BACKEND
  - **Sadece Frontend:** Yalnızca istemci ekibi için 1 sayfa
  - **Sadece Admin & Backend:** Yalnızca sunucu ve yönetim paneli ekibi için 1 sayfa
  - **[Kompakt Tek Sayfa](tek_sayfa_kompakt.html):** Her iki bölümü tek bir A4 kağıda sığdıran günlük standup/masaüstü sürümü.
- 🎯 **Dinamik Öncelik Döngüsü:** Görev yanındaki `P0`, `P1`, `P2`, `P3` rozetlerine tıklayarak öncelik derecesini değiştirebilirsiniz.
- ✍️ **Boş / Kalemle Doldurulabilir Şablon Modu:** Tek tıkla görev satırlarını noktalı el yazısı formatına çevirebilirsiniz.
- 🔤 **Medeo Tipografi Standartları:** Proje içine gömülü yerel `Medeo Sans`, `Medeo Sans Display` ve `Medeo Mono` font desteği.

---

## 🚦 Kritiklik Seviyeleri (Priority Scale)

Siyah-beyaz baskıda tonların birbirine karışmaması için sembolik ve yüksek kontrastlı rozetler kullanılmıştır:

| Rozet | Kritiklik | Tanım & Kapsam | Eylem Süresi (SLA) |
| :---: | :--- | :--- | :--- |
| `[■ P0]` | **Blocker / Acil Kritik** | Canlıyı durduran, güvenlik/auth açığı, veri kaybı riski, ana akış tıkalı. | Derhal / Aynı Gün |
| `[▣ P1]` | **Yüksek (High)** | MVP için zorunlu çekirdek akışlar, birincil CRUD, ana API entegrasyonu. | Mevcut Sprint / 24–48 Saat |
| `[□ P2]` | **Orta (Medium)** | İkincil işlevler, arama/filtreleme, validasyon, responsive uyumluluk. | Planlı Sprint Akışı |
| `[◌ P3]` | **Düşük (Low)** | Kozmetik detaylar, mikro-animasyonlar, nice-to-have özellikler. | Backlog |

---

## 🖨️ A4 Çıktı Alma Rehberi

1. `index.html` dosyasını (veya [Canlı Demo](https://isihussain.github.io/it-task-matrix-a4/) adresini) tarayıcınızda açın.
2. İstediğiniz dili (`TR`, `EN`, `RU`, `AZ`) ve sayfa görünümünü seçin.
3. Sayfa üstündeki **"A4 Yazdır / PDF Olarak Kaydet"** butonuna tıklayın (veya <kbd>Ctrl</kbd> + <kbd>P</kbd>).
4. Yazıcı ayarları penceresinde:
   - **Hedef:** Yazıcınız veya *"PDF Olarak Kaydet"*
   - **Sayfa Boyutu:** `A4`
   - **Düzen:** `Dikey (Portrait)`
   - **Kenar Boşlukları:** `Yok (None)` veya `Varsayılan`
   - **Arka Plan Grafikleri:** `İşaretli (Açık)`

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak sunulmuştur.
