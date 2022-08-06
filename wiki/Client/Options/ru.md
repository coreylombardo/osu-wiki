# Настройки

![Options menu](img/options_basic-RU.jpg "Меню настроек \(боковая панель\)")

В главном меню нажмите на `Options` или клавишу `O` (или же `Ctrl` + `O`, что работает практически на любом экране), чтобы открыть палень настроек и изменить доступные опции в osu!. После открытия меню настроек можно набрать текст для поиска конкретной опции. Текст строки поиска дрогнет, если поисковый запрос не имеет результатов.

При изменении опции, имеющей значение по умолчанию, серая вертикальная полоска слева будет светиться жёлтым цветом. Нажав на неё, можно вернуть значние этой опции к значению по умолчанию. 

## Общее

![General icon](img/general-RU.jpg "Иконка раздела «Общее»")

Этот раздел посвящён вашей учётной записи, языковым настройкам, и обновлениям osu!

### Вход

If you are not signed in to the game client, it will automatically open the options menu on start-up, prompting you to sign in. You can ignore this by pressing `Esc`, clicking on the back button, or navigating to the song selection screen. By not signing in, the game client will mark you as a "Guest" and you will not be able to fetch online scores, submit scores, or play [Multi](/wiki/Client/Interface/Multiplayer).

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
| `Logged in as {username}` | Показывает пользовательское меню, см. ниже. | Кнопка |

---

При нажатии на подсказку `Logged in as {username}` появится меню с этими кнопками:

| Название | Описание | Тип |
| :-- | :-- | :-- |
| `1. View Profile` | View your profile on the website. | Кнопка |
| `2. Sign Out` | Sign out from this game client. | Кнопка |
| `3. Change Avatar` | Change your profile picture (this will redirect you to the website). | Кнопка |
| `4. Close` | Close this dialog. You can also press `Esc`. | Кнопка |

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

### Рендеринг

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Ограничение FPS` | Set the frame rate limit. See below for details. | Список | `Optimal` |
| `Счётчик FPS` | Toggle the FPS counter. This is seen in the bottom-right corner of the screen. | Галочка | `Выключено` |
| `Режим совместимости` | Use the old renderer that osu! used before with older computers. This will restart your game client. | Галочка | `Выключено` |
| `Снизить кол-во потерянных кадров` | Adjust graphical settings to decrease dropped/stuttered frames. | Галочка | `Выключено` |
| `Обнаруживать снижение производительности` | Warn you if another program on your computer may harm your client's performance. | Галочка | `Включено` |

---

*Note: When the game client is not the active window, the fps limit is dropped to 30fps automatically.*\
*Caution to laptop users: using `Unlimited (gameplay)` may cause your laptop to overheat!*

При открытии списка `Ограничение FPS` появятся эти опции:

| Название | Описание |
| :-- | :-- |
| `Вертикальная синхронизация` | Limits the game client to the refresh rate of your monitor. See explanation below for details. |
| `Power Saving` | Limits the game client to twice the refresh rate of your monitor. |
| `Optimal` | Limits the game client to eight times the refresh rate of your monitor, capping at 960fps. |
| `Нет (во время игры)` | Limits the game client to the refresh rate of your monitor. See explanation below for details. |

- Пояснение `Вертикальной синхронизации`: Проще говоря, вертикальная синхронизация заставляет игру ждать загрузки всего кадра перед его отображением.
  - Вероятно, вы хотите включить это, если видите «разрывы» экрана (когда нижняя часть игры отстаёт от верхней части).
  - Несмотря на вышеизложенное, это может вызвать задержки или замедления, так как клиент должен ждать загрузки каждого кадра.
- Пояснение `Нет (во время игры)`: Unlimited only applies to when you are playing a beatmap.
  - When you are not playing a beatmap, the frame rate is limited to twice the refresh rate of your monitor, or 240fps, whichever is higher.
  - This option is **not recommended**. Using the `Unlimited (gameplay)` option can lead to stutters.
  - Using the `Optimal` option instead offers imperceivable changes in system (input to output) latency when compared to `Unlimited (gameplay)`.

### Layout

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Разрешение` | Set the game client resolution. The listed resolutions are limited to what your monitor/GPU supports. | Список |  |
| `Полноэкранный режим` | Run the game client in fullscreen (usually decreases input latency). | Галочка | `Включено` |
| `Render at native resolution` | Use the full native resolution but will display osu! in a smaller centred portion of the screen. | Галочка | `Включено` |
| `По горизонтали` | Adjust horizontal offset for letterboxing mode. Only appears if `Render at native resolution` is enabled. | Ползунок | `0%` |
| `По вертикали` | Adjust vertical offset for letterboxing mode. Only appears if `Render at native resolution` is enabled. | Ползунок | `0%` |

