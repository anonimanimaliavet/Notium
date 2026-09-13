# Notium — Telefonda otomatik APK oluşturma

Bu projeye GitHub Actions otomatik APK sistemi eklenmiştir.

## Telefonda yapacağın işlem

1. GitHub'da yeni bir repository oluştur: `Notium`
2. Bu ZIP'i açıp içindeki tüm dosyaları repository'ye yükle.
3. GitHub'da **Actions** sekmesine gir.
4. **Notium APK Builder** workflow'unu seç.
5. **Run workflow** düğmesine bas.
6. İşlem tamamlanınca workflow sayfasında **Artifacts → Notium-debug-apk** bölümünden APK'yı indir.
7. APK'yı telefonda açıp kur.

Ayrıca `main` veya `master` dalına her yeni kod gönderildiğinde APK otomatik oluşturulur ve GitHub Releases bölümüne de eklenir.

## Önemli

Bu sistem APK'yı senin telefonunda değil, GitHub'ın ücretsiz Linux sunucusunda derler. Böylece telefona Android Studio kurmana gerek kalmaz.
