Это гостевая статья от [Бена Страхана][1] — члена клуба Meteor.js. Он 
написал крутой обобщающий пост, и я хочу им поделится со всем клубом!

## Как я стал разработчиком веб приложений — *в стиле Meteor*

Что должен знать веб-разработчик, собирающийся создавать приложения 
на [Meteor][2]?
Ниже приведен список языков, фреймворков, библиотек, пакетов и многое другое ;)

Списки в статье специально даны в определённом порядке, если не указано 
иное. Эта статья не объясняет, почему вы должны изучать ту или иную 
техноголию (вы сами должны в этом разобраться). Её цель — дать быстрый
обзор технологий, с которыми ежедневно имеет дело Meteor-разработчик. 

Чтобы не блуждать в море новой информации, хорошо бы иметь под 
рукой карту, на которую можно взглянуть и узнать в какой точке
пути вы находитесь.

![Побег Немо][3]

## Языки, библиотеки и фреймворки, трындец!

В конечном итоге вам нужно уметь понимать [Meteor API][4]. Изучение технологий, 
приведенных ниже, даст вам всё необходимое. Нет нужды становиться экспертом в 
каждой области, но нужно понимать структуру и терминологию каждой из них. 

Вы не знаете, что такое API? [Посмотрите видео этого парня][5].

### Обязательно

1. [Javascript][23] — вначале JS?! Да, солдат, не задавай мне снова вопросов, 
а то я подыму тебя с вертухи!
2. [Shell (Terminal)][24]
3. [HTML & CSS][25]
4. [JSON][26]
5. [MongoDB][27]
6. [Handlebars][28]
7. [Git][29] и [GitHub][30]
8. [jQuery][31]
9. [LESS][32] и/или [SASS][33]
10. [Underscore][34] и/или [Lo-Dash][35]
11. [Bootstrap][36]

### Опционально (изучайте при необходимости)

1. [NodeJS][6]
2. [Cordova][7]
3. [ElasticSearch][8]
4. [Ionic][9] — пакет Meteor [Meteoric][10]

## MeteorJS

Теперь, когда изучены все перечисленные технологии, вы достойны 
познать силу и великолепие Meteor!

![газонокосилка работающая на meteor][11]

Почему вам нужно изучить ВСЁ это перед тем, как
прикасаться к Meteor? Потому что Meteor — это [full-Stack][12] платформа.
Через Meteor вы управляете фронт-эндом, бек-эндом и всеми остальными эндами.

…Ладно, больше никаких вопросов, давайте узнаем ещё БОЛЬШЕ! 

Пришло время становиться Meteor-задротом, читайте доки:

* [Основная документация по API][4]
* [Подпроекты][13]

Если подпроекты выглядят пугающе, не волнуйтесь. Ниже приведен 
необходимый минимум, который вам нужно знать:

1. [Blaze][14]
2. [Spacebars][15]
3. [Tracker][16]
4. [Utilities][17]

### Хорошие уроки и курсы по Meteor

Упорядочены по сложности и глубине. Уроки, курсы, книги и видео 
проведут вас по различным проектам Meteor. Это будет кульминацией 
всей статьи:

