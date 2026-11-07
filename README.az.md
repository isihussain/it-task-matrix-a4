# 📋 İT Layihə Tapşırıq və Kritiklik Səviyyəsi Şablonu (A4 Çap)

Hər hansı bir proqram təminatı / İT layihəsində **FRONTEND (Müştəri Tərəfi / UI)** və **ADMIN & BACKEND (İdarəetmə Paneli, API, DB və Servislər)** işlərini əhəmiyyət dərəcələrinə görə təsnif etmək, komanda daxilində tapşırıq bölgüsü aparmaq və **A4 qara-ağ** çap alıb üzərində işləmək üçün hazırlanmış veb tətbiqi və çap şablonu.

[ **English** ](README.md) | [ **Türkçe** ](README.tr.md) | [ **Русский** ](README.ru.md) | [ **Azərbaycan** ]

**Canlı Demo:** [https://isihussain.github.io/it-task-matrix-a4/](https://isihussain.github.io/it-task-matrix-a4/)

---

## 🔗 Əlaqəli Layihələr

- **[Monthly Project & Calendar Planner (Printable A4)](https://github.com/isihussain/monthly-project-planner-a4)** — Minimalist, tonerə qənaət edən, tək səhifə A4 aylıq layihə və təqvim planlayıcısı. [Canlı Demo](https://isihussain.github.io/monthly-project-planner-a4/)

---

## ✨ Xüsusiyyətlər

- 🖨️ **A4 Qara-Ağ Çap Optimizasiyası:** Toner və mürəkkəb israfının qarşısını alan, fotokopidə solmayan yüksək kontrastlı dizayn (`@page { size: A4 portrait; margin: 0; }`).
- 🌐 **4 Dil Dəstəyi (i18n):** **Azərbaycan dili**, **English**, **Türkçe** və **Русский** arasında bir kliklə dərhal keçid.
- ✏️ **Birbaşa Brauzerdə Redaktə:** Layihə adı, sprint, tarixlər, tapşırıqlar, məsullar və qiymətləndirmələr birbaşa kliklə-redaktə et məntiqi ilə işləyir.
- 💾 **Avtomatik Yaddaş Saxlanması (LocalStorage):** Səhifəni bağlasanız və ya yeniləsəniz belə daxil etdiyiniz məlumatlar itmir.
- 📦 **JSON İdxal və İxrac (Export / Import):** Fərqli layihələriniz üçün şablonları JSON formatında yaddaşda saxlaya, komanda yoldaşlarınızla bölüşə bilərsiniz.
- 📑 **Çoxlu Görünüş Rejimləri:**
  - **Hamısı (2 Səhifə Ön-Arxa):** Səhifə 1: FRONTEND | Səhifə 2: ADMIN & BACKEND
  - **Yalnız Frontend:** Müştəri komandası üçün ayrılmış 1 səhifəlik vərəq
  - **Yalnız Admin & Backend:** Server və verilənlər bazası komandası üçün 1 səhifəlik vərəq
  - **[Kompakt Tək Səhifə](tek_sayfa_kompakt.html):** Hər iki bölməni tək bir A4 kağıza sığdıran gündəlik standup versiyası.
- 🎯 **Dinamik Prioritet Dövrü:** Tapşırığın yanındakı `P0`, `P1`, `P2`, `P3` rozetlərinə klikləyərək təcililik dərəcəsini dəyişə bilərsiniz.
- ✍️ **Boş / Qələmlə Doldurulan Rejim:** Tək kliklə tapşırıq sətirlərini nöqtəli əl yazısı formatına çevirə bilərsiniz.
- 🔤 **Medeo Tipoqrafiya Standartları:** Layihəyə yerləşdirilmiş yerli `Medeo Sans`, `Medeo Sans Display` və `Medeo Mono` şrift dəstəyi.

---

## 🚦 Kritiklik Səviyyələri (Priority Scale)

| Rozet | Kritiklik | Təsvir və Əhatə Dairəsi | İcra Müddəti (SLA) |
| :---: | :--- | :--- | :--- |
| `[■ P0]` | **Bloker / Təcili** | İstehsalı dayandıran, təhlükəsizlik/auth boşluğu, məlumat itkisi riski, əsas axın kilidlənib. | Dərhal / Həmin gün |
| `[▣ P1]` | **Yüksək (High)** | MVP üçün məcburi əsas axınlar, ilkin CRUD, əsas API inteqrasiyaları. | Mövcud Sprint / 24–48 Saat |
| `[□ P2]` | **Orta (Medium)** | İkinci dərəcəli funksiyalar, axtarış/filtrləmə, validasiya, mobil uyğunluq. | Planlaşdırılmış Sprint |
| `[◌ P3]` | **Aşağı (Low)** | Kosmetik düzəlişlər, mikro-animasiyalar, əlavə istəklər (nice-to-have). | Backlog |

---

## 🖨️ A4 Çap Təlimatı

1. `index.html` faylını (və ya [Canlı Demo](https://isihussain.github.io/it-task-matrix-a4/) ünvanını) brauzerinizdə açın.
2. İstədiyiniz dili (`AZ`, `EN`, `TR`, `RU`) və səhifə görünüşünü seçin.
3. Səhifənin yuxarısındakı **"A4 Çap Et / PDF Saxla"** düyməsinə klikləyin (və ya <kbd>Ctrl</kbd> + <kbd>P</kbd>).
4. Çap parametrləri pəncərəsində:
   - **Hədəf:** Çap cihazınız və ya *"PDF kimi saxla"*
   - **Vərəq Ölçüsü:** `A4`
   - **Orientasiya:** `Portret (Şaquli)`
   - **Kənar Boşluqları:** `Yoxdur (None)` və ya `Defolt`
   - **Arxa Plan Qrafikası:** `Aktiv`

---

## 📄 Lisenziya

Bu layihə [MIT Lisenziyası](LICENSE) əsasında açıq mənbəli olaraq təqdim edilmişdir.
