# Aion — корректные описания умений и предметов / Correct Skill & Item Descriptions

Исправленные описания умений и предметов для клиента **Aion 4.6**: дописаны скрытые
характеристики (сила диспела, точность, PvP-коэффициенты, высота области действия и т. д.)
и поправлены места, где официальный текст говорил неправду.
Русский и английский варианты содержат одинаковый набор правок.

*Corrected skill and item descriptions for the **Aion 4.6** client: hidden values are spelled out
(dispel power, accuracy, PvP ratios, effect area height and so on) and places where the official
text was simply wrong are fixed. The Russian and English versions contain the same set of fixes.*

| Папка / Folder | Что внутри / Contents |
| --- | --- |
| `ru/` | русские описания / Russian descriptions |
| `en/` | английские описания / English descriptions |

<details open>
<summary><b>&nbsp;Русский&nbsp;</b> — нажми, чтобы свернуть</summary>

## Установка

1. Скачай архив со страницы [Releases](../../releases): `...-ru.zip` — описания на русском,
   `...-en.zip` — на английском.
2. Открой папку с игрой, зайди в `L10N`, а оттуда — в свою языковую папку (чаще всего `7_rus`).
3. Скопируй в неё папку `Data` из архива и согласись на замену файлов.
4. Перезапусти игру.

Должно получиться так:

```
Aion\L10N\7_rus\Data\strings\client_strings_skill.xml
Aion\L10N\7_rus\Data\strings\client_strings_item.xml
Aion\L10N\7_rus\Data\strings\client_strings_item2.xml
```

Какая папка нужна — зависит от клиента:

- если в `L10N` лежит всего одна папка — она и нужна, как бы она ни называлась;
- если папок много — `7_rus`, `2_eng`, `2_deu`, `2_fra`, а рядом `rus`, `eng`, `deu` без цифры —
  бери те, что **с цифрой**. Папки без цифры хранят озвучку и текстуры, описаний там нет.

Верный признак нужной папки: в ней уже лежат `Data\strings\client_strings_skill.xml`,
`client_strings_item.xml` и `client_strings_item2.xml`. Если таких папок несколько и непонятно,
какая твоя, — скопируй во все, хуже не будет.

Имя папки не всегда говорит о языке. На некоторых сборках папка называется `7_rus`, а текст
внутри английский — значит, английские файлы кладутся именно туда.

Откат: либо удалить (если изначально не было), либо восстановление (проверка) файлов в лаунчере вернёт оригиналы.

## Установка без релиза

Открой папку `ru` или `en` в этом репозитории, скачай все три файла кнопкой
**Download raw file** и положи их в `L10N\<твоя папка>\Data\strings\` с заменой.

</details>

<details>
<summary><b>&nbsp;English&nbsp;</b> — click to expand</summary>

## Installation

1. Download an archive from the [Releases](../../releases) page: `...-ru.zip` for Russian
   descriptions, `...-en.zip` for English ones.
2. Open your game folder, go into `L10N`, then into your language folder (usually `7_rus`).
3. Copy the `Data` folder from the archive into it and agree to replace the files.
4. Restart the game.

The result should look like this:

```
Aion\L10N\7_rus\Data\strings\client_strings_skill.xml
Aion\L10N\7_rus\Data\strings\client_strings_item.xml
Aion\L10N\7_rus\Data\strings\client_strings_item2.xml
```

Which folder you need depends on the client:

- if `L10N` contains just one folder, that is the one, whatever it is called;
- if there are many folders — `7_rus`, `2_eng`, `2_deu`, `2_fra`, plus `rus`, `eng`, `deu`
  without a number — use the ones **with a number**. The folders without a number hold
  voice-over and textures, no descriptions.

A sure sign of the right folder: it already contains `Data\strings\client_strings_skill.xml`,
`client_strings_item.xml` and `client_strings_item2.xml`. If several folders qualify and you are
not sure which one is yours, copy into all of them — it does no harm.

The folder name does not always tell you the language. On some servers the folder is called
`7_rus` while the text inside it is English — so English files go right there.

Reverting: delete the files (if there were none before), or the file check / repair in your launcher will download the originals again.

## Installing without a release

Open the `ru` or `en` folder in this repository, download all three files with the
**Download raw file** button, and put them into `L10N\<your folder>\Data\strings\`,
replacing the existing ones.

</details>
