# Українська локалізація — Cairn

Фанатський переклад Cairn (The Game Bakers) українською. Мод — плагін BepInEx, що підміняє англійські
тексти українськими; оригінальні файли гри не змінюються. Перекладено всі тексти гри.

Переклад безкоштовний і таким лишиться. Якщо він припав до душі, можна кинути монету
в скарбничку: **https://send.monobank.ua/jar/8ZddSdGUd7**

## Встановлення

Завантажте останній архів на сторінці [Releases](https://github.com/furmonenko/cairn-ukrainian/releases).

1. Відкрийте теку гри (Steam: правою кнопкою по грі → «Керувати» → «Переглянути локальні файли»).
2. Розпакуйте туди весь архів, щоб `winhttp.dll` і тека `BepInEx` опинилися поруч із `Cairn.exe`.
3. Мову гри лишіть **English**: переклад підміняє саме англійську.
4. Перший запуск довший за звичайний: BepInEx готується. Далі гра стартує як завжди.

Уже маєте BepInEx 6 (IL2CPP) для інших модів — досить теки `BepInEx\plugins\CairnUkrainian`.
Steam Deck / Linux: у параметрах запуску гри впишіть `WINEDLLOVERRIDES="winhttp=n,b" %command%`.

Видалити мод: прибрати теку `BepInEx\plugins\CairnUkrainian`. Разом із BepInEx — також теки `BepInEx`,
`dotnet` і файли `winhttp.dll`, `doorstop_config.ini`, `changelog.txt`.

Після оновлення гри нові або змінені рядки лишаються англійською до наступного випуску перекладу.

## Помилки й побажання

Одруківки, кострубаті фрази, написи, що не влізли: [Issues](https://github.com/furmonenko/cairn-ukrainian/issues),
бажано зі знімком екрана: що написано, де саме, як має бути.

## Ліцензія

Текст перекладу — CC BY-NC-SA 4.0 ([`LICENSE.md`](LICENSE.md)). Шрифт Play — SIL Open Font License.
BepInEx — LGPL-2.1. Файлів гри в архіві немає.

Переклад не пов’язаний із The Game Bakers. Cairn — торгова марка її власників.
