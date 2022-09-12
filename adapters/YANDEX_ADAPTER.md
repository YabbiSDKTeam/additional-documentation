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
// Установите для полноэкранной рекламы
YabbiAds.setCustomParams("yandex_interstitial_id", "YANDEX_INTERSTITIAL_ID");

// Установите для видео с вознаграждением
YabbiAds.setCustomParams("yandex_rewarded_id", "YANDEX_REWARDED_ID");
```

### Unity
```c#
// Установите для полноэкранной рекламы
Yabbi.SetCustomParams("yandex_interstitial_id", "YANDEX_INTERSTITIAL_ID");

// Установите для видео с вознаграждением
Yabbi.SetCustomParams("yandex_rewarded_id", "YANDEX_REWARDED_ID");
```
