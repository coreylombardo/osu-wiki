# Настройки

![Options menu](img/options_basic-RU.jpg "Меню настроек \(боковая панель\)")

В главном меню нажмите на `Options` или клавишу `O` (или же `Ctrl` + `O`, что работает практически на любом экране), чтобы открыть палень настроек и изменить доступные опции в osu!. После открытия меню настроек можно набрать текст для поиска конкретной опции. Строка поиска дрогнет, если поисковый запрос не имеет результатов.

При изменении опции, имеющей значение по умолчанию, серая вертикальная полоска слева будет светиться жёлтым цветом. Нажав на неё, можно вернуть значние этой опции к значению по умолчанию. 

## Общее

![General icon](img/general-RU.jpg "Иконка раздела «Общее»")

Этот раздел посвящён вашей учётной записи, языковым настройкам, и обновлениям osu!

### Вход

Если вы не вошли в игровой клиент, при запуске автоматически откроется меню настроек, предлагающее залогиниться. Вы можете проигнорировать его, нажав `Esc`, щёлкнув на кнопку «Назад» или перейдя на экран выбора песни. Если вы всё же не залогинишься, клиент пометит вас как «Guest», и вы не сможете получать онлайн-результаты, отправлять результаты или играть в [мультиплеер](/wiki/Client/Interface/Multiplayer).

В этом случае будут показаны эти опции:

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Логин` | Ввод логина вашей учётной записи. | Текст | *(пусто)* |
| `Пароль` | Ввод пароля вашей учётной записи. | Пароль | *(пусто)* |
| `Запомнить логин` | При включении, клиент запомнит введённый вами логин. | Галочка | `Включено` |
| `Запомнить пароль` | При включении, клиент запомнит введённый вами пароль. Это также сохранит ваш вход в клиент.  | Галочка | `Выключено` |
| `Вход` | Войти в систему osu! с указанными учётными данными. Нажатие клавиши `Enter` в формах логина или пароля тоже работает. | Кнопка |  |
| `Зарегистрироваться` | Открывает экран [регистрации](/wiki/Registration) | Кнопка |  |

---

Если вы вошли в учётную запись, вы увидите это:

| Название | Описание | Тип |
| :-- | :-- | :-- |
| `Логин: {логин}` | Показывает пользовательское меню. Подробности см. ниже. | Кнопка |

---

При нажатии на подсказку `Логин: {логин}` появится меню с этими кнопками:

| Название | Описание | Тип |
| :-- | :-- | :-- |
| `1. Открыть профиль` | Посмотреть свой профиль на сайте. | Кнопка |
| `2. Выйти` | Выйти из своей учётной записи в клиенте. | Кнопка |
| `3. Поменять аватарку` | Сменить свою аватарку. Это перенаправит вас на сайт. | Кнопка |
| `4. Отмена` | Закрыть это меню. Также можно нажать `Esc`. | Кнопка |

Вы можете открыть это меню, нажав на свой профиль, где он доступен.

### Язык

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Язык` | Показывает список языков для выбора. | Список |  |
| `Метаданные на языке оригинала` | На экране выбора песни, карты будут отображать свои оригальные или нетранслитерированные метаданные, если имеются. | Галочка | `Выключено` |
| `Использовать в чате старый шрифт` | Меняет новый шрифт в [чате](/wiki/Client/Interface/Chat_console) (Aller) на старый (Tahoma). | Галочка | `Выключено` |

### Обновление

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Ветка обновлений` | Показывает список доступных сборок клиента. | Список | `Стабильная` |
| `У Вас последняя версия osu!` | Нажмите, чтобы заставить игру проверить наличие обновлений и установить их, если они есть. | Кнопка |  |
| `Открыть директорию osu!` | Открывает локальную папку osu!, в которой находятся скины, карты, и т.п. | Кнопка |  |

---

При открытии выпадающего списка `Ветка обновлений` появятся эти опции:

| Название | Описание |
| :-- | :-- |
| `Стабильная` | Стабильная сборка публичного релиза. |
| `Бета` | Тестовая сборка - получает новые фишки раньше, но, возможно, имеет больше багов. |
| `Экспериментальная` | Тестовая сборка - получает новые фишки ещё раньше, но, возможно, имеет ещё больше багов. |

## Графика

![Graphics icon](img/graphics-RU.jpg "Иконка раздела «Графика»")

Этот раздел посвящён внешнему виду клиента, некоторым частям интерфейса, и настройкам графики.

### Обработчик графики

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Ограничение FPS` | Устанавливает ограничение частоты кадров. Подробности см. ниже. | Список | `Optimal` |
| `Счётчик FPS` | Включить счётчик частоты кадров. Он отображается в нижнем правом углу экрана. | Галочка | `Выключено` |
| `Режим совместимости` | Использовать старый рендерер для устаревших компьютеров. Это перезапустит игровой клиент. | Галочка | `Выключено` |
| `Снизить кол-во потерянных кадров` | Настроить графику так, чтобы уменьшить кол-во потерянных кадров. | Галочка | `Выключено` |
| `Обнаруживать снижение производительности` | Игра предупредит вас, если она обнаружит запущенные программы, которые могут отрицательно влиять на её производительность. | Галочка | `Включено` |

