# XiaoAutoLingo — Privacy Policy / Політика конфіденційності

_Last updated: 11 November 2026 (ML Kit diagnostics)_

XiaoAutoLingo (package `link.xiaodroid.xiaoautolingo`) translates the Chinese labels of the Xiaomi car app (`com.mi.car.mobile`) on your phone screen. XiaoAutoLingo is an independent app and is not affiliated with Xiaomi.

## What the app accesses
- **Accessibility service.** When you turn it on, the service reads the visible labels of the Xiaomi car app only (the service is limited to `com.mi.car.mobile`) and draws translations over them in its own window. It does not read other apps, does not perform actions for you and does not collect what you type.
- **Screen captures.** Where the Xiaomi car app does not report where a label is (Flutter screens, text inside pictures), the service takes a capture of the screen while the Xiaomi car app is in front and recognizes the text on the phone (Google ML Kit, on-device). Captures are processed in memory and immediately discarded; they are never saved or sent.

## What is sent or collected
- **Labels, screen captures and translations never leave the phone.** Translation is done by a built-in dictionary and by Google ML Kit on the device.
- The app downloads the ML Kit translation language pack from Google servers once.
- **Google ML Kit diagnostics.** Google ML Kit, the on-device library the app uses for text recognition and translation, may send Google anonymous diagnostic information (device model, Android version, ML Kit version, performance and error data) to keep the library working. It does not include labels, captures or translations. See Google's ML Kit terms: https://developers.google.com/ml-kit/terms
- The developer receives no data. The app has no accounts, no advertising and no tracking of its own. Translations it has already made are stored only in the app's private storage on your phone and are deleted when you uninstall the app.

## Your control
Turn the service off at any time in Android Settings → Accessibility → XiaoAutoLingo, or with the switch in the app. Uninstalling removes all app data.

## Contact
xiaodroidlink@lifestyle.salon

---

## Українською
XiaoAutoLingo перекладає китайські написи застосунку Xiaomi для машини просто на екрані телефона. Не пов'язано з Xiaomi.
- Служба спеціальних можливостей читає лише видимі написи застосунку Xiaomi для машини і малює переклад у власному вікні. Інші програми не бачить, дій за вас не виконує.
- Де застосунок не повідомляє місця напису, служба робить знімок екрана й розпізнає текст на телефоні (Google ML Kit). Знімок обробляється в пам'яті й одразу відкидається — не зберігається й нікуди не надсилається.
- Написи, знімки й переклади ніколи не залишають телефон. Програма один раз завантажує мовний пакет ML Kit із серверів Google.
- Бібліотека Google ML Kit може надсилати Google анонімну діагностику (модель телефона, версія Android, версія ML Kit, швидкодія й помилки) — без написів, знімків і перекладів. Розробник жодних даних не отримує; акаунтів і реклами немає.
- Вимкнути: Налаштування Android → Спеціальні можливості → XiaoAutoLingo. Видалення програми стирає всі її дані.
