#Minecraft предметы и блоки

##Подключение

Скачать файлы c расширением .css и .png нужных вам модов.
Подключить .css файлы к html странице подобным образом:

```html
<link rel="stylesheet" href="blocks_items.css" />
```

##Использование

```html
<span class="item item_ID item_ID_DATA"></span>
```

ID - id предмета

DATA - damage предмета

Т.к. один и тот же предмет в логах может принимать разные параметры DATA, нужно одновременно использовать и ```item_ID``` и ```item_ID_DATA```

###Пример

```html
<span class="item item_264 item_264_0"></span>
<span class="item item_5 item_5_1"></span>
```

![иконки алмаза и досок](http://i.imgur.com/TSJnbXb.png)