---

*Примечание: Когда игровой клиент не выбран в качестве активного окна, ограничение частоты кадров автоматически снижается до 30 кадров в секунду.*\
*Предостережение для пользователей ноутбуков: `Unlimited (gameplay)` может привести к перегреву ноутбука!*
 
При открытии списка `Ограничение FPS` появятся эти опции:

| Название | Описание |
| :-- | :-- |
| `Вертикальная синхронизация` | Ограничивает игровой клиент частотой обновления вашего монитора. Подробности см. ниже. |
| `Power Saving` | Ограничивает игровой клиент удвоенной частотой обновления вашего монитора. |
| `Optimal` | Ограничивает игровой клиент в восемь раз выше частоты обновления вашего монитора, максимум до 960 кадров в секунду. |
| `Нет (во время игры)` | Ограничивает игровой клиент частотой обновления вашего монитора. Подробности см. ниже. |

- Пояснение опции `Вертикальная синхронизация`: Проще говоря, вертикальная синхронизация заставляет игру ждать загрузки всего кадра перед его отображением.
  - Вероятно, вы хотите включить это, если видите «разрывы» экрана (когда нижняя часть игры отстаёт от верхней части).
  - Несмотря на вышеизложенное, это может вызвать задержки или замедления, так как клиент должен ждать загрузки каждого кадра.
- Пояснение опции `Нет (во время игры)`: Эта опция применяется только при игре карты.
  - Когда вы не играете карту, частота кадров ограничена удвоенной частотой обновления вашего монитора, или 240 кадрами в секунду, в зависимости от того, что выше.
  - Эта опция **не рекомендуется**. Использование `Unlimited (gameplay)` может привести к визуальным задержкам.
  - С другой стороны, опция `Optimal` обеспечивает вовсе незаметное изменение системной задержки (как вводной, так и выходной) по сравнению с `Unlimited (gameplay)`.

### Параметры экрана

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Разрешение` | Устанавливает разрешение игрового клиента. Доступные разрешения ограничены тем, что поддерживает ваш монитор/видеокарта. | Список |  |
| `Полноэкранный режим` | Игра будет работать в полноэкранном режиме. Это обычно уменьшает входную задержку. | Галочка | `Включено` |
| `Render at native resolution` | Использует полное собственное разрешение, но при этом игра будет отображаться в меньшей части экрана по центру (леттербоксинг). | Галочка | `Включено` |
| `По горизонтали` | Настраивает горизонтальное смещение для режима леттербоксинга. Появляется только при включении опции `Render at native resolution`. | Ползунок | `0%` |
| `По вертикали` | Настраивает вертикальное смещение для режима леттербоксинга. Появляется только при включении опции `Render at native resolution`. | Ползунок | `0%` |

- Если `Полноэкранный режим` выключен, под ним появится надпись `Running without fullscreen mode will increase your input latency!`.

### Детализация

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Ползущие слайдеры` | Слайдеры будут разворачиваться из своей начальной точки. | Галочка | `Включено` |
| `Фоновое видео` | Разрешает воспроизведение фонового видео во время игры (можно отключить на каждой конкретной карте). | Галочка | `Включено` |
| `Сториборды` | Разрешает воспроизведение сториборда (можно отключить на каждой конкретной карте). | Галочка | `Включено` |
| `Комбо-всплески` | Разрешает отображение комбо-всплесков при достижении рубежа комбо. | Галочка | `Выключено` |
| `Вспышки от нот` | Показывает нежное свечение за каждым хит-результатом. Не отключает освещение во время киая. | Галочка | `Включено` |
| `Эффекты шейдеров` | Display, graphically speaking, concert-type effects. Они могут быть автоматически отключены, если ваш компьютер недостаточно мощный для них. | Галочка | `Выключено` |
| `Сглаживающий фильтр` | Настраивает шейдеры, чтобы они были менее яркими. Это автоматически включит `Эффекты шейдеров`. | Галочка | `Выключено` |
| `Формат скриншотов` | Устанавливает формат скриншотов. | Список | `JPEG (малый размер)` |

### Главное меню

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Включить снег` | Показывать снежные эффекты в главном меню (принудительно включён зимой). | Галочка | `Выключено` |
| `Параллакс` | Show a slight parallax while navigating in-game menus (вне самой игры). | Галочка | `Включено` |
| `Показывать советы` | Show a tip every time you visit the main menu. (Tips are not displayed in the cuttingedge builds.) | Галочка | `Включено` |
| `Включить голосовое приветствие` | Play the "welcome" and "see ya" sounds upon opening and closing the game respectively. | Галочка | `Включено` |
| `Использовать музыкальную тему osu!` | If enabled, the main theme song will play after the game client is opened. Once the song changes, you cannot play it again until the game client has been restarted. | Галочка | `Включено` |
| `Seasonal backgrounds` | Use fanart contest winners as the background in the main menu (and for beatmaps without background images). The images will cycle when the song is changed. | Список | `Sometimes` |

---

При открытии списка `Seasonal backgrounds` появятся эти опции:

| Название | Описание |
| :-- | :-- |
| `Sometimes` | You will see seasonal backgrounds for a few weeks at the beginning of each season. The osu!dev team will choose when they will be removed, replaced with more plain backgrounds you are used to. |
| `Never` | You will never see seasonal backgrounds, and defaults will be used in all cases. |
| `Always` | You will always have the current season's backgrounds. |

### Выбор песни

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Показывать миниатюры` | Display a preview image of each beatmap's background. This requires the selected skin's version to 2.2+. | Галочка | `Включено` |

## Игра

![Gameplay icon](img/gameplay-RU.jpg "Иконка раздела «Игра»")

Этот раздел посвящён настройкам, влияющим на игровой процесс.

### Общее

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Затемнение фона` | Adjust the level of dimming applied to the background and storyboard while playing (can be set per-beatmap). | Ползунок | `80%` |
| `Don't change dim level during breaks` | Disable brightening the dim level during breaks, making the background never visible. | Галочка | `Выключено` |
| `Прогресс` | Configure where and how the song progress bar is displayed. See below for details. | Список | `Справа вверху (круг)` |
| `Шкала точности` | Configure accuracy meter appearing below the beatmap. Note that osu!catch will always use `Цветовую`. | Список | `Отклонение от нуля` |
| `Размер шкалы точности` | Configure size of score meter. | Ползунок | `1x` |
| `Всегда показывать нажимаемые клавиши` | Show the key status overlay even while playing normally. | Галочка | `Выключено` |
| `Показывать первую ноту при игре с хидденом` | When playing with the "hidden" mod, show only the first note's approach circle. | Галочка | `Включено` |
| `Изменять скорость прокрутки в osu!mania в зависимости от BPM карты` | Adjust speed of osu!mania's scrolling depending on the BPM of the beatmap. | Галочка | `Выключено` |
| `Своя скорость для каждой карты osu!mania` | Remember the scroll speed you had set per-beatmap. | Галочка | `Выключено` |

---

If you open the dropdown list for `Progress Display`, you will be presented with these options:

| Название | Описание |
| :-- | :-- |
| `Справа вверху (круг)` | Use a pie chart to show the remaining duration before the song starts and the time left before completion. This is seen left of the accuracy. |
| `Справа вверху (полоса)` | Use a short horizontal bar to display the time left before completion. This is seen underneath the score but above the accuracy. |
| `Справа внизу` | Use a short horizontal bar to display the time left before completion. This is seen in the bottom-right corner. |
| `Внизу (полоса)` | Use a long horizontal bar to display the time left before completion. This is seen on the bottom. |

---

If you open the dropdown list for `Шкала точности`, you will be presented with these options:

| Название | Описание |
| :-- | :-- |
| `Отключена` | Do not use a meter to display the player's hit timing. |
| `Цветовая` | Use coloured blocks to display hit timing. (osu!catch will always use this if `Hit error` is selected.) |
| `Отклонение от нуля` | Use a meter to display hit timing. This shows if the player had hit too early or too late. |