- If `Полноэкранный режим` is disabled, `Running without fullscreen mode will increase your input latency!` will appear underneath it.

### Детальные настройки

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Ползущие слайдеры` | Слайдеры будут разворачиваться из своей начальной точки. | Галочка | `Включено` |
| `Фоновое видео` | Allow the beatmap background video to play during gameplay (can be disabled per-beatmap). | Галочка | `Включено` |
| `Сториборды` | Allow beatmap storyboards to be played (can be disabled per-beatmap). | Галочка | `Включено` |
| `Комбо-всплески` | Allow combo bursts to display upon reaching a combo milestone. | Галочка | `Выключено` |
| `Вспышки от нот` | Display a subtle glow behind each hit explosion. Does not disable lighting during Kiai Time. | Галочка | `Включено` |
| `Эффекты шейдеров` | Display, graphically speaking, concert-type effects. This may automatically be disabled if your computer cannot handle it. | Галочка | `Выключено` |
| `Сглаживающий фильтр` | Adjusts the shaders to be less flashy. This will automatically enable `Эффекты шейдеров`. | Галочка | `Выключено` |
| `Формат скриншотов` | Устанавливает формат скриншотов. | Список | `JPEG (малый размер)` |

### Главное меню

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Включить снег` | Show snow effects on the main menu (forcibly enabled during the winter). | Галочка | `Выключено` |
| `Параллакс` | Show a slight parallax while navigating in-game menus (not during gameplay). | Галочка | `Включено` |
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

| Name | Description |
| :-- | :-- |
| `Top-Right (Pie)` | Use a pie chart to show the remaining duration before the song starts and the time left before completion. This is seen left of the accuracy. |
| `Top-Right (Bar)` | Use a short horizontal bar to display the time left before completion. This is seen underneath the score but above the accuracy. |
| `Bottom-Right` | Use a short horizontal bar to display the time left before completion. This is seen in the bottom-right corner. |
| `Bottom (long)` | Use a long horizontal bar to display the time left before completion. This is seen on the bottom. |

---

If you open the dropdown list for `Score meter type`, you will be presented with these options:

| Name | Description |
| :-- | :-- |
| `None` | Do not use a meter to display the player's hit timing. |
| `Colour` | Use coloured blocks to display hit timing. (osu!catch will always use this if `Hit error` is selected.) |
| `Hit error` | Use a meter to display hit timing. This shows if the player had hit too early or too late. |

### Song Select

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Display beatmaps from` | This adjusts the **lowest** difficulty beatmap that will be displayed in song select. | Slider | `0 stars` |
| `up to` | This adjusts the **highest** difficulty beatmap that will be displayed in song select. | Slider | `10+ stars` |

## Audio

![Audio icon](img/audio-RU.jpg "Audio icon")

This section is about audio related options.

### Devices

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Output device` | Select the preferred output device for audio. (Options given are based on what your computer reports.) | Dropdown | `Default` |
| `Audio compatibility mode` | Uses the legacy audio engine which has higher latency but is more compatible. | Галочка | `Выключено` |

