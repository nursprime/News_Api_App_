# News_Api_App_
 App containing news pages by categories with kotlin
 
# NewsApp

NewsApp, Kotlin kullanılarak geliştirilmiş, REST API ile haberleri çekip gösteren bir mobil uygulamadır. Kullanıcılar, güncel haberleri kategorilere göre görüntüleyebilir ve detaylarına ulaşabilirler.

## Özellikler

- Güncel haberleri listeleme
- Kategorilere göre filtreleme
- Haber detaylarını görüntüleme

## Kurulum


    ```

1. **Gerekli Bağımlılıkları Yükleyin:**

    Android Studio'da projeyi açın ve `Gradle` senkronizasyonunu yapın.

2. **API Anahtarınızı Ayarlayın:**

    - `local.properties` dosyasını açın veya oluşturun (proje kök dizininde).
    - API anahtarınızı ekleyin:

      ```properties
      NEWS_API_KEY=your_api_key_here
      ```

    - `build.gradle` dosyasında API anahtarını kullanarak ilgili yerleri güncelleyin:

      ```kotlin
      val apiKey = BuildConfig.NEWS_API_KEY
      ```

3. **Uygulamayı Çalıştırın:**

    Uygulamayı başlatın ve ana ekran üzerinden kategorilere göre haberleri görüntüleyin.







 