### Выбор песни

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Показывать карты от` | This adjusts the **lowest** difficulty beatmap that will be displayed in song select. | Ползунок | `0 звёзд` |
| `до` | This adjusts the **highest** difficulty beatmap that will be displayed in song select. | Ползунок | `10+ звёзд` |

## Звук

![Audio icon](img/audio-RU.jpg "Иконка раздела «Звук»")

Этот раздел посвящён опциям, связанным со звуком.
### Устройства

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Устройство вывода` | Select the preferred output device for audio. (Options given are based on what your computer reports.) | Список | `Default` |
| `Audio compatibility mode` | Uses the legacy audio engine which has higher latency but is more compatible. | Галочка | `Выключено` |

### Volume

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Общее` | Controls the main volume. | Ползунок | `100%` |
| `Музыка` | Controls the music volume. | Ползунок | `80%` |
| `Эффекты` | Controls the hitsounds and in-game sounds. | Ползунок | `80%` |
| `Игнорировать хитсаунды` | Favour hitsounds supplied by the current skin instead of the beatmap's included hitsounds. | Галочка | `Выключено` |

The master, music, and effect volume can be changed elsewhere by pressing `Alt` and scrolling up or down or by pressing `Alt` and pressing `Up` or `Down`.

### Универсальный оффсет

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Универсальный оффсет` | The offset (in milliseconds) that all beatmaps will use (in addition to the local offset). | Ползунок | `0 мс` |
| `Мастер настройки оффсета` | Открывает мастер настройки оффсета. | Кнопка |  |

- Подробнее о мастере настройки оффсета: см. [Мастер настройки оффсета](/wiki/Client/Options/Offset_Wizard)
- Подробнее об использовании мастера настройки оффсета: см. [Как использовать мастер настройки оффсета](/wiki/Guides/How_to_Use_the_Offset_Wizard)

## Скин

![Skin icon](img/skin-RU.jpg "Иконка раздела «Скин»")

Этот раздел посвящён тем вещам, связанным со скинами.

### Скин

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Skin sample image` | Display various gameplay elements from the selected skin. Click to cycle through different element sets. | Кнопка |  |
| `Выбор скина` | Changes the skin. Items in dropdown are based on what is in the `osu!/Skins` folder. (Names are based on folder name.) | Список | `Default` |
| `Посмотреть на внешний вид` | Previews the skin by playing a random beatmap with auto mod. Mode is determined on what was selected in song selection. | Кнопка |  |
| `Открыть директорию скина` | Открывает папку выбранного скина. | Кнопка |  |
| `Экспортировать в .osk` | Exports the current skin as a `.osk` file to share. Once your game client is done exporting, it will open the directory containing the `.osk` file. | Кнопка |  |
| `Игнорировать скины всех карт` | Favour the selected skin over the beatmap's included skin. This does not include hitsounds (see next option below). | Галочка | `Выключено` |
| `Свои хитсаунды и озвучка интерфейса` | Always use the selected skin's hitsounds instead of the beatmap's included hitsounds. | Галочка | `Включено` |
| `Свой скин для тайко` | Use osu!taiko-specific skin elements, if supplied by the selected skin. See [Skinning/osu!taiko](/wiki/Skinning/osu!taiko) for details. | Галочка | `Выключено` |
| `Свой курсор из скина` | Favour the current skin's cursor over any cursors supplied by beatmaps. | Галочка | `Выключено` |
| `Размер курсора` | Adjust the cursor size. | Ползунок | `1x` |
| `Автоподстройка размера курсора` | Automatically adjusts the cursor size based on the circle size of the beatmap. | Галочка | `Выключено` |
| `Окрашивать шар на слайдере в цвета комбо` | Slider balls will use the current combo colour (usually transparent). Requires skin support. | Галочка | `Включено` |

## Управление

![Input icon](img/input-RU.jpg "Иконка раздела «Управление»")

Этот раздел посвящён периферийным устройствам ввода.
### Мышь

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Чувствительность мыши` | Adjust the sensitivity of the mouse cursor. If changed, it may automatically enable `Прямой ввод`. | Ползунок | `1x` |
| `Прямой ввод` | Read mouse/tablet positional values directly from the hardware, without any post-processing (this is to ignore mouse acceleration). | Галочка | `Выключено` |
| `Отображать активную область в окно osu!` | Confine input devices with absolute positioning (e.g. pen tablets) to the game client window only. | Галочка | `Выключено` |
| `Ограничивать курсор` | Prevent mouse cursor from leaving the game client window. See below for details. | Список | `Only when fullscreen` |
| `Отключить колёсико мыши во время игры` | Disable mouse wheel during gameplay. Using the mouse wheel can change the master volume value. | Галочка | `Выключено` |
| `Отключить кнопки мыши во время игры` | Disable mouse buttons during gameplay. This is helpful for keyboard users. | Галочка | `Выключено` |
| `Показывать волны при нажатии` | Show subtle ripple effect when the mouse is clicked. | Галочка | `Выключено` |