### Volume

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Master` | Controls the main volume. | Slider | `100%` |
| `Music` | Controls the music volume. | Slider | `80%` |
| `Effect` | Controls the hitsounds and in-game sounds. | Slider | `80%` |
| `Ignore beatmap hitsounds` | Favour hitsounds supplied by the current skin instead of the beatmap's included hitsounds. | Галочка | `Выключено` |

The master, music, and effect volume can be changed elsewhere by pressing `Alt` and scrolling up or down or by pressing `Alt` and pressing `Up` or `Down`.

### Offset Adjustment

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Universal offset` | The offset (in milliseconds) that all beatmaps will use (in addition to the local offset). | Slider | `0ms` |
| `Offset wizard` | Opens the offset wizard. | Button |  |

- For details about the offset wizard, see [Offset Wizard](/wiki/Client/Options/Offset_Wizard).
- For details on using the offset wizard, see [How to use Offset Wizard](/wiki/Guides/How_to_Use_the_Offset_Wizard).

## Skin

![Skin icon](img/skin-RU.jpg "Skin icon")

This section is about skin related things.

### Skin

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Skin sample image` | Display various gameplay elements from the selected skin. Click to cycle through different element sets. | Button |  |
| `Current skin` | Changes the skin. Items in dropdown are based on what is in the `osu!/Skins` folder. (Names are based on folder name.) | Dropdown | `Default` |
| `Preview gameplay` | Previews the skin by playing a random beatmap with auto mod. Mode is determined on what was selected in song selection. | Button |  |
| `Open current skin folder` | Opens the selected skin folder. | Button |  |
| `Export as .osk` | Exports the current skin as a `.osk` file to share. Once your game client is done exporting, it will open the directory containing the `.osk` file. | Button |  |
| `Ignore all beatmap skins` | Favour the selected skin over the beatmap's included skin. This does not include hitsounds (see next option below). | Галочка | `Выключено` |
| `Use skin's sound samples` | Always use the selected skin's hitsounds instead of the beatmap's included hitsounds. | Галочка | `Включено` |
| `Use Taiko skin for Taiko mode` | Use osu!taiko-specific skin elements, if supplied by the selected skin. See [Skinning/osu!taiko](/wiki/Skinning/osu!taiko) for details. | Галочка | `Выключено` |
| `Always use skin cursor` | Favour the current skin's cursor over any cursors supplied by beatmaps. | Галочка | `Выключено` |
| `Cursor size` | Adjust the cursor size. | Slider | `1x` |
| `Automatic cursor size` | Automatically adjusts the cursor size based on the circle size of the beatmap. | Галочка | `Выключено` |
| `Use combo colour as tint for slider ball` | Slider balls will use the current combo colour (usually transparent). Requires skin support. | Галочка | `Включено` |

## Управление

![Input icon](img/input-RU.jpg "Иконка раздела «Управление»")

Этот раздел посвящён периферийным устройствам ввода.
### Мышь

| Название | Описание | Тип | По умолчанию |
| :-- | :-- | :-- | :-- |
| `Sensitivity` | Adjust the sensitivity of the mouse cursor. If changed, it may automatically enable `Raw Input`. | Ползунок | `1x` |
| `Raw input` | Read mouse/tablet positional values directly from the hardware, without any post-processing (this is to ignore mouse acceleration). | Галочка | `Выключено` |
| `Map absolute raw input to the osu! window` | Confine input devices with absolute positioning (e.g. pen tablets) to the game client window only. | Галочка | `Выключено` |
| `Confine mouse cursor` | Prevent mouse cursor from leaving the game client window. See below for details. | Список | `Only when fullscreen` |
| `Disable mouse wheel in play mode` | Disable mouse wheel during gameplay. Using the mouse wheel can change the master volume value. | Галочка | `Выключено` |
| `Disable mouse buttons in play mode` | Disable mouse buttons during gameplay. This is helpful for keyboard users. | Галочка | `Выключено` |
| `Cursor ripples` | Show subtle ripple effect when the mouse is clicked. | Галочка | `Выключено` |

- When `Raw Input` is enabled, it will display the number of reports it receives per second and the latency in milliseconds.
- The cursor ripple effect can be triggered by pressing `M1` and `M2` during game play.

