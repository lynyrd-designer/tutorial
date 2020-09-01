Этот FAQ посвящен вкату во фронтенд-разработку.Основное предназначение FAQ'a - дать краткое, но емкое направление по оптимальному изучению стэка технологий, которые используются во фронтенде.

## Содержание

1. [Интро](#Интро)
2. [Верстка](#Верстка)
3. [JavaScript](#javascript)
4. [Основы](#Основы)
5. [Продолжение](#Продолжение)
6. [Advanced](#advanced)
7. [Дополнительно](#Дополнительно)

## Интро

Фронтенд в 2020+ — это **не**:

- Верстка лендингов
- Колупание в вордпрессе, жумле и проприетарных конструкторах сайтов - если вы хотите устроится в фирму, про вордпресс просто забудьте и не вспоминайте его, как страшный сон.

B 2020 фронтенд-разработка — это создание веб-приложений на JS'e. Хотя верстка отошла на второй план, это не значит, что изучать ее не обязательно — браузеры все так же понимают только CSS-стили, поэтому вы обязательно столкнетесь с ними на работе.

Что нужно знать на позицию фронтенд-разработчика начально-среднего уровня:

- HTML + CSS
- JS (ES6 как минимум, понимать TypeScript)
- Фреймворк(тут теперь у вас два выбора: либо React, либо Vue. На данный момент, пока, React все еще держит планку, но, количество вакансий на Vue стремительно растет).

Попутно изучается работа с командной строкой, git, инструменты сборки и прочие штуки. Все теоретические навыки обязательно подкрепляются практикой.

> Сколько времени займет обучение?

Много. В среднем, путь с нуля до уровня более-менее шарящего реакт/вью разраба потребуется около года. Ключевое слово - `с нуля`.

> Могу ли учить верстку/JS после работы по 2 часа?

Можете, но это вряд ли будет эффективно. Минимум, в день вам необходимо тратить от 4-х часов. Если вы тратите меньше, то у меня для вас плохие новости.

> Слышал что для устройства на работу нужно портфолио
Я тоже такое слышал, но обычно под "портфолио" понимают профиль на гитхабе и ссылочки на завершенные/активные проекты (если позволяет NDA | заказчик). По-большому счету, это все ерунда. Да, по мере вашего продвижения и прокачке скилов во фронтенде, вы можете добавлять свои проекты на гитхаб, но по сути, на них ни кто не обращает внимания, т.к ни что вам не мешает просто склонировать какой-то проект от дади Вани к себе в профиль и выдавать за свой.

> Почему фронтенд вообще существует? Есть же CMS/конструкторы-сайтов.

Через конструктор можно создать лендинг с рекламой ноготочков, что-то сложнее – нет.

>  Отдельно хотел бы отметить следующее: после того, как пройдет 2-3 месяца вашего непрерываного обучения - создать профиль на hh, разместить резюме и делать отклики на вакансии. Скорее всего, если вы еще неопытный инфантил, вам будут отправлять тестовые задания, на основе которых вы уже поймете, что учить, куда скакать и что вообще требуют.
> >
> > > СЕКРЕТ: Круто выполненое тестовое задание - это 90% вашего успеха на собесе. Скорее всего вас будут спрашивать именно о нем. Обьясните, расскажите свой код, что как делали - и оффер у вас в кармане.

У меня в тестовом просят сделать что-то невероятное, я такого еще не знаю даже

> Есть компании адекватные, есть нет. Пример неадекватного тестового: //github.com/fugr-ru/frontend-javascript-test
> Пример адекватного тестового: https://1drv.ms/b/s!AkZ_6ifMJnRTwWgmE0rZT_4yTwMf

Можно посмотреть гарвардский курс CS50. На [ютубе](https://www.youtube.com/playlist?list=PLawfWYMUziZqyUL5QDLVbe3j5BKWj42E5) есть его русскоязычная версия от 2015 года (с тех пор в кампуктерах ничего не поменялось). Англоязычную версию можно найти посвежее. Атеншн: для вката это необязательно, но полезно.

## Верстка

### Основы

#### Что нужно знать

- HTML:

  - Структура документа
  - Разметка
  - Тэги
  - Атрибуты

- CSS:

  - Основные селекторы (без фанатизма)
  - Основные свойства (отступы, размеры, цвет, шрифты и прочее)
  - Наследование свойств, каскад, вложенность
  - Основы сетки: блочная модель, флоаты, инлайн-блоки, [флексы](https://developer.mozilla.org/ru/docs/Learn/CSS/CSS_layout/Flexbox)
  - Свойства position

- Все вместе:
  - Типовая разметка текста
  - Картиночки, ссылочки
  - Таблички, списочки
  - Формы, инпуты, лэйблы

#### Итого

Умение сверстать простенькую статику, без новомодных фич, без семантики, модульности, бэмов, шмэмов, респонсивности и прочего. На все про все около месяца.

#### Где учить, что читать

- Старт: интерактивные курсы хтмл академии: https://htmlacademy.ru/program бесплатных вполне хватит, но можно и оплатить подписку (рекомендую, за 590 рублей очень много полезной инфы). Можно спросить в треде скриншоты теории продвинутых интерактивов: их регулярно трут отовсюду, кроме меги, поэтому приходится перезаливать.
- http://htmlbook.ru/
- https://html5book.ru/
- https://webref.ru/
- Базовый интенсив все той же академии (брать на торрентах)

Не стоит увлекаться просмотром сотен тысяч курсов, вебинаров, туториалов и прочему. Как правило хтмл академии + хтмлбука более чем достаточно для усвоения азов верстки.

Вообще, самый иделальный вариант для вас, чтобы научиться верстать.
Алгоритм:

- Проходите интерактивные курсы на HTMLAcademy - для начала хватит бесплатных.
- После этого идете сюда: https://www.youtube.com/channel/UCqGjCzCi5zG3RjJUA-ZDBkQ
- На канале BrainsCloud заходите в плейлесты и ищете макеты Mongo и ActiveBox.
- Верстаете вместе с автором, сначала прям вместе, переписывая его действия - параллельно изучая что за теги он использует на (http://htmlbook.ru/)
- На данном этапе жестко учим, что такое flexBox и Grid, интерактивная игрушка вам поможет (https://flexboxfroggy.com/#ru)
- После этого начинаете верстать сами, но не сразу, а в отрывках 5 минут. Например, посмотрели 5 минут видео - записали в конспект, что он сверстал, затем ставите на паузу и верстаете сами.
- В плейлистах смотрим все, кроме jQuery - он вам в принципе не нужен
- После того, как сверстали пару макетов, идем снова на HTML Academy и покупаем интерактивные курсы на 590 рублей.
- Проходим все курсы, анимацию, пока, можно не трогать.
- Все, в принципе, больше вам ни какие курсы и никакие видосы не нужны. На этом алгоритме вы сможете научиться верстать до того уровня, который требуют на собесах.

ВАЖНО!! Да, первое время вам будет сложно, даже ОЧЕНЬ сложно, но универсальной таблетки нет. Просто берите и верстайте. Ваш покорный слуга, на старте карьеры, 6 часов решал здесь задачи на флексы: (https://flexboxfroggy.com/#ru)

После этого можно начинать Версткy advanced/

#### Очень подробный верстка-гайдлайн

Стоит как минимум бегло просмотреть и прикинуть, что к чему: http://webmasters.teamdev.com/

---

### Верстка advanced

#### Что нужно знать

- HTML5: тэги и их семантику, атрибуты

- CSS:

  - Продвинутые селекторы (опять же без фанатизма, но знать полезно)
  - Градиенты, трансформации, анимации, переходы и прочие приколюхи
  - Респонсив ("адаптивность")
  - Переменные

  - Препроцессор SASS.

- Тулинг:

  - Организация структуры проекта
  - Работа в терминале (да, удаляй свой github desktop, вот прямо сейчас)
  - Использование пакетов, npm/yarn
  - Сборщики (для начала parcel, хардкорный режим – webpack)
  - Трансформация css: postcss, css-modules

- Не помешает:
  - Примерное понимание как работает js
  - Уметь верстать по макету из Figma – основной тулзой дизайнеров в 2020.
  - Уметь работать с каким-нибудь css-фреймворком (tailwind, bootstrap)

На все про все: еще месяц-два-три в ХУДШЕМ случае.

#### Итого получаем

Верстальщика, которая сможет заверстать статику любой сложности по данному макету.

#### Где учить, что читать?(РАСШИРЕННАЯ ВЕРСИЯ)

- https://www.freecodecamp.org/ - бесплатный ресурс с туториалами по (HTML, CSS, JS, React, Angular, Bootstrap, Git, Linux) с подробными разъяснениями + бесплатные курсы с сертификатами. Подходит ко всему

* http://nnmclub.to/forum/viewtopic.php?t=1220071 - 1 часть продвинутого курса от академии 2019. Там же можно найти 2 часть (заходим через VPN)
* http://htmlbook.ru/
* https://webref.ru/
* Верстка по БЭМ на примерах: http://habrahabr.ru/post/203440/
* http://ru.bem.info/ - документация БЭМ от Яндекса (ахтунг, фанатизм зашкаливает, не стоит увлекаться)
* http://getbootstrap.com/ - самый известный цсс-фреймворк.
* https://tailwindcss.com/ – цсс-фреймворк, который приходит на замену бутстрапу.
* http://habrahabr.ru/post/114256/ - чеклист верстки. Несколько устарел, но, в целом, актуален.
* http://habrahabr.ru/hub/webdev/ - тематический хаб, иногда проскальзывают полезные публикации.
* http://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/ – как работают браузеры.
* Документация препроцессоров: http://sass-lang.com/ http://lesscss.org/ http://stylus-lang.com/

**Дополнительные ресурсы, которые могут быть полезными на данном этапе:**

- http://css-tricks.com/ - много готовых шаблонов для решения часто встречающихся задач
- http://codepen.io/ - ресурс с кучей интересных примеров кода
- http://cssgridgarden.com/ – изучение гридов в формате игры

#### Что верстать самостоятельно

- Макеты для верстки, тоже от академии. Все из их рассылки и не проверялось уже пару лет. https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
- Крупный пак с псдшками для практики - https://mega.nz/#!CtYGSCbB!3Y6fDxxL_N_LstGFPGjHrhXbIoNqk4BzmNjjEmk2jPc
- http://dbfreebies.co/templates http://freebiesbug.com/psd-freebies/website-template/ - cайты с макетами.

#### В чем работать

На двнный момент [VSCode](https://code.visualstudio.com/) – это дефолтный редактор для фронтендеров и не только. Вся суть в гибкой настройке, ультраполезных плагинах и регулярных обновлениях. После перехода на жс+фреймворки в нем можно будет продолжать полноценно работать. Те, у кого дрова вместо рабочей станции, могут попробовать Sublime или NP++, но со временем с них все равно придется слезать.

#### Что делать дальше

Сверстать пару макетов для закрепления и переходить к JS. Не помешает сразу зацепить гит, основные команды в терминале, поколупать какую-нибудь бубунту на виртуалке. Само собой использование сборщика, отсутствие боязни терминала, понимание того, как браузер рендерит страничку, как лучше подключать шрифты/стили/скрипты и т.п.
ВАЖНО!! Если вы хотите стать именно frontend-разработчиком, не надо годами сидеть и изучать верстку. После пары тройки готовых шаблонов, можете смело переходить к js.

#### Самый крутой агйд по гит-хабу:

https://learngitbranching.js.org/?locale=ru_RU

**[⬆ К оглавлению](#Содержание)**

---

## JavaScript

Мир JS — это особый мир особого программирования, где любая задача может иметь десятки решений, где существуют сотни и тысячи инструментов, библиотек и подводных камней.

На самом деле, все довольно хорошо, и есть устоявшийся мейнстримовый набор:

- ES6+, TS
- Фреймворк на выбор
- Инструменты для работы с ЦСС на выбор (препроцессоры + бэм, цсс модули, css-in-js, либо свои корпоративные велосипеды)
- Webpack

Помните, что ньюфага никто (адекватный) не посадит, например, писать / править конфиги под SSR, поэтому учить наизуть webpack internals нинужно.

Обновляемый [роадмап frontend-разработчика](https://roadmap.sh/frontend). Не стоит пугаться большого разнообразия – основное, это то, что отмечено фиолетовым. Дойдя до react/redux уже можно искать работу. Роадмап на английском, но, вас, как фронтенд разработчика, не должно это пугать, правда?

### Основы

Для начала, посоветую вам учебник Дмитрия Трепачева : (http://old.code.mu/) - Очень крутой учебник, начиная с основ JS, заканчивая фреймворками. Если честно, то вообще JS можно от начала и до конца, если вы новичек, учить именно по этому учебнику. Все максимально доступно и понятно. Обьяснение - ДЗ.

учебник на JavaScript на русском языке — [Кантор](http://learn.javascript.ru/) . Ультраплатиновая ультрагоднота. У многих с нее пригорает, поэтому палим фишку: читаем про сам язык, скипаем особенности работы всякого дрянья в IE6, задачи делаем избирательно. И будем вам щастье. Учить этот учебник, как математику не нужно, в нем много того, чем вы даже, спустя год работы, пользоваться не будете, поэтому подходим к изучению избирательно. В идеале, чекайте учебник трепачева, че не понятно - смотрите у Кантора.
На начальном этапе, некоторые задачи после прохождения урока могут показаться вам сложными - те, которые такие - скипаем, позже вы к ним вернетесь.

Чтение нужно разнообразить видосами и другими сайтами. Одна и та же вещь, объясненная много раз разными словами, становится понятнее:

- Видос по основам JS от Минина (https://www.youtube.com/watch?v=Bluxbh9CaQ0&t=20235s) УЛЬТРАГОДНОТА
- Канал [Code Dojo](https://www.youtube.com/channel/UCY10FZglXJ8RL3xB04VpykQ) (рус) – относительно неплохие видео по ЕС6+, хотя все это есть и у Кантора. Есть немного реакта, редакса и ангуляра

- [Coursehunters](https://coursehunters.net/course/ponimanie-prototipnogo-nasledovaniya-v-javascript) - скринкаст egghead, популярно и кратко о прототипах, всего 30 минут, ES6.
- [Udemy, "The Complete JavaScript Course"](https://www.udemy.com/the-complete-javascript-course/) - неплохой платный курс (ну вы понели намек, да?)

- Канал [funfunfunction](https://www.youtube.com/c/funfunfunction/videos) - можно найти объяснение многих сложных для новичка штук – [async/await](https://youtu.be/568g8hxJJp4), [bind и this](https://youtu.be/GhbhD1HR5vk), [рекурсия](https://youtu.be/k7-N8R0-KY4), [каррирование](https://youtu.be/iZLP4qOwY8I).
- Канал [LearnCode.academy](https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw) — очень годный канал. Смотреть ES5 и ES6.

Основной справочник по JS — [Mozilla Developer Network](http://developer.mozilla.org/en/docs/Web/JavaScript). Хотите почитать про промисы — пишите в гугле `promises mdn`.

---

## Продолжение

- Продолжаем читать Кантора или Трепачева: заканчиваем первую часть, читаем DOM, события. Материалы касательно работы с графикой можно опустить.
- Курс "JavaScript Algorithms and Data Structures" на [freecodecamp](https://www.freecodecamp.org/learn/) – практическое дополнение к Кантору. На задачах в разделах "Basic/Intermediate Algorithm Scripting" можно применить прочитанное в учебнике. Плюс – эти задачи часто попадаются на собеседованиях.
- [Codewars](https://www.codewars.com/?language=javascript) – тоже про решение задач. Для саморазвития можно смотреть решение на других языках.
- Канал [Sorax](https://www.youtube.com/user/ArtSorax) (рус) – очень клевый канал по "олдскульной ванилле" (ES5, прототипы и прочие прелести жизни). Алярм: может закипеть мозг, объясняет очень быстро и четко, никаких вам "переменная это коробочка с данными"

* [JS the Right Way](http://jstherightway.org/) (есть версия на русском) – невообразимо объемный гайд: книги и статьи для изучения, описание фреймворков, стайлгайды и т.п. Рекомендуем ознакомиться

> **А... книжки?**

Само собой. Заходите ко мне в группу, листаете вверх, там будет сборник, называется "Вы не знаете JS". Это вообще все, что вам пока нужно из книжек.

> Что уметь?

Писать рабочий, хорошо структурированный, модульный код ОБЯЗАТЕЛЬНО на ES6 (лучше всего сразу привыкать к [TypeScript](https://www.typescriptlang.org/)). Для практики стоит придумать задачу - неважно, насколько шаблонной / скучной / избитой она будет. Легендарный тудулист вполне подойдет для оттачивания навыков: здесь вам и события, и работа с ДОМ, и обработка форм, можно прикрутить хранилище данных (localStorage, firebase) или даже "полноценный" бэкенд. К тому же, кода вполне достаточно для того, чтобы, например, написать приложение, используя MVC.

> Мой друг Самуил-Реактовец сказал, что прототипы не нужны. Можно их пропустить, уж очень они мудреные? Есть же ES6!

Нельзя. Во-первых, это один из самых часто встречающихся вопросов на собеседовании. Во-вторых, это основа основ JS, прототипы были, есть, будут и никуда не денутся, никакие ES6 классы и готовые либы этого не изменят. Понять прототипы === понять, как работает все, что на них завязано. А на них завязано вообще все. Ну, почти.

Все теоретические навыки обязательно подкрепляются практикой. Решайте задачки Кантора, каты на [CodeWars](https://www.codewars.com/?language=javascript), задачи из разделов "Basic/Intermediate Algorithm Scripting" на [freecodecamp](https://www.freecodecamp.org/learn). Попробуйте написать что-нибудь несложное, пусть код будет похож на императивную простыню: главное, чтобы работало.

---

## Advanced

### Промышленное программирование

Пришло время преодолеть разрыв между легкими и приятными учебными заданиями и суровой практикой с которой вам предстоит столкнуться на работе.

#### Выбор фреймворка

Первое и единственное решение, которое нужно принять: на какой фреймворк садиться. На текущий момент (2020) на выбор 2 с половиной стула:

##### Первый стул - [React](https://facebook.github.io/react/)

Традиционный выбор редакции (upd: в 2020 Реакт по прежнему универсальный выбор, замена не предвидится).
Ньюфажикам его советуют по многим причинам:

- Относительно высокий, но "плоский" порог входа: придется изучить все, что так или иначе пригодится после (включая вебпак)
- Много вакансий
- Куча обучающих материалов
- Прекрасное коммьюнити

Минусы:

- Каждый пук надо прикручивать самостоятельно. Да, даже цсс, не говоря уж про роутер, стейтменеджмент и прочее
- Отдельный пункт - анальные боли при работе с формами (для чего есть сотни библиотек, каждая из которых имеет неповторимый набор багов)
- Фейсбук делает Реакт **под себя**, так что неудивляйтесь, если через 6 месяцев все придется переписывать
- Редакс все еще промышленный стандарт, со всеми вытекающими через одно место

> Но Реакт не фреймворк, мне так на курсах гикбрейнса сказали!

Есть строгий критерий, определяющий грань между фреймворком и кастомым кодом/библиотекой. Для тех, кому впадлу [читать](https://habrahabr.ru/post/116232/) - Реакт вполне себе фреймворк. Свои недовольства можете отправлять в спортлото.

##### Второй стул - [Vue 2](https://vuejs.org/)

Из плюсов:

- Полноценный набор инструментов - в отличие от Реакта не придется прикручивать гайками отваливающиеся цсс модули
- Предельная простота и интуитивность
- Прельстиво и приятно шлепать формы (а мы же здесь формошлепы, как никак)

Минусы:

- Эван почему-то считает своим долгом копипастить у Фейсбука все. Даже то, что нинужно
- Сильно меньше работы

##### Второй с половиной стул - [Angular](https://angular.io/)

Трудное дитя гугла, поимело провальный старт, из-за чего его считают плохим, негодным, что, на самом деле, не так.

Плюсы:

- Искаропки есть все. Т.е. вообще все. А то, чего нет, прикручивается через CLI
- Собственно, шедевральное CLI (начинася с 6 версии cdk)
- Коммьюнити из суровых энтерпрайзеров, которые видели некоторое shit и которых ничем не испугать
- Много работы

Минусы:

- Oche высокий порог входа, придется выучить вообще все, при чем не всегда понятно, в каком порядке.
- На этом, собственно, все

Лучшие ресурсы для начала обучения - официальная документация. Что у Реакта, что у Ангулара, что у Вью она очень подробная и человеческая.

1. Документация. Ваш самый лучший друг. Читаем, что вы собираетесь изучать, пробуем установить, трогаем примеры.
2. Курсы. Как правило, одного достаточно, смысла смотреть `n` курсов по одному и тому же предмету нет - все повторяется.
3. Видосики, записи конференций
4. Статьи, бест практис, опенсорс проекты
5. ...
6. ?
7. Profit!

Кривая обучения в этом месте резко становится очень крутой и преодолеть ее с первого раза получается не у всех. Документация, случайные статьи и твиттеры разработчиков станут вашими новыми друзьями. И, конечно, эксперименты и практика.

#### Сборка

Если вы собирайтесь разбивать JS-код на несколько файлов и нормально использовать `import/export`, то вас настигнет вопрос сборки приложения. Сейчас для этого принято использовать [Webpack](https://webpack.js.org) — очень гибкий и мощный, но сложный в настройке инструмент, который интерпретирует все файлы как JS-модули.

Тут следует сказать, что для учебных и личных проектов в 90% случаев будет хватать [Create React App](https://create-react-app.dev/docs/getting-started/) или другого бойлерплейта. В таком случае webpack и babel уже зарание настроены во внутренностях и его можно не трогать. На промышленных проектах возможностей бойлерплейта обычно не хватает, поэтому рано или поздно вы столкнетесь с настройкой этих тулзов. Но еще раз – ньюфага никто не посадит править сложный конфиг на большом проекте, поэтому без фанатизма.

[Скринкаст Кантора](https://www.youtube.com/playlist?list=PLDyvV36pndZHfBThhg4Z0822EEG9VGenn) поможет вам разобраться с базовой конфигурацией.
`Варнинг - скринкаст устарел, умер и разложился, оставим его здесь на память.`

[Полноценный скринкаст по новому вебпаку](https://www.youtube.com/playlist?list=PLTbz5Wv5vNcs0zKKmF0DSo6m05RnMqUXk) (рус) - must watch.

> По стостоянию на 21.12.2018 современные браузеры нативно поддерживают ES модули, что позволяет использовать `import/export'` прямо браузере, без вебпаков. Но на проде использовать пока рановато.

#### Деплой

Чтобы ваши проектики увидел будущий работодатель, их нужно задеплоить – то есть развернуть где-то на сервере в продакш–режиме. Сейчас сделать это стало очень просто, есть несколько вариантов:

- Залить на github-pages. [Вот туториал от CRA](https://create-react-app.dev/docs/deployment/#github-pages).
- [Vercel](https://vercel.com/) (бывший Now) – наверное, самый быстрый способ задеплоить (в одну команду из консоли, либо нажимая кнопочки руками)
- [Heroku](https://www.heroku.com/) – некогда самый популярный сервис, сейчас непонятно – похоже уступает другим
- [Netlify](https://www.netlify.com/) – туда же

Деплоим, ссылки указываем резюме, работодатель тыкает (но это не точно) наши проекты, убеждается в нашей крутости, profit.

#### Что делать дальше

Если вы уже состояфшийся фронт и вам кажется, что развиваться больше некуда - вынуждены вас разочаровать.

- [TypeScript](https://www.typescriptlang.org/) - пожалуй, самый популярный и полезный яп, расширяющий возможности ванильного JS. Очень рекомендуем попробовать (в 2020 must have). Будем откровенны - если вы читаете этот раздел, то TS вы уже ДОЛЖНЫ знать, так что давайте, бегом-бегом читать документацию, благо она у ТС шикарная.
- [ClojureScript](https://clojurescript.org/) - кложура, которая транспайлится в ЖС.
- [elm](http://elm-lang.org/) - функциональщина с приятным ароматом хаскеля и замечательным синтаксисом, от которого у неофитов выпадают глаза. До поры до времени активно форсился, но потом утратил позиции в связи с новым хайп-продуктом от господа бога нашего и пророка Фейсбука (о чем ниже).
- [ReasonML](https://reasonml.github.io/) - окамль с человеческим лицом от фейсбука. Ну или типа того, who cares? [Полезная ссылочка для инетерсующихся](http://2ality.com/2017/11/about-reasonml.html)
- [Dart](https://www.dartlang.org/) - авантюра гугла по созданию полноценной альтернативы JS со своим интерпретатором и андефайнедами. Попросили упомянуть - упомянули, вот. Есть такая штука, да, наверное, даже клевая (а может и нет). Больше сказать о нем нечего, в вакансиях почти не встречается, реального продакшн кода на нем лично составители FAQ и их знакомые не имели.
- [CoffeeScript](http://coffeescript.org/) - морально и физически устарел, все хорошее, что в нем было, перекочевало в ES6+. Иногда встречается в дремучих проектах, написанных на рубя с шаблонами. Учить не нужно, да и нечего там учить.

**TL;DR**: В 2020 TypeScript стал стандартом, большинство новых проектов стартуют на нем. Все остальное (кроме кофе) можно потрогать на досуге, но в основном для саморазвития – работы на этом очень мало. Кофе не нужно, пейте чай. Шутка. Нет, правда, кофескрипт не нужен.

Выбрав стул с реактом, можно смотреть в сторону таких вещей:

- [Next.js](https://nextjs.org/) – фреймворк поверх реакта с упором на SSR. Активно поддерживается, большое коммюнити, много примеров.
- [Gatsby](https://www.gatsbyjs.org/) - что-то похожее на next, но попроще. Сделан упор на создание блогов/лендингов. Есть много плагинов, расширяющих базовые возможности. Хорошо работает со многими cms.
- [Styled Components](https://styled-components.com/) - css-in-js с компонентным подходом. Как альтернатива – [Emotion](https://github.com/emotion-js/emotion). Можно почитать про [JSS](https://cssinjs.org/) (используется в [material-ui](https://material-ui.com/))
- [Apollo GraphQL](https://www.apollographql.com/) – инструмент для работы с graphql на жсе, есть клиентская [библиотека](https://www.apollographql.com/docs/react/) под реакт. [Что такое graphql, хабр](https://habr.com/ru/post/326986/).
- Тестирование – большая тема, но тут ясно одно: на основные части любого приложения, которое активно разрабатывают, должны быть написаны тесты – иначе смэрть. Как делаются и что почитать: [дока реакта](https://ru.reactjs.org/docs/testing.html), [jest](https://jestjs.io/docs/ru/tutorial-react), [React Testing Library](https://testing-library.com/docs/react-testing-library/intro).

Независимо от стула:

- Progressive Web Apps – это про использование набора технологий, позволяющих делать веб-приложение максимально похожим на нативное. Например, такое приложение может слать пуш-нотификации и работать офлайн. Что почитать: [хабр](https://habr.com/ru/post/418923/), [гугл](https://web.dev/progressive-web-apps/). Неплохой [курс](https://www.udemy.com/course/progressive-web-app-pwa-the-complete-guide/) на udemy.

Не забываем про линтинг [ESLint](http://eslint.org) который избавит от совсем уж тупых ошибок/опечаток и приучит к написанию красивого кода.

Навыки работы с консолью и гитом подразумеваются для любого разработчика по умолчанию, об этом часто даже не пишут в вакансии.

### Лицензии

Для чего нужны лицензии, какую лучше применить для того или иного проекта, что они разрешают, а что нет - знать нужно. Поэтому предоставляю ссылку на замечательный ресурс [TLDRLegal](https://tldrlegal.com/), который поможет разобраться во всем этом.

### Устройство на работу

Причесываем гитхаб, маскируем коммиты уровня "ффыарфрырыффф". Составляем адекватное резюме, рассылаем его по всему хедхантеру, небо и Аллаха в копию. Впрочем, если в резюме видны зачатки мысли (и вы в ДС), то HR скоро вас сами найдут и обрушат лавину звонков и писем.

Основная часть собеседования это рассказ о себе и своих проектах. Заранее подумайте что сказать. Если есть ноутбук, то приходите с ним и показывайте проекты вживую.

Если ты живешь в мухосранске, то хорошим вариантом зарабатывать 900кк/наносек может быть удаленка. Уточним – под удаленном работой понимается не фриланс, а все та же работа в компании/студии, только с дому. Спасибо пандемии – количество удаленных вакансий возросло многократно, после пандемии возможно многие так и не вернутся в офисы. Вот где можно найти нормальные (и дерьмовые) вакансии на удаленочку:

- [Хабр Карьера (бывший moikrug)](https://career.habr.com/) – есть адекватные вакансии, нужно заполнить профиль
- [джин](https://djinni.co/) – много удаленных вакансий. Можно анонимно опубликовать профиль, хрки сами будут тебе писать.
- Телеграм:
  - [джс джобс](https://t.me/javascript_jobs), [джс жобс бот](https://t.me/javascript_jobs_feed) – самый популярный канал с вакансиями и резюме по жс
  - [profunctor jobs](https://t.me/profunctor_jobs) – вакансии от канала с мемами

#### Платиновые вопросы на собеседованиях!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Большая часть из них разобрана здесь: [Вопросы кандидату на должность front-end разработчика](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/src/translations/russian). Можно посмотреть ["Собеседования в прямом эфире"](https://www.youtube.com/playlist?list=PLo6puixMwuSOa_0EH6X4OXzFAmyQGS3a3) на канале хекслета.

Решения тестовых задач в функциональном стиле — очки х2: `спорный момент`. Инсайд: из-за наплыва "адептов функциональщины" и "детей ES6" могут потребовать написать "чистое решение" на ES5. Передаем привет всем, кто опустил / не понял прототипы.

**[⬆ К оглавлению](#Содержание)**

---

## Дополнительно

### Английский

> Нужен ли английский и как его выучить? Я и так уже по самую макушку завален материалами!

Нужен. Большая часть самых клевых материалов - на английском, большая часть влиятельных / шарящих людей в коммьюнити - не из СНГ и общаются на английском или своем родном (передаю привет одному голландцу). Плюс это нехилый бонус к трудоустройству.

Ниже будет подборка ответов / материалов по англйискому от анонов, за что им спасибо.

> Как учить?

Практикой и погружением:

- Приложения на смартфон Duolingo и Memrise. Первый бесплатен, второй платен, но бесплатной версии более чем достаточно. У Duolingo есть и [веб-версия](https://www.duolingo.com/)
- Чтение англоязычного интернета. Даже банальной Википедии будет достаточно. Еще можно читать газеты и издания мирового уровня типа:
- [vox](http://vox.com)
- [economist](http://www.economist.com/)
- [NYT](http://www.nytimes.com/)
- [BBC](http://www.bbc.com/)
- [spectrum](http://spectrum.ieee.org/)
- [combinator](https://news.ycombinator.com/)
- Фильмы на английском с сабами
- Игры на английском с сабами
- Интерфейс во всех приложениях на английском

Для грамматики подойдет курс от Полиглот 16 уроков. Еще стоит отметить простой переводчик по клику для хрома LinguaLeo. Другое полезное расширение - Grammarly, смотрит за правильностью того как ты пишешь на английском и высвечивает ошибки, неправильную грамматику, подсказывает правильный порядок слов и так далее. А ещё он может показывать значение слова по клику, с полноценной выдачей о значении этого слова

Читать поначалу можно словарём - Chrome, Google Dictionary дополнение. Кликанье на все непонятные слова во время чтения/раздумья над смыслом статьи должно стать привычкой.

Обычно сначала трудно но через пару недель чувствуешь результат, потом уже стабильное улучшение.

### Подкасты

Подкасты сейчас очень популярны, только ленивый их не записывает. Но среди всей этой кучи встречаются реально интересные, где можно послушать крутых спецов из той или иной сферы или что-то полезное узнать. По фронтенду их существует огромное количество как на русском языке, так и на английском (в этом случае можно прокачать свой скилл восприятия английского на слух). Вот самые популярные из них.

На русском:

- [Веб-стандарты](https://soundcloud.com/web-standards)
- [FrontendWeekend](http://frontendweekend.ml/)
- [Фронтенд Юность](https://soundcloud.com/frontend_u)
- [DevShacht](https://soundcloud.com/devschacht)
- [Пятиминутка React](http://5minreact.ru/)

На ангийском:

- [Front End Happy Hour](https://frontendhappyhour.com/)
- [JS Party](https://changelog.com/jsparty)
- [JavaScript Jabber](https://devchat.tv/js-jabber/)
- [The Frontside Podcast](https://frontside.io/podcast/)
- [Egghead Podcasts](https://egghead.io/podcasts)

### Игры

Большинство людей любят игры. Но как же приятно осознавать, что ты проводишь время с пользой, играя в них. Ниже приведу список игр, нацеленных на прокачку различных технологий и работй с алгоритмами:

- [WarriorJS](https://warriorjs.com/)

  Данная игра нацелена на прокачку сразу нескольких навыков. Таких, как программирование на JavaScript, и работа с алгоритмами.

  Вы играете за воина, поднимающийся на высокую башню, чтобы получить меч JS, на пути встречаются различные сложности, которые надо преодолеть, написав необходимый код. На сайте также есть рейтинг игроков, благодаря этому появляется своеобразный соревновательный режим.

- [codepip](https://codepip.com/games/)

  На данном сайте имеется большой выбор игр (некторые из них платные), нацеленных на прокачку CSS и JS.

  Лично я проходил Flexbox Froggy и Grid Garden. Благодаря чему, стал лучше понимать работу с flexbox'ами и grid'ами.

### Прочие мелочи

> Правда ли, что JS был придуман за 10 дней? Мой друг Вася-Джавист сказал, что это ущербный недоязык, хах.

Первая спецификация действительно была разработана и утверждена в кратчайшие сроки, и предназначалась для решения примитивнейших задач (оживить картинку, подсветить кнопочки). С тех пор прошло очень много времени, от первой спецификации осталась только общая концепция да парочка досадных багов, которые нельзя пофиксить из-за обратной совместимости (typeof Null, ага).

> Нужен ли матан?

Скажем так: лишним не будет, но и без него frontend разработчик не чувствует себя ущербным. Полезными будут знания дискретной математики, теории чисел и графов, а также основы теории алгоритмов (впрочем, это уже CS). Все это вполне изучается самостоятельно в свободное время. Для практики в этом деле лучше использовать Python: он более строгий, лаконичный и понятный. Хотя и на ES6 получаются очень даже красивые решения всяких олимпиадных задачек.

> Хочу фрилансить!

Фрилансить версталой - гиблое дело. Да и вообще фрилансить без опыта работы - гиблое дело. Да и вообще фрилансить в 2020 - гиблое дело. Адская конкуренция, кривые ТЗ, неадекватные заказчики, баны на апворках и прочие прелести ждут. Но никто не мешает попробовать.

> Так как же в итоге начать понимать JS?

Универсального ответа на этот вопрос нет. Если Вы начинаете вкатываться с нуля, то вот примерный алгоритм для новичка:

> Для начала у вас есть два сайта на выбор: (http://code.mu/ru/javascript/book/prime/) и (https://learn.javascript.ru/). Смотрите и тот и тот и выбираете, какой вам больше нравится.
> Для начала учите основы, маленькими шагами двигаясь вперед. Лично я рекомендую первый учебник, потоvу что именно там материалы подаются именно в том порядке, в котором они вам пригодятся в реальной практике + после каждой темы есть очень хорошая практика.
> Все, что прочитали - закрепляем видосами на ютубе.
> После того, как прошло недели 2-3, открываем это видео и смотрим еще раз (https://www.youtube.com/watch?v=Bluxbh9CaQ0&t=20235s).
> После этого переходим к ДОМ. На этом этапе у вас уже появится понимание, куда двигаться.

Самое главное - это практика. Всегда что-то мастерите, после того, как узнали какую-то тему, всегда попробуйте сделать что-то свое.

Так же скажу поповоду мотивации: иногда вам будет казаться, что все плохо, что у вас ничего не получается и вы ничего не умеете. Это нормально, абсолютно. Если прошел месяц а вы чувствуете тоже самое - это нормально. Если прошло два - это нормально. Если три - то это не нормально.

По поводу мотивации есть два отличных ролика:
(https://www.youtube.com/watch?v=lV4Ww8vGU88)
(https://www.youtube.com/watch?v=rAT3zYWBmp8&t=415s)

Этот тред будет дополняться, так что не выкидывайте ссылку

**[⬆ К оглавлению](#Содержание)**