- When `Raw Input` is enabled, it will display the number of reports it receives per second and the latency in milliseconds.
- The cursor ripple effect can be triggered by pressing `M1` and `M2` during game play.

---

If you open the dropdown list for `Confine mouse cursor`, you will be presented with these options:

| Название | Описание |
| :-- | :-- |
| `никогда` | Never prevent the mouse from leaving the game client. |
| `в полноэкр. режиме` | Only prevent the mouse from leaving the game client when fullscreen (this also includes `Letterboxing`). |
| `всегда` | Always prevent the mouse from leaving the game client in any resolution. |

### Клавиатура

| Название | Описание | Тип |
| :-- | :-- | :-- |
| `Назначание клавиш` | Displays a dialog which allows you to see or change your keyboard bindings. See [Keyboard Bindings](/wiki/Client/Options/Keyboard_bindings) for more details. | Кнопка |
| `Раскладка osu!mania` | Displays a dialog which allows you to see or change your osu!mania bindings. See [osu!mania layout](/wiki/Game_mode/osu!mania) for more details. | Кнопка |

### Другое

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Поддержка TabletPC` | Improves compatibility with graphic tablets and tablet PCs. | Галочка | `Выключено` |
| `Поддержка Wiimote/TaTaCon Drum` | Enable support for Nintendo's Wii Taiko Drum controller and Wiimotes. Pair device via Bluetooth before enabling. | Галочка | `Выключено` |

## Редактор

![Editor icon](img/editor-RU.jpg "Иконка раздела «Редактор»")

Этот раздел повсящён [редактору карт](/wiki/Client/Beatmap_editor).

These options only affect while working inside the beatmap editor or in test mode (test playing a beatmap).

### Общее

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Фоновое видео` | Play the beatmap's background video while editing. | Галочка | `Выключено` |
| `Использовать стандартный скин` | Use osu!'s default skin while editing, despite the current skin's settings. | Галочка | `Выключено` |
| `Ползущие слайдеры` | Enable snaking sliders while editing. | Галочка | `Включено` |
| `Анимация попадания` | Enable hit animations while editing. | Галочка | `Выключено` |
| `Связывающие точки` | Enable follow points while editing. | Галочка | `Включено` |
| `Показывать стеки` | Stack the hit circles as if in gameplay. | Галочка | `Включено` |

These options can be manually overwritten by using the `View` menu in the beatmap editor.

## Онлайн

![Online icon](img/online-RU.jpg "Иконка раздела «Онлайн»")

This section is about chat, spectators, multi, and osu!direct.

### Оповещения и личные данные

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Последняя строка чата` | Display the most recent chat message at the bottom of the screen. The message that displays is from the current channel you are viewing. | Галочка | `Выключено` |
| `Сворачивать чат во время игры` | If chat is open during breaks or in-game menus, the game client will automatically hide it when gameplay starts again. | Галочка | `Включено` |
| `Показывать уведомление при упоминании вашего ника` | When someone [mentions your username](/wiki/Client/Interface/Chat_console/Highlight) in chat, a notification will appear. | Галочка | `Включено` |
| `Показывать уведомления чата` | Display a notification, when new chat messages arrive. | Галочка | `Включено` |
| `Звуковое уведомление при упоминании вашего ника` | When someone [mentions your username](/wiki/Client/Interface/Chat_console/Highlight) in chat, a sound will play. | Галочка | `Включено` |
| `Показывать другим своё местоположение` | Share your city location in your user card (note that your country is already shared). | Галочка | `Выключено` |
| `Показывать список зрителей` | Show a list of current spectators on the left of the screen during gameplay. | Галочка | `Включено` |
| `Отправлять зрителям ссылку на играемую карту` | Send currently-playing beatmap to `#spectator` channel when you have spectators. | Галочка | `Включено` |
| `Показывать уведомления во время игры` | Allow a push notification to display during gameplay. If disabled, the game client will wait until you are done playing. | Галочка | `Включено` |
| `Уведомлять, когда друзья меняют статус` | Display a notification, whenever your friend goes online or offline. | Галочка | `Включено` |
| `Разрешить приглашения от всех игроков` | Allow multi game invites from anyone. Disabling this will limit multiplayer invites to friends only. | Галочка | `Включено` |

