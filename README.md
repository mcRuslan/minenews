# MINE NEWS

Android-приложение на Kotlin + Jetpack Compose в блочной эстетике Minecraft.

## Возможности
- Загружает мировые новости из публичной RSS-ленты BBC News.
- Показывает заголовки, описания и даты публикации.
- Открывает оригинальную статью в браузере.
- Обновляет ленту по нажатию кнопки.
- Не требует API-ключа или регистрации.

## Сборка APK
1. Установите Android Studio (JDK 17 и Android SDK Platform 35).
2. Откройте папку `MineNews` в Android Studio.
3. Дождитесь Gradle Sync.
4. Выберите Build → Build Bundle(s) / APK(s) → Build APK(s).
5. APK появится в `app/build/outputs/apk/debug/app-debug.apk`.

Приложение использует Android API и не содержит native-библиотек, поэтому собранный APK подходит для ARM64 (и других Android ABI).

## Источник
BBC News World RSS: https://feeds.bbci.co.uk/news/world/rss.xml
