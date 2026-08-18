# Grav Admin2 Turkish Localization

**Turkish localization for the Grav CMS Admin2 administration panel.**

**Grav CMS Admin2 yönetim paneli için Türkçe yerelleştirme.**

---

## 🇬🇧 English

### About

This repository provides a Turkish localization file for the **Grav CMS Admin2** administration panel.

The translation was created to provide a fully Turkish administrative interface for users who prefer to manage their Grav CMS websites in Turkish.

The localization is provided as a standalone `tr-TR.yaml` language file and can be installed without modifying the Admin2 source code.

### Compatibility

* **Grav CMS:** `>= 2.0.0`
* **Admin2:** `>= 2.0.0`
* **Language:** Turkish (`tr-TR`)
* **File format:** YAML

> **Important:** This localization is intended for the modern Grav Admin2 panel used with Grav 2.x. It is not intended for the legacy/classic Grav Admin plugin and may not work with Grav 1.x.

### Installation

Copy the following file into your Grav installation:

```text
user/plugins/admin2/languages/tr-TR.yaml
```

The final directory structure should look like:

```text
user/
└── plugins/
    └── admin2/
        └── languages/
            └── tr-TR.yaml
```

No modification to the Admin2 source code is required.

### Enable Turkish Language

After copying the file:

1. Log in to the Grav Admin2 panel.
2. Open **Settings**.
3. Find **Admin Language**.
4. Select **Türkçe (TR)**.
5. Save the settings if required.
6. Reload the administration panel.

Admin2 detects language files placed in its `languages/` directory through Grav's standard language pipeline.

### Technical Notes

Admin2 uses Grav's language system and supports modern ICU-based translations.

Translation files can contain:

* Standard Grav translation keys
* Admin2-specific translation keys
* ICU MessageFormat strings
* Placeholders
* Pluralization and select expressions where applicable

The Turkish localization follows the existing Admin2 translation structure and key names so that the original Admin2 source does not need to be modified.

### Screenshot

Example of the Turkish Admin2 interface:

![Grav Admin2 Turkish Localization](screenshots/admin2-turkish.png)

### Project Status

This is a community-maintained Turkish localization.

The translation is provided as a separate language file so it can be installed independently and updated without modifying the Admin2 source code.

### Contributing

Contributions, corrections and translation improvements are welcome.

If you find:

* a missing translation,
* an incorrect Turkish translation,
* a spelling or terminology issue,
* an untranslated Admin2 string,
* or a compatibility problem,

please open an issue or submit a pull request.

### Upstream Project

This localization is intended for:

**Grav CMS Admin2**

https://github.com/getgrav/grav-plugin-admin2

For the official Admin2 project, documentation, releases and contribution guidelines, please refer to the upstream repository.

---

## 🇹🇷 Türkçe

### Hakkında

Bu repository, **Grav CMS Admin2** yönetim paneli için Türkçe yerelleştirme dosyası sağlar.

Amaç, Grav CMS web sitelerini Türkçe yönetmek isteyen kullanıcılar için Admin2 yönetim panelini mümkün olduğunca tamamen Türkçe hale getirmektir.

Yerelleştirme, bağımsız bir `tr-TR.yaml` dil dosyası olarak hazırlanmıştır ve Admin2 kaynak kodunda herhangi bir değişiklik yapılmasını gerektirmez.

### Uyumluluk

* **Grav CMS:** `>= 2.0.0`
* **Admin2:** `>= 2.0.0`
* **Dil:** Türkçe (`tr-TR`)
* **Dosya formatı:** YAML

> **Önemli:** Bu yerelleştirme Grav 2.x ile kullanılan modern Grav Admin2 paneli için hazırlanmıştır. Eski/klasik Grav Admin eklentisi için tasarlanmamıştır ve Grav 1.x sürümleriyle çalışmayabilir.

### Kurulum

Aşağıdaki dosyayı Grav kurulumunuzdaki ilgili dizine kopyalayın:

```text
user/plugins/admin2/languages/tr-TR.yaml
```

Son klasör yapısı aşağıdaki gibi olmalıdır:

```text
user/
└── plugins/
    └── admin2/
        └── languages/
            └── tr-TR.yaml
```

Admin2 kaynak kodunda herhangi bir değişiklik yapılmasına gerek yoktur.

### Türkçe Dilini Etkinleştirme

Dosyayı kopyaladıktan sonra:

1. Grav Admin2 yönetim paneline giriş yapın.
2. **Ayarlar** bölümünü açın.
3. **Yönetim Dili** seçeneğini bulun.
4. **Türkçe (TR)** seçeneğini seçin.
5. Gerekirse ayarları kaydedin.
6. Yönetim panelini yeniden yükleyin.

Admin2, `languages/` dizinine yerleştirilen dil dosyalarını Grav'ın standart dil sistemi üzerinden algılar.

### Teknik Bilgiler

Admin2, Grav'ın dil altyapısını kullanır ve modern ICU tabanlı çevirileri destekler.

Dil dosyaları aşağıdaki yapıların kullanılmasına izin verir:

* Standart Grav çeviri anahtarları
* Admin2'ye özel çeviri anahtarları
* ICU MessageFormat ifadeleri
* Değişkenler ve placeholder'lar
* Gerektiğinde çoğul ifadeler ve select yapıları

Türkçe yerelleştirme, mevcut Admin2 çeviri yapısı ve anahtar isimleri korunarak hazırlanmıştır. Böylece Admin2 kaynak kodunda değişiklik yapılmasına gerek kalmaz.

### Ekran Görüntüsü

Türkçeleştirilmiş Grav Admin2 yönetim panelinden örnek:

![Grav Admin2 Türkçe Yerelleştirme](screenshots/admin2-turkish.png)

### Proje Durumu

Bu proje topluluk tarafından geliştirilen ve sürdürülen bir Türkçe yerelleştirmedir.

Çeviri bağımsız bir dil dosyası olarak sunulmaktadır. Böylece Admin2 kaynak koduna müdahale edilmeden kurulabilir ve güncellenebilir.

### Katkıda Bulunma

Katkılar, düzeltmeler ve çeviri geliştirmeleri memnuniyetle karşılanır.

Aşağıdaki durumlardan birini fark ederseniz issue açabilir veya pull request gönderebilirsiniz:

* eksik bir çeviri,
* hatalı Türkçe çeviri,
* yazım veya terminoloji problemi,
* İngilizce kalmış Admin2 metni,
* uyumluluk problemi.

### Kaynak Proje

Bu yerelleştirme aşağıdaki resmi proje için hazırlanmıştır:

**Grav CMS Admin2**

https://github.com/getgrav/grav-plugin-admin2

Resmî Admin2 projesi, güncel sürümler, dokümantasyon ve katkı kuralları için upstream repository'yi takip edebilirsiniz.

---

## License

This repository contains a localization file intended for use with the Grav CMS Admin2 project.

Please refer to the upstream Admin2 project for the applicable project license and licensing information:

https://github.com/getgrav/grav-plugin-admin2

---

## Acknowledgements

Thanks to the **Grav CMS** and **Admin2** contributors for the open-source project and its localization infrastructure.

Türkçe yerelleştirmenin hazırlanmasına olanak sağlayan Grav CMS ve Admin2 geliştiricilerine ve katkıda bulunan topluluğa teşekkürler.
