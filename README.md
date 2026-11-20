# Uy mashq — APK

## 1. Imzo (bir marta)
Har bir APK bir xil kalit bilan imzolanadi. Shuning uchun yangi versiya eskisining ustiga o'rnatiladi va belgilangan kunlar, vazn yozuvlari o'chmaydi.

GitHub repo → **Settings → Secrets and variables → Actions → New repository secret**.
`IMZO_MAXFIY.txt` dagi 4 ta secretni qo'shing: KEYSTORE_BASE64, KEYSTORE_PASSWORD, KEY_ALIAS, KEY_PASSWORD.
`uy-mashq.jks` va parollarni repoga YUKLAMANG, alohida xavfsiz joyda saqlang.

## 2. APK
1. Shu papkadagi hamma narsani (yashirin `.github` papkasi bilan) repoga yuklang.
2. **Actions** → «APK yig'ish» (5–8 daqiqa).
3. **Artifacts** → `uy-mashq-apk-v1.0.N` → `uy-mashq.apk` ni telefonga o'rnating.

## 3. Yangilash
Faqat `www/index.html` ni almashtiring. Yangi APK ni o'chirmasdan, ustidan o'rnating: «Yangilash» chiqadi, ma'lumotlar saqlanadi.
Ma'lumot kaliti `uyMashq2` hech qachon o'zgartirilmaydi.
