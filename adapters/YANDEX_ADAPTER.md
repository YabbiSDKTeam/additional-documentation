# Рекламный адаптер для Яндекса

## Подключение рекламы
1. Зарегестрируйтесь в личном кабинете паблишера на сайте - <a href="https://partner.yandex.ru" target="_blank">https://partner.yandex.ru</a>.
2. Добавьте приложение, в котором хотите использовать адаптер.

Наше SDK поддерживает 2 типа рекламы.
* **Полноэкранная реклама**
* **Видео с вознаграждением**

Добавьте нужные рекламный блоки.

Каждый рекламный блок имеет свой идентификатор, записанный в формате `R-M-XXXXXX-Y`.
Добавьте его в кастомные параметры SDK.

### Android
```java
// Установите для показа полноэкранной рекламы Яндекса
YabbiAds.setCustomParams(YbiAdaptersParameters.yandexInterstitialID, "замените_на_свой_id");
    
// Установите для показа рекламы с вознаграждением Яндекса
YabbiAds.setCustomParams(YbiAdaptersParameters.yandexRewardedID, "замените_на_свой_id");
```

### iOS
```swift
// Установите для показа полноэкранной рекламы Яндекса
YabbiAds.setCustomParams(YBIAdaptersParameters.yandexInterstitialID, "замените_на_свой_id")

// Установите для показа рекламы с вознаграждением Яндекса
YabbiAds.setCustomParams(YBIAdaptersParameters.yandexInterstitialID, "замените_на_свой_id")
```

### Unity
```csharp
// Установите для показа полноэкранной рекламы Яндекса
Yabbi.SetCustomParams(YbiAdaptersParameters.yandexInterstitialID, "вставьте_свой_id");

// Установите для показа рекламы с вознаграждением Яндекса
Yabbi.SetCustomParams(YbiAdaptersParameters.yandexRewardedID, "вставьте_свой_id");
```
