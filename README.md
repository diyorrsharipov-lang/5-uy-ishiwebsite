# Food Court — Your Food court at home (Figma Concept)

Figma Community fayli (`Food delivery concept`) va `node-id=51-0` (Main page + Style Guide) asosida yaratilgan to'liq responsiv, interaktiv taom yetkazib berish veb-sayti.

## Loyiha xususiyatlari:
- **Dizayn Konsepsiyasi**: Food Court («Your Food court at home»)
- **Asosiy Ranglar & Uslub (Style Guide)**:
  - Brand Yellow: `#FFE245` (Asosiy aksent va harakatga chaqiruvchi tugmalar)
  - Dark Charcoal: `#1C1C24`
  - Soft Gray Background: `#F3F4FB`
  - Badge Colors: Red (`#FF4757`), Green (`#2ECC71`), Amber (`#FFC107`)
  - Shrift: *Plus Jakarta Sans* / *Inter*
- **Bloklar & Sahifalar**:
  1. **Header & Manzil tanlash**:
     - Brend logotipi («FoodCourt at home»)
     - Manzilni o'zgartirish modali (Deliver to: 742 Evergreen Terrace)
     - Qidiruv paneli (Real-time Search)
     - Savatcha hisoblagichi va interaktiv savatcha tugmasi
  2. **Hero Bo'limi**:
     - «Your Food court at home» bosh sarlavhasi
     - Jonli statistika (20m tezkor yetkazish, 4.9 reyting, 45+ oshxona)
     - Maxsus promo-aktsiya nishonlari
  3. **Kategoriyalar filtri**:
     - Burgers, Artisan Pizza, Asian & Bowls, Sushi Rolls, Healthy Greens, Desserts, Smoothies & Drinks
     - Har bir toifaga bosilganda menyu darhol filtrlanadi
  4. **Menyu va Taomlar Gridi**:
     - Yuqori sifatli ishtahaochar fotosuratlar
     - Bestseller, Chef Choice, Healthy, Hot & Spicy teglari
     - Reyting (★ 4.9), tayyorlanish vaqti va narxlar
     - «+ Add» savatchaga qo'shish tugmasi
  5. **Maxsus aksiya (30% chegirma)**:
     - «FOODCOURT30» promokodini bir marta bosishda nusxalash
  6. **Ishlash tizimi (3 oddiy qadam)**:
     - 1. Taomni tanlang
     - 2. Qulay to'lov
     - 3. 20 daqiqada issiq yetkazib berish
  7. **Mobil ilova yuklab olish bloki**:
     - App Store va Google Play havolalari
     - QR kod illyustratsiyasi
  8. **Interaktiv Savatcha (Slide-in Cart Drawer)**:
     - Tanlangan taomlar miqdorini oshirish/kamaytirish (+ / -)
     - Promokod kiritish («FOODCOURT30» orqali -30% hisoblash)
     - Yetkazib berish narxi va jami summani hisoblash
     - Buyurtmani tasdiqlash

## Ishga tushirish:
Sayt hozirda lokal serverda ishlamoqda:
```
http://localhost:3001/
```
To'g'ridan-to'g'ri `index.html` faylini ochishingiz ham mumkin.
Serverni qayta ishga tushirish uchun:
```bash
node server.js
```
