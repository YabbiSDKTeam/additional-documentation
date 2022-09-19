# Web SDK

## Установка

Для установки добавьте добавьте следующий скрипт в конце элемента body вашего сайта.

```html
<body>

     <!-- Тут находится код вашего сайта -->

    <script src="//ssp.bestssp.com/s.js?p=<ID>"></script>
</body>
```

Замените `<ID>` на ваш идентификатор.

Либо произведите установка через *JavaScript*. Для этого добавьте следующий код в исполняемом *JavaScript* файле.

```js
let item = document.createElement("script");
item.type = "text/javascript";
item.src = "//ssp.bestssp.com/s.js?p=<ID>";
let body = document.querySelector('body')
body.append(item);
```

Замените `<ID>` на ваш идентификатор.

## Установка для Construct 3

1. Перейдите в панель *Проект*. Если панель не активна, вы можете открыть ее перейдя в *Меню* - *Вид* - *Бар*.
2. Щёлкните правой ПКМ на папке *Скрипты*. Выберите *Добавить новый скрипт*.
3. Добавьте следующий код в функцию *OnBeforeProjectStart*.
4. Замените `<ID>` на ваш идентификатор.

```js
async function OnBeforeProjectStart(runtime)
{
	let item = document.createElement("script");
	item.type = "text/javascript";
	item.src = "//ssp.bestssp.com/s.js?p=<ID>";
	let body = document.querySelector('body')
	body.append(item);
	
	runtime.addEventListener("tick", () => Tick(runtime));
}
```
