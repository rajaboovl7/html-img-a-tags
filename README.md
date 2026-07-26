# HTML img va a teglari mashqi 🖼️🔗

Bu loyiha dasturlashni o'rganish davomida yaratgan mustaqil ishlarimdan biri. Unda rasm joylashtirish (`img`) va sahifalar orasida havola yaratish (`a`) mavzulari amaliyotda o'rganilgan.

---

## 🖼️ 1. `img` tegi

Sahifaga rasm joylashtirish uchun ishlatiladi.

```html
<img src="rasm.jpg" alt="Rasm tavsifi" width="300" height="200">
```

* **`src`** — rasm fayli manzili (yo'li yoki havolasi)
* **`alt`** — rasm yuklanmasa yoki ko'zi ojiz foydalanuvchilar uchun o'qiladigan matn
* **`width` / `height`** — rasm o'lchamlarini belgilash

---

## 🔗 2. `a` tegi

Boshqa sahifaga yoki manzilga o'tish (havola) uchun ishlatiladi.

```html
<a href="https://example.com" target="_blank">Havola matni</a>
```

* **`href`** — o'tiladigan manzil (URL yoki boshqa sahifa)
* **`target="_blank"`** — havolani yangi oynada ochish
* Rasmni ham havola qilib bo'ladi:

```html
<a href="https://example.com">
    <img src="rasm.jpg" alt="Bosiladigan rasm">
</a>
```

---

## 🛠 Ishlatilgan texnologiyalar

- **HTML5** — rasm va havola elementlarini joylashtirish uchun

## 📌 Loyiha haqida

Bu — HTML'da rasm (`img`) va havola (`a`) teglarining asosiy xossalarini mashq qilish uchun qilingan loyiha. Kelajakda JavaScript o'rganilganda, rasm va havolalarga dinamik funksiyalar ham qo'shiladi.
