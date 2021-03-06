Пять человек собрались, чтобы стать фронт-энд разработчиками. Начали с нулевых знаний.


## Прогресс по знаниям

Справочники в интернете предоставляют исчерпывающую информацию по разным технологиям. Новичку сложно понять в каком порядке, и что необходимо учить. Чтобы исправить эту ситуацию, в списках ниже собранны и сгрупированны по технологиям самые необходимые теги, команды и прочее, которые необходимо знать наизусть.

Если знаете плохо что-то из списка и там уже стоит `+`, значит следует это срочно выучить. Не отставайте.

1. [Справочник по HTML](https://webref.ru/html)
1. [Справочник по CSS](https://webref.ru/css)
1. [Git Book на русском на оф. сайте](https://git-scm.com/book/ru/v2)


### HTML тэги
```
+ html:5
+ div
+ span
+ a 
+ p
+ h1-h6
+ img
+ table>(tr>th+tr>td)
+ strong
+ i
+ u
+ hr
+ style
- ul>li, ol>li
- button
- form, input, label, textarea
- pre
- sub, sup
- video, audio
```


### CSS свойства
```
+ display
+ padding
+ margin
+ border
  + border-top, border-bottom, border-left, border-right
  + border-image
  + border-spacing
  + border-collapse
  + border-color
  + border-style
+ width, min-width, max-width
+ height, min-height, max-height
+ background
  + background-color
  + background-image
  + background-repeat
  + background-position
  + background-size
+ cursor
+ box-shadow
+ overflow, overflow-x, overflow-y
+ opacity
+ float, clear
+ position, top, bottom, left, right
+ vertical-align
- box-sizing
- z-index

для инлайн и инлайн-блок элементов:
если определить эти свойства для блок элемента,
то они будут приняты инлановыми и инлайн-блочными наследниками
+ text-align, text-align-last
+ color
+ line-height
+ font
  + font-family
  + font-size
  + font-weight
  + font-style
+ text-decoration
+ text-transform
- text-overflow
- text-shadow
- letter-spacing
- white-space
```


### JavaScript: журнал прохождения по #встречам
```
+ HTMLElemnet
  + .style #В19
  + .onclick #В19
  + .dataset #В21

+ document
  + .querySelectorAll #В19
  + .querySelector #В20

+ цикл for #В20

+ Array.prototype
  + .forEach #В20
```


### Git команды
```
+ git init — создать локальный репозиторий
+ git clone — склонировать удаленный репозиторий
+ git status — посмотреть какие изменения на сцене, а какие за кулисами
+ git add <файлы> — вывести изменения из-за кулис на сцену
- git checkout -- <файлы> — увести изменения со сцены за кулисы
+ git commit — сделать снимок сцены и сохранить его в текущюю ветку
+ git log — посмотреть историю снимков в текущей ветке
+ git push — отправить историю снимков на удаленный репозиторий
+ git pull — запросить новые снимки с удаленного репозитория для текущей ветки
+ git remote add <название> <адрес> — добавить ссылку на удаленный репозиторий
+ git checkout <ветка> — перйти на другую ветку
+ git checkout -b <имя_новой_ветки> — создать новую ветку
- git reset
- git merge <имя_другой_ветки> — добавить в текущию ветку снимки из «другой ветки» 
- git fetch — получить информацию о всех ветках на удаленном репозитории
```


## Статистика

Ниже представлены графики, которые показывают кто и сколько времени потратил на кодинг за последние 7 дней. Если кликнуть по графику, откроется история за 30 дней.

| Участник | Статистика |
| :---     | :---:      |
| Света    | [<img src="https://wakatime.com/share/@svetlana/5ddde81c-26b9-4dce-a7ca-f7c1cc4a299f.png" height="300" alt="По клику — история за 30 дней"/>](https://wakatime.com/share/@svetlana/2592d30e-b47d-4d8e-9075-42b2dc24b44b.svg) |
| Айрат    | [<img src="https://wakatime.com/share/@Ayrat/083400fa-6982-4b10-a0e1-5d81ef1f1fea.png" height="300" alt="По клику — история за 30 дней"/>](https://wakatime.com/share/@Ayrat/e694a8a9-6d54-43e0-b7d3-20b873582320.svg) |
| Кирилл   | [<img src="https://wakatime.com/share/@f4eb4dfe-8143-43ef-972c-049f2f70e22e/ced37656-84bb-4ae8-84af-d24a6abf35d7.png" height="300" alt="По клику — история за 30 дней"/>](https://wakatime.com/share/@f4eb4dfe-8143-43ef-972c-049f2f70e22e/dc83902d-e979-4676-9dcb-6d04450a0b7f.svg) |
| Артём    | [<img src="https://wakatime.com/share/@b5b22cc5-467a-4d0b-b410-12f556aef22d/44a7e465-8194-4071-8195-bb1d2ee0b378.png" height="300" alt="По клику — история за 30 дней"/>](https://wakatime.com/share/@b5b22cc5-467a-4d0b-b410-12f556aef22d/87afb21e-4674-4488-a28d-34f787a4d7c6.svg) |
| Костя    | [<img src="https://wakatime.com/share/@4942ac04-3571-47be-9874-ec0ded68b6d8/4c96721d-7b5e-4a19-a18d-d5bf2331c34f.png" height="300" alt="По клику — история за 30 дней"/>](https://wakatime.com/share/@4942ac04-3571-47be-9874-ec0ded68b6d8/75d2f3ce-1f63-4de1-91c2-cc3cb56474a6.svg) |

[Профили участников](https://github.com/orgs/kompotik/people) на ГитХабе


## Наши места обитания

- На Ю-тьюбе [плейлист](https://youtube.com/playlist?list=PLp85Etu01sAeBI6qD1oNRC7EKhF5CoeKg)
- В Телеграме [чатик](https://t.me/kompotik_chat) и [канал](https://t.me/kompotik_feed)
- На Гитхабе [организация](https://github.com/kompotik)
