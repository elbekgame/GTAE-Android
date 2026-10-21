GTA E — Android ilova loyihasi (bir telefonda o‘ynash)

HOLATI
- Ilova nomi: GTA E
- Ekran: gorizontal (landscape), to‘liq ekran
- O‘yin: hozircha bitta telefonda, mavjud HTML o‘yin
- Bu ZIP — Android loyiha manbalari; tayyor APK fayli emas.

APK YASASH — KOMPYUTERDA
1. Android Studio o‘rnating va ishga tushiring.
2. ZIPni chiqarib, Android Studio ichida GTAE-Android papkasini Open qiling.
3. Gradle Sync tugashini kuting.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) ni bosing.
5. APK odatda app/build/outputs/apk/debug/app-debug.apk ichida paydo bo‘ladi.
6. APKni telefonga ko‘chirib o‘rnating. Kerak bo‘lsa Android sozlamalarida ushbu manbadan o‘rnatishga ruxsat bering.

FAQAT TELEFONDA
ZArchiver faqat ZIPni chiqaradi; o‘zi APK tuzmaydi. Telefonning o‘zida APK yig‘ish uchun AndroidIDE kabi Android/Gradle loyihasini kompilyatsiya qila oladigan muhit kerak bo‘ladi. Bunday muhitda loyiha papkasini ochib Gradle build qilish kerak. Telefon modeli va Android versiyasiga qarab bu usul ishlamasligi mumkin.

MUHIM
- O‘yin Three.js kutubxonasini CDN orqali yuklaydi, shu sabab o‘yin ishlashi uchun internet kerak.
- Bu versiyada ko‘p o‘yinchili tarmoq rejimi yo‘q; bitta telefonda o‘ynash uchun mo‘ljallangan.
- APK ushbu muhitda kompilyatsiya qilinmadi, chunki Android SDK/Gradle build vositalari mavjud emas.