1. [Meteor's official tutorial][37] (бесплатно)
2. [Your First Meteor Application][38] от David Turnbull (бесплатно)
3. [Meteor Walkthrough Videos][39] от George McKnight (бесплатно)
4. [Meteor Cookbook][40] от Abigail Watson
5. [Discover Meteor][41] от Sacha Greif & Tom Coleman (от $ до $$) 
(прим. переводчика: есть [бесплатная версия на русском языке][153])
6. [Meteor in Action][42] от Manuel Schoebel & Stephan Hochhaus ($)
7. [8 Days of Meteor][43] от Josh Owens ($)
8. [Meteor Testing][44] от Sam Hatoum ($)
9. [Meteor Club Master Bootcamp][45] от Josh Owens ($$$)
10. [Meteor Club Testing Bootcamp][46] от Josh Owens & Sam Hatoum ($$$)
11. [Bulletproof Meteor][47] от Arunoda Susiripala (бесплатно или $$)
12. Продвинутые курсы [Evented Mind][48] от Chris Mather ($$)

## Пакеты Meteor (в произвольном порядке)

Да, для изучения осталось ещё много всего. У Метеора есть менеджер пакетов,
который называется [Atmosphere][18]. Он позволяет сообществу создавать 
пакеты, которые глубоко интегрированы в платформу Meteor, они расширяют
API, доступные для вас как для разработчика. Ниже приведен список из
стандартных пакетов, которые вы найдёте в почти каждом серьёзном
Meteor-приложении, поэтому их нужно знать:

| Название пакета | GitHub | Atmosphere | Сайт |
| --------------------------------- | ------------- | ----------------- | ------------- |
| accounts-password                 | [github][49]  | [atmosphere][50]  | [сайт][51]    | 
| useraccounts:core                 | [github][52]  | [atmosphere][53]  | [сайт][54]    | 
| reactive-var                      |               | [atmosphere][55]  | [сайт][56]    | 
| reactive-dict                     |               | [atmosphere][57]  |               | 
| iron:router                       | [github][58]  | [atmosphere][59]  | [руководство][122] [сайт][60]  | 
| zimme:iron-router-active          | [github][61]  | [atmosphere][62]  |               | 
| zimme:iron-router-auth            | [github][63]  | [atmosphere][64]  |               | 
| manuelschoebel:ms-seo             | [github][65]  | [atmosphere][66]  | [статья][67]  | 
| dburles:collection-helpers        | [github][68]  | [atmosphere][69]  |               | 
| matb33:collection-hooks           | [github][70]  | [atmosphere][71]  |               | 
| reywood:publish-composite         | [github][72]  | [atmosphere][73]  | [сайт][74]    | 
| ongoworks:security                | [github][75]  | [atmosphere][76]  |               | 
| alanning:roles                    | [github][77]  | [atmosphere][78]  | [сайт][123]   | 
| aldeed:autoform                   | [github][79]  | [atmosphere][80]  |               | 
| aldeed:collection2                | [github][81]  | [atmosphere][82]  |               | 
| aldeed:simple-schema              | [github][83]  | [atmosphere][84]  |               | 
| momentjs:moment                   | [github][85]  | [atmosphere][86]  | [сайт][87]    | 
| matteodem:easy-search             | [github][88]  | [atmosphere][89]  | [сайт][90]    | 
| matteodem:server-session          | [github][91]  | [atmosphere][92]  |               | 
| meteorhacks:kadira                | [github][93]  | [atmosphere][94]  | [сайт][95]    | 
| meteorhacks:aggregate             | [github][96]  | [atmosphere][97]  |               | 
| meteorhacks:fast-render           | [github][98]  | [atmosphere][99]  | [сайт][124]   | 
| meteorhacks:subs-manager          | [github][100] | [atmosphere][101] |               | 
| meteorhacks:unblock               | [github][102] | [atmosphere][103] |               | 
| raix:handlebar-helpers            | [github][104] | [atmosphere][105] |               | 
| yogiben:helpers                   | [github][106] | [atmosphere][107] |               | 
| zimme:collection-softremovable    | [github][107] | [atmosphere][109] |               | 
| zimme:collection-timestampable    | [github][110] | [atmosphere][111] |               | 
| u2622:persistent-session          | [github][112] | [atmosphere][113] |               | 
| tmeasday:publish-counts           | [github][114] | [atmosphere][115] |               | 
| percolatestudio:synced-cron       | [github][116] | [atmosphere][117] |               | 
| dburles:factory                   | [github][118] | [atmosphere][119] |               | 
| anti:fake                         | [github][120] | [atmosphere][121] |               | 

##Кроличья нора становится всё глубже…

Ух ты, вы должно быть упорные, раз дошли до этого места. Ладно, 
хотите взглянуть на мои суперсекретные списки?

### Сервис-провайдеры

Когда вам нужно разместить ваше приложение онлайн, есть огромное 
количество сервис-провайдеров, доступных для разработчика. Ниже несколько
из них, которые служат целям Meteor-сообщества (и делают отличную работу),
поэтому я решил озвучить их названия:

*   [Kadira][19] — отслеживание производительности
*   [Modulus][20] — хостинг (используйте промо-код «Metpodcast», чтобы 
получить кредит в $25)
*   [Compose][21] — хостинг Mongo БД с Oplog

### Блоги, блоги, новости и всё остальное (в произвольном порядке) 

Пойдём выпьем со мной чего-нибудь, что остудит нас после Meteor… Увидишь, 
мы будем не одни:

- [Crater.io][125] — агрегатор новостей
- [Meteor Weekly][126] — агрегатор новостей
- [Meteor's Official Blog][127] — блог
- [Josh Owens][128] — блог
- [Discover Meteor][129] — блог
- [The Meteor Chef][130] — блог
- [Differential][131] — блог
- [Gentlenode][132] — блог
- [MeteorHacks][133] — блог
- [Meteor Tips][134] — блог
- [PEM][135] — блог
- [Manuel Schoebel][136] — блог
- [Practical Meteor][137] — блог
- [Lukasz Kups][138] — блог
- [David Burles][139] — блог
- [The Meteor Podcast][140] — подкаст
- [Meteor Devshops][141] — YouTube
- [Josh Owens][142] — YouTube
- [George McKnight][143] — YouTube
- [Arunoda Susiripala][144] — YouTube
- [David Turnball][145] — YouTube
- [Sasi Kanth][146] — YouTube
- [Vianney Lecroart][147] — Medium
- [Space Camp][148] — Medium
- [Dominus][149] — Medium
- [Arunoda Susiripala][150] — Medium
- [Sacha Greif][151] — Medium
- [Paul van Zyl][152] — Medium

Если я кого-то забыл, дайте мне знать на ([@_benstr][1]) или [@joshowens][22]. 

### Другие статьи вроде этой

- [Best Learning Resources for Meteor.js][154] от Stephan Hochhaus
- [Learn Meteor.js Properly][155] от Richard ?

 [1]: https://twitter.com/_benstr
 [2]: http://meteor.com
 [3]: img/now-what.gif
 [4]: http://docs.meteor.com/#/full/
 [5]: https://www.youtube.com/watch?v=QSUnBPv4iQ0
 [6]: http://nodejs.org/
 [7]: http://cordova.apache.org/
 [8]: http://www.elasticsearch.org/
 [9]: http://ionicframework.com/
 [10]: http://meteoric.github.io/
 [11]: img/lawnmower.gif
 [12]: https://www.youtube.com/watch?v=nMtgFZSdtwk
 [13]: https://www.meteor.com/projects
 [14]: https://atmospherejs.com/meteor/blaze
 [15]: https://atmospherejs.com/meteor/spacebars
 [16]: https://atmospherejs.com/meteor/tracker
 [17]: https://www.meteor.com/utilities
 [18]: https://atmospherejs.com/
 [19]: https://kadira.io
 [20]: https://modulus.io
 [21]: https://compose.io
 [22]: https://twitter.com/joshowens
 [23]: http://www.codecademy.com/en/tracks/javascript
 [24]: http://linuxcommand.org/learning_the_shell.php
 [25]: http://www.codecademy.com/tracks/web
 [26]: http://en.wikipedia.org/wiki/JSON
 [27]: http://www.mongodb.org/
 [28]: http://handlebarsjs.com/
 [29]: https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-
 [30]: https://guides.github.com/
 [31]: http://www.codecademy.com/en/tracks/jquery
 [32]: http://lesscss.org/
 [33]: http://sass-lang.com/
 [34]: http://underscorejs.org/
 [35]: https://lodash.com/
 [36]: http://getbootstrap.com/
 [37]: https://www.meteor.com/install
 [38]: http://meteortips.com/
 [39]: https://www.youtube.com/channel/UC4-DIsbr23Z-rPe_F4JAH9w
 [40]: https://github.com/awatson1978/meteor-cookbook
 [41]: https://discovermeteor.com/
 [42]: http://www.manning.com/hochhaus/
 [43]: http://8daysofmeteor.com/
 [44]: http://www.meteortesting.com/
 [45]: http://meteorjs.club/learn
 [46]: http://meteorjs.club/testing-meteorjs
 [47]: https://bulletproofmeteor.com/
 [48]: https://www.eventedmind.com/
 [49]: https://github.com/meteor/meteor/tree/devel/packages/accounts-password
 [50]: https://atmospherejs.com/meteor/accounts-password
 [51]: http://docs.meteor.com/#/full/accounts_api
 [52]: https://github.com/meteor-useraccounts/core
 [53]: https://atmospherejs.com/useraccounts
 [54]: http://useraccounts.meteor.com/
 [55]: https://atmospherejs.com/meteor/reactive-var
 [56]: http://docs.meteor.com/#/full/reactivevar
 [57]: https://atmospherejs.com/meteor/reactive-dict
 [58]: https://github.com/eventedmind/iron-router/
 [59]: https://atmospherejs.com/iron/router
 [60]: http://eventedmind.github.io/iron-router/
 [61]: https://github.com/zimme/meteor-iron-router-active
 [62]: https://atmospherejs.com/zimme/iron-router-active
 [63]: https://github.com/zimme/meteor-iron-router-auth/
 [64]: https://atmospherejs.com/zimme/iron-router-auth
 [65]: https://github.com/DerMambo/ms-seo
 [66]: https://atmospherejs.com/manuelschoebel/ms-seo
 [67]: http://www.manuel-schoebel.com/blog/meteor-and-seo
 [68]: https://github.com/dburles/meteor-collection-helpers/
 [69]: https://atmospherejs.com/dburles/collection-helpers
 [70]: https://github.com/matb33/meteor-collection-hooks
 [71]: https://atmospherejs.com/matb33/collection-hooks
 [72]: https://github.com/englue/meteor-publish-composite/
 [73]: https://atmospherejs.com/reywood/publish-composite
 [74]: http://braindump.io/meteor/2014/09/12/publishing-reactive-joins-in-meteor.html
 [75]: https://github.com/ongoworks/meteor-security/
 [76]: https://atmospherejs.com/ongoworks/security
 [77]: https://github.com/alanning/meteor-roles/
 [78]: https://atmospherejs.com/alanning/roles
 [79]: https://github.com/aldeed/meteor-autoform/
 [80]: https://atmospherejs.com/aldeed/autoform
 [81]: https://github.com/aldeed/meteor-collection2/
 [82]: https://atmospherejs.com/aldeed/collection2
 [83]: https://github.com/aldeed/meteor-simple-schema/
 [84]: https://atmospherejs.com/aldeed/simple-schema
 [85]: https://github.com/moment/moment/
 [86]: https://atmospherejs.com/momentjs/moment
 [87]: http://momentjs.com/
 [88]: https://github.com/matteodem/meteor-easy-search/
 [89]: https://atmospherejs.com/matteodem/easy-search
 [90]: https://github.com/matteodem/meteor-easy-search/wiki
 [91]: https://github.com/matteodem/meteor-server-session/
 [92]: https://atmospherejs.com/matteodem/server-session
 [93]: https://github.com/meteorhacks/kadira/
 [94]: https://atmospherejs.com/meteorhacks/kadira
 [95]: https://kadira.io/
 [96]: https://github.com/meteorhacks/meteor-aggregate/
 [97]: https://atmospherejs.com/meteorhacks/aggregate
 [98]: https://github.com/meteorhacks/fast-render/
 [99]: https://atmospherejs.com/meteorhacks/fast-render
 [100]: https://github.com/meteorhacks/subs-manager/
 [101]: https://atmospherejs.com/meteorhacks/subs-manager
 [102]: https://github.com/meteorhacks/unblock/
 [103]: https://atmospherejs.com/meteorhacks/unblock
 [104]: https://github.com/raix/Meteor-handlebar-helpers
 [105]: https://atmospherejs.com/raix/handlebar-helpers
 [106]: https://github.com/yogiben/meteor-helpers
 [107]:  https://atmospherejs.com/yogiben/user-helpers
 [108]: https://github.com/zimme/meteor-collection-softremovable
 [109]: https://atmospherejs.com/zimme/collection-softremovable
 [110]: https://github.com/zimme/meteor-collection-timestampable/
 [111]: https://atmospherejs.com/zimme/collection-timestampable
 [112]: https://github.com/okgrow/meteor-persistent-session/
 [113]: https://atmospherejs.com/u2622/persistent-session
 [114]: https://github.com/percolatestudio/publish-counts/
 [115]: https://atmospherejs.com/tmeasday/publish-counts
 [116]: https://github.com/percolatestudio/meteor-synced-cron/
 [117]: https://atmospherejs.com/percolatestudio/synced-cron
 [118]: https://github.com/percolatestudio/meteor-factory/
 [119]: https://atmospherejs.com/dburles/factory
 [120]: https://github.com/anticoders/meteor-fake/
 [121]: https://atmospherejs.com/anti/fake
 [122]: https://github.com/EventedMind/iron-router/blob/devel/Guide.md
 [123]: http://alanning.github.io/meteor-roles/classes/Roles.html
 [124]: https://meteorhacks.com/introducing-fast-render.html
 [125]: http://crater.io/
 [126]: https://meteorhacks.com/meteor-weekly/
 [127]: https://www.meteor.com/blog
 [128]: http://joshowens.me/
 [129]: https://www.discovermeteor.com/blog
 [130]: http://themeteorchef.com/
 [131]: http://differential.com/blog
 [132]: https://gentlenode.com/journal/meteor
 [133]: https://meteorhacks.com/
 [134]: http://meteortips.com/blog/
 [135]: http://pem-musing.blogspot.com/
 [136]: http://www.manuel-schoebel.com/blog
 [137]: http://practicalmeteor.com/
 [138]: http://lukaszkups.net/notes/
 [139]: http://meteorcapture.com/
 [140]: http://www.meteorpodcast.com/
 [141]: https://www.youtube.com/user/MeteorVideos
 [142]: https://www.youtube.com/channel/UCjRSH4MO9CR40bJQxfZMFWQ?spfreload=10
 [143]: https://www.youtube.com/channel/UC4-DIsbr23Z-rPe_F4JAH9w
 [144]: https://www.youtube.com/channel/UC6ABSyRbYDjvn87xexjreNQ
 [145]: https://www.youtube.com/channel/UCgdL1Nsxd9Dv7wig8F06R0Q
 [146]: https://www.youtube.com/channel/UCuK5KMmdJgMiPI733DOKauw
 [147]: https://medium.com/@acemtp
 [148]: https://medium.com/space-camp
 [149]: https://medium.com/@Dominus
 [150]: https://medium.com/@arunoda
 [151]: https://medium.com/@sachagreif
 [152]: https://medium.com/@pushplaybang
 [153]: http://ru.discovermeteor.com
 [154]: https://www.yauh.de/best-learning-resources-for-meteorjs/
 [155]: http://javascriptissexy.com/learn-meteor-js-properly/
