---
cover: .gitbook/assets/f89e3a1a566aab1ccf2d4048e4d34c05.jpg
coverY: 0
title: Admin 'Tavria'
---

# Admin 'Tavria'

{% table %}

---

*  {% colwidth=[792] isHeader=true %}

   <p><strong>Active Directory</strong> (Центр администрирования) mmc (Добавить оснастку) \
   Пользователи и компьютеры\
   ***\
   <strong><code>mstsc.exe</code></strong> <strong>--</strong> Удаленный рабочий стол (WIN + R (Выполнить))</p><p><code>terminal-sgp</code>  (ОТГР сети) <strong>--</strong> Удаленный рабочий стол\
   <strong><code>taskmgr.exe</code> --</strong> Диспетчер задач (WIN + R / C:\\Windows<strong>System32</strong>)</p><p><code>\\printserv</code>  (<em>в проводнике</em>) <strong>--</strong> Принтеры сети\
   ***\
   \[<code>password Розница</code>\]  --  Администратор / 9898bfg</p><p>\[<code>password user</code>\]  --  sspolushin / 548741qqZ\
   \[<code>password user</code>\]  --  aibabitskyi / Westimer1\
   <mark style=«color:orange;»><strong>\[</strong><strong><code>default password</code></strong><strong>\]  --  123456Ss</strong></mark></p>

---

*  {% colwidth=[792] %}

   <p><code>\\10.10.2.123\\storage</code>\
   dc.tavria-rus.ru\\aibabitskyi <strong>--</strong> We7timer1</p>

{% /table %}

### <Tavria>

-  [Ссылка для удаленного доступа](https://rds.tavria-rus.ru/RDWeb/Pages/ru-RU/Default.aspx) 

-  [Ссылка на панель управления](https://cloud.tavria-rus.ru/index.php/apps/dashboard/) (Админ)

-  [Ссылка на почту](https://mail.tavria-rus.ru/)

---

В случае когда имеются сложности в удаленными раб столами или в политики админ - лучшее решение это ребут компа и обновление политик (через CMD) - `gpupdate /force`



<details>

<summary>Не работает сканер</summary>

-  ПРОВЕРИТЬ ЧТО НЕТ ДРУГИХ ЛОКАЛЬНЫХ СЕАНСОВ НА КОМПЬЮТЕРЕ (чтобы порт не был занят другой сессией)



-  Удалить всё оборудование из обработки «Сервис» -> «Торговое оборудование» -> «Подключение и настройка торгового оборудования» -> «Сканеры штрихкода»



-  Добавить сканер штрихкода в справочник «Операции» -> «Справочник» -> «Подключаемое оборудование» -> 3а) Тип - Сканеры штрихкода, Обработчик драйвера - 1С: Сканеры штрихкода, Рабочее место - выбирается автоматически. 3b) Настройка нового сканера - режим работы КЛАВИАТУРА

</details>



<details>

<summary>аууу</summary>

-  111



-  222



-  333

</details>