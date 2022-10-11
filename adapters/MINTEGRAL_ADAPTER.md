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
    YabbiAds.setCustomParams("mintegral_app_id", "замените_на_свой_id");
    YabbiAds.setCustomParams("mintegral_app_key", "замените_на_свой_id");
    
    // Установите для показа полноэкранной рекламы Mintegral
    YabbiAds.setCustomParams("mintegral_interstitial_placement_id", "замените_на_свой_id");
    YabbiAds.setCustomParams("mintegral_interstitial_id", "замените_на_свой_id");
    
    // Установите для показа рекламы с вознаграждением Mintegral
    YabbiAds.setCustomParams("mintegral_rewarded_placement_id", "замените_на_свой_id");
    YabbiAds.setCustomParams("mintegral_rewarded_id", "замените_на_свой_id");
```
