# Рекламный адаптер для Mintegral

## Подключение рекламы
1. Зарегестрируйтесь в личном кабинете паблишера на сайте - <a href="https://adv.mintegral.com/" target="_blank">https://adv.mintegral.com/</a>.
2. Добавьте приложение, в котором хотите использовать адаптер.

Наше SDK поддерживает 2 типа рекламы.
* **Полноэкранная реклама**
* **Видео с вознаграждением**

Добавьте нужные рекламный блоки.

Каждый рекламный блок имеет свой идентификатор.
Добавьте его в кастомные параметры SDK.

### Android
```java
// Установите для показа рекламы от Mintegral
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralAppID, "замените_на_свой_id");
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralApiKey, "замените_на_свой_id");
    
// Установите для показа полноэкранной рекламы Mintegral
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralInterstitialPlacementId, "замените_на_свой_id");
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralInterstitialUnitId, "замените_на_свой_id");
    
// Установите для показа рекламы с вознаграждением Mintegral
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralRewardedPlacementId, "замените_на_свой_id");
YabbiAds.setCustomParams(YbiAdaptersParameters.mintegralRewardedUnitId, "замените_на_свой_id");
```

### iOS
```swift
// Установите для показа рекламы от Mintegral
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralAppID, "замените_на_свой_id")
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralApiKey, "замените_на_свой_id")
    
// Установите для показа полноэкранной рекламы Mintegral
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralInterstitialPlacementId, "замените_на_свой_id")
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralInterstitialUnitId, "замените_на_свой_id")
    
// Установите для показа рекламы с вознаграждением Mintegral
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralRewardedPlacementId, "замените_на_свой_id")
YabbiAds.setCustomParams(YBIAdaptersParameters.mintegralRewardedUnitId, "замените_на_свой_id")
```

### Unity

```csharp
// Установите для показа рекламы от Mintegral
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralAppID, "вставьте_свой_id");
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralApiKey, "вставьте_свой_id");
    
// Установите для показа полноэкранной рекламы Mintegral
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralInterstitialPlacementId, "вставьте_свой_id");
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralInterstitialUnitId, "вставьте_свой_id");
    
// Установите для показа рекламы с вознаграждением Mintegral
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralRewardedPlacementId, "вставьте_свой_id");
Yabbi.SetCustomParams(YbiAdaptersParameters.mintegralRewardedUnitId, "вставьте_свой_id");
```