---

If you open the dropdown list for `Confine mouse cursor`, you will be presented with these options:

| Name | Description |
| :-- | :-- |
| `Never` | Never prevent the mouse from leaving the game client. |
| `Only when fullscreen` | Only prevent the mouse from leaving the game client when fullscreen (this also includes `Letterboxing`). |
| `Always` | Always prevent the mouse from leaving the game client in any resolution. |

### Keyboard

| Name | Description | Type |
| :-- | :-- | :-- |
| `Change keyboard bindings` | Displays a dialog which allows you to see or change your keyboard bindings. See [Keyboard Bindings](/wiki/Client/Options/Keyboard_bindings) for more details. | Button |
| `osu!mania layout` | Displays a dialog which allows you to see or change your osu!mania bindings. See [osu!mania layout](/wiki/Game_mode/osu!mania) for more details. | Button |

### Other

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `OS TabletPC support` | Improves compatibility with graphic tablets and tablet PCs. | Галочка | `Выключено` |
| `Wiimote/TaTaCon Drum support` | Enable support for Nintendo's Wii Taiko Drum controller and Wiimotes. Pair device via Bluetooth before enabling. | Галочка | `Выключено` |

## Редактор

![Editor icon](img/editor-RU.jpg "Иконка раздела «Редактор»")

Этот раздел повсящён [редактору карт](/wiki/Client/Beatmap_editor).

These options only affect while working inside the beatmap editor or in test mode (test playing a beatmap).

### General

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Background video` | Play the beatmap's background video while editing. | Галочка | `Выключено` |
| `Always use default skin` | Use osu!'s default skin while editing, despite the current skin's settings. | Галочка | `Выключено` |
| `Snaking sliders` | Enable snaking sliders while editing. | Галочка | `Включено` |
| `Hit animations` | Enable hit animations while editing. | Галочка | `Выключено` |
| `Follow points` | Enable follow points while editing. | Галочка | `Включено` |
| `Stacking` | Stack the hit circles as if in gameplay. | Галочка | `Включено` |

These options can be manually overwritten by using the `View` menu in the beatmap editor.

## Онлайн

![Online icon](img/online-RU.jpg "Иконка раздела «Онлайн»")

This section is about chat, spectators, multi, and osu!direct.

### Alerts and Privacy

| Name | Description | Type | Default |
| :-- | :-- | :-- | :-- |
| `Chat ticker` | Display the most recent chat message at the bottom of the screen. The message that displays is from the current channel you are viewing. | Галочка | `Выключено` |
| `Automatically hide chat during gameplay` | If chat is open during breaks or in-game menus, the game client will automatically hide it when gameplay starts again. | Галочка | `Включено` |
| `Show a notification pop-up when someone says your name` | When someone [mentions your username](/wiki/Client/Interface/Chat_console/Highlight) in chat, a notification will appear. | Галочка | `Включено` |
| `Show chat message notifications` | Display a notification, when new chat messages arrive. | Галочка | `Включено` |
| `Play a sound when someone says your name` | When someone [mentions your username](/wiki/Client/Interface/Chat_console/Highlight) in chat, a sound will play. | Галочка | `Включено` |
| `Share your city location with others` | Share your city location in your user card (note that your country is already shared). | Галочка | `Выключено` |
| `Show spectators` | Show a list of current spectators on the left of the screen during gameplay. | Галочка | `Включено` |
| `Automatically link beatmaps to spectators` | Send currently-playing beatmap to `#spectator` channel when you have spectators. | Галочка | `Включено` |
| `Show notification popups instantly during gameplay` | Allow a push notification to display during gameplay. If disabled, the game client will wait until you are done playing. | Галочка | `Включено` |
| `Show notification popups when friends change status` | Display a notification, whenever your friend goes online or offline. | Галочка | `Включено` |
| `Allow multiplayer game invites from all users` | Allow multi game invites from anyone. Disabling this will limit multiplayer invites to friends only. | Галочка | `Включено` |

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
