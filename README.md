# UZBEKISTAN LIFE — avtomatik yangilanishlar

Bu repoda faqat o'yinning **yangilanish fayllari** turadi (o'yin kodlari bu yerda emas).
O'yin (APK/EXE) har ochilganda `versiya.json` ni tekshiradi va yangisi bo'lsa
`v<N>_windows.pck` yoki `v<N>_android.pck` ni yuklab oladi. Keyingi ochilishda yangilanish qo'llanadi.

| Maydon | Ma'nosi |
|---|---|
| `base` | Qaysi APK/EXE uchun. O'yindagi `BASE` dan farq qilsa — yangi APK/EXE o'rnatish kerak |
| `version` | Yangilanish raqami (oshib boradi) |
| `notes` | Nima o'zgargani — o'yinda ko'rsatiladi |
| `files` | Platformalar bo'yicha fayl nomi va `sha256` (buzilgan fayl qo'llanmaydi) |

Har bir yangilanish bazadan beri bo'lgan **barcha** o'zgarishlarni o'z ichiga oladi.

O'yin modellari va animatsiyalar (Mixamo) shu fayllar ichida faqat o'yinning bir qismi sifatida tarqatiladi.