### Интеграция

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Discord Rich Presence` | Provides [rich presence data to Discord](/wiki/Guides/Discord_Rich_Presence). | Галочка | `Включено` |
| `Включить интеграцию с Yahoo! Messenger` | Yahoo! Messenger будет показывать песню, которую вы слушаете или играете. Это нужно настроить на сайте. | Галочка | `Выключено` |
| `Включить интеграцию с MSN Live` | Windows Live Messenger будет показывать песню, которую вы слушаете или играете. | Галочка | `Выключено` |
| `Автоматически скачивать карты через osu!direct` | For [osu!supporters](/wiki/osu!supporter) only. When spectating or multiplaying, the beatmap will be downloaded automatically. | Галочка | `Включено` |
| `Предпочитать карты без видео` | Только для [саппортеров osu!](/wiki/osu!supporter). Карты будут скачиваться через osu!direct без видео. | Галочка | `Выключено` |

### Игровой чат

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Скрывать оскорбительные слова` | Заменяет оскорбительные слова на `*бип*`. | Галочка | `Выключено` |
| `Скрывать юникод` | Удаляет все нестандартные символы ASCII в чате. | Галочка | `Выключено` |
| `Вести логи личных сообщений` | Личные сообщения будут сохраняться в папке `osu!/Logs`. | Галочка | `Выключено` |
| `Блокировать личные сообщения не от друзей` | Вам личные сообщения отправлять смогут только друзья. | Галочка | `Выключено` |
| `Игнор-лист (через пробел)` | Внесённые вами сюда слова будут игнорироваться. | Текст | *(пусто)* |
| `Список подсвечиваемых в чате слов (через пробел)` | Внесённые вами сюда слова будут [подсвечиваться](/wiki/Client/Interface/Chat_console/Highlight) в чате. | Текст | *(пусто)* |

## Разное

![Maintenance icon](img/maintenance-RU.jpg "Иконка раздела «Разное»")

Этот раздел посвящён картам и обновлениям.

### Общее

| Название | Описание | Тип |
| :-- | :-- | :-- |
| `Удалить все неранкнутые карты` | Delete all unranked maps in your songs folder. | Кнопка |
| `Восстановить права доступа к директориям` | Give read/write permission to the game client for access to its folders. (This will require the administrator password to complete.) | Кнопка |
| `Пометить все карты сыгранными` | Mark all maps as "played". | Кнопка |
| `Запустить апдейтер` | Close the game client and open the updater to search for updates and download if any. | Кнопка |

At the bottom, the version number will be displayed. Clicking this will open the [changelog](/wiki/Glossary/Changelog) for that version in your internet browser.

### Отладка

#### Build version

See which build version the game client currently has and which type of build updates the game client receives. Clicking on this will direct you to the release notes using your preferred browser.

The builds are versioned using this versioning scheme:

```
b{YYYY}{MM}{DD}.{revision}{type}
```

- `{YYYY}` is the build year
- `{MM}` is the build month
- `{DD}` is the build day
- `{revision}` is the build revision
  - If there is no build revision number, the decimal point will be removed.
- `{type}` is the build type
  - If there is no build type value, assume it is `Stable`.

## Trivia

- If you type in a username but leave the password textbox empty, osu! will use that name when saving the score locally.
- Opening the options sidebar will automatically trigger `osu! is up-to-date!`'s function (it will begin checking for updates).
- The `Seasonal backgrounds` option was added after positive feedback was given to the osu!dev team.
  - More details: [main menu background changes](https://osu.ppy.sh/community/forums/topics/606931)

### История

- The old options screen was an actual screen that had tabs, buttons, and a dark pale blue background.
- The old options screen also featured a skin selection screen that also allows you to preview live play of a beatmap in osu!.
  - After the options screen was moved over to a sidebar, this screen was still accessible by opening a skin file.
  - Access to this was later removed after skin previews and the live preview functions came to be.
