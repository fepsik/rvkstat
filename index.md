<head>
<link rel="shortcut icon" type="image/x-icon" href="as.ico">
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-114798296-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-114798296-1');
</script>
</head>

<p align="center">
<a href="https://selesnow.github.io/"><img src="https://alexeyseleznev.files.wordpress.com/2017/03/as.png" height="80"></a>
</p>

<style type="text/css">

ul.nm_ul {
  list-style: none; /*убираем маркеры списка*/
  margin: 0; /*убираем отступы*/
  padding-left: 0; /*убираем отступы*/
  margin-top:25px; /*делаем отступ сверху*/
  background:#DCDCDC; /*добавляем фон всему меню*/
  height: 30px; /*задаем высоту*/
}
a.nm_a {
  text-decoration: none; /*убираем подчеркивание текста ссылок*/
  background:#696969; /*добавляем фон к пункту меню*/
  color:#fff; /*меняем цвет ссылок*/
  padding:0px 7px; /*добавляем отступ*/
  font-family: arial; /*меняем шрифт*/
  line-height:30px; /*ровняем меню по вертикали*/
  display: block; 
  border-right: 1px solid #677B27; /*добавляем бордюр справа*/
  -moz-transition: all 0.3s 0.01s ease; /*делаем плавный переход*/
  -o-transition: all 0.3s 0.01s ease;
  -webkit-transition: all 0.3s 0.01s ease;
}
a.nm_a:hover {
  background:#FF8C00;/*добавляем эффект при наведении*/
}
li.nm_li {
  float:left; /*Размещаем список горизонтально для реализации меню*/
  position:relative; /*задаем позицию для позиционирования*/
}
     
    /*Стили для скрытого выпадающего меню*/
    li.nm_li > ul.nm_ul {
        position:absolute;
        top:5px;
        display:none;   
    }
     
    /*Делаем скрытую часть видимой*/
    li.nm_li:hover > ul.nm_ul {
        display:block; 
        width:280px;  /*Задаем ширину выпадающего меню*/      
    }
   li.nm_li:hover > ul.nm_ul > li.nm_li {
        float:none; /*Убираем горизонтальное позиционирование*/
    }
</style>

<h2>Menu:</h2>
<center>
<ul class="nm_ul">
    <li class="nm_li"><a href="/" class="nm_a">Main</a></li>
    <li class="nm_li"><a href="/" class="nm_a">R Packages</a>
        <ul class="nm_ul">
            <li class="nm_li"><a href="/galigor" class="nm_a">galigor</a></li>
            <li class="nm_li"><a href="/ryandexdirect" class="nm_a">ryandexdirect</a></li>
            <li class="nm_li"><a href="/rym" class="nm_a">rym</a></li>
            <li class="nm_li"><a href="/rfacebookstat" class="nm_a">rfacebookstat</a></li>
            <li class="nm_li"><a href="/rvkstat" class="nm_a">rvkstat</a></li>
	    <li class="nm_li"><a href="/rmytarget" class="nm_a">rmytarget</a></li>
	    <li class="nm_li"><a href="/rmixpanel" class="nm_a">rmixpanel</a></li>
	    <li class="nm_li"><a href="/rGitHub" class="nm_a">rGitHub</a></li>
	    <li class="nm_li"><a href="/getProxy" class="nm_a">getProxy</a></li>
        </ul>
    </li>
	<li class="nm_li"><a href="#" class="nm_a">Онлайн Книги</a>
	    <ul class="nm_ul">
            <li class="nm_li"><a href="https://r-for-marketing.netpeak.net/" class="nm_a">Язык R в Интернет Маркетинге</a></li>
            <li class="nm_li"><a href="https://netpeak.net/files/whitepapers/10-fishek-web-analitiki.pdf" class="nm_a">10 фишек Google Analytics</a></li>
        </ul>
	</li>
	<li class="nm_li"><a href="#" class="nm_a">Онлайн Курсы</a>
	    <ul class="nm_ul">
            <li class="nm_li"><a href="https://learn.needfordata.ru/r" class="nm_a">Язык R в Интернет Маркетинге</a></li>
        </ul>
    </li>
    <li class="nm_li"><a href="/library" class="nm_a">Статьи</a></li>
    <li class="nm_li"><a href="https://alexeyseleznev.wordpress.com/" class="nm_a">Блог</a></li>
    <li class="nm_li"><a href="/news" class="nm_a">Новости</a></li>
    <li class="nm_li"><a href="/publications" class="nm_a">Архив</a></li>
</ul>
</center>
<Br>

# rvkstat - R пакет для работы с API Вконтакте<img src='https://raw.githubusercontent.com/selesnow/rvkstat/master/inst/logo/rvkstat.png' align="right" height="139" /></a>

## Ссылки
* [Документация](https://selesnow.github.io/rvkstat/)
* [Отчёт об ошибках и доработках](https://github.com/selesnow/rvkstat/issues)
* [Список релизов](https://github.com/selesnow/rvkstat/releases)
* [Группа в Вконтакте](https://vk.com/data_club)

## CRAN
[![Rdoc](http://www.rdocumentation.org/badges/version/rvkstat)](http://www.rdocumentation.org/packages/rvkstat)
[![rpackages.io rank](http://www.rpackages.io/badge/rvkstat.svg)](http://www.rpackages.io/package/rvkstat)
[![](https://cranlogs.r-pkg.org/badges/rvkstat)](https://cran.r-project.org/package=rvkstat)

## Содержание ReadMe пакета rvkstat

- **[Краткое описание пакета rvkstat](https://selesnow.github.io/rvkstat/#краткое-описание-пакета-rvkstat)**
- **[Как получить подробную справку по функциям пакета](https://selesnow.github.io/rvkstat/#как-получить-подробную-справку-по-функциям-пакета-rvkstat)**
- **[Что необходимо для начала работы с API Вктонтакте с помощью пакета rvkstat](https://selesnow.github.io/rvkstat/#что-необходимо-для-начала-работы-с-api-вктонтакте-с-помощью-пакета-rvkstat)**
- **[Как обойти блокировку API сервиса Вконтакте на Украине](https://selesnow.github.io/rvkstat/#как-работать-с-api-сервисом-вконтакте-на-украине)**
- **[Установка пакета rvkstat](https://selesnow.github.io/rvkstat/#установка-пакета)**
- **[Как пройти аутентификацию для работы с API Вконтакте с помощью пакета rvkstat](https://selesnow.github.io/rvkstat/#авторизация-вконтакте-для-работы-с-api)**
  - [vkGetToken](https://selesnow.github.io/rvkstat/#пример-прохождения-авторизации-с-помощью-функции-vkgettoken) - Авторизация в Вконтакте с помощью метода [Implicit Flow](https://github.com/selesnow/rvkstat#Пример-прохождения-авторизации-с-помощью-функции-vkgettoken), ключ доступа пользователя.
  - [vkGetGroupToken]() -  - Авторизация в Вконтакте с помощью метода [Implicit Flow](https://github.com/selesnow/rvkstat#Пример-прохождения-авторизации-с-помощью-функции-vkgettoken), ключ доступа сообщества.
  - [vkAuth](https://selesnow.github.io/rvkstat/#пример-прохождения-авторизации-с-помощью-функции-vkauth) - Авторизация в Вконтакте с помощью метода [Authorization Code Flow](https://vk.com/dev/authcode_flow_user)
- **[Функции доступные в пакете rvkstat](https://selesnow.github.io/rvkstat/#функции-доступные-в-пакете-rvkstat)**
  - [Функции для загрузки данных из рекламного кабинета Вконтакте](https://selesnow.github.io/rvkstat/#функции-для-загрузки-данных-из-рекламного-кабинета-вконтакте)
    - [vkGetAdCategories](https://selesnow.github.io/rvkstat/#получить-список-возможных-тематик-рекламных-объявлений-и-их-подразделов) - Получить возможные тематики рекламных объявлений и их подразделы.
    - [vkGetAdAccounts](https://selesnow.github.io/rvkstat/#получить-список-досупных-рекламных-кабинетов-вконтакте) - Получить список доступных рекламных кабинетов
    - [vkGetAdClients](https://selesnow.github.io/rvkstat/#получить-список-клиентов-из-агентского-аккаунта-вконтакте) - Получить список клиентов из агентского аккаунта
    - [vkGetAds](https://selesnow.github.io/rvkstat/#получить-список-объявлений-из-рекламного-кабинета-вконтакте) - Получить список объявлений
    - [vkGetAdsLayout](#получить-список-объявлений-из-рекламного-кабинета-вконтакте) - Возвращает описания внешнего вида рекламных объявлений.
    - [vkGetAdCampaigns](https://selesnow.github.io/rvkstat/#получить-список-рекламных-кампаний-из-рекламного-кабинета-вконтакте) - Получить список рекламных кампаний
    - [vkGetAdStatistics](https://selesnow.github.io/rvkstat/#получить-статистику-показателей-эффективности-по-рекламным-объявлениям-кампаниям-клиентам-или-всему-кабинету) - Получить статистику показателей эффективности по рекламным объявлениям, кампаниям, клиентам или всему кабинету
    - [vkGetAdCityStats](https://selesnow.github.io/rvkstat/#получить-статистику-по-охвату-аудитории-по-рекламным-кампаним-или-объявления-в-разрезе-городов) - Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе городов
    - [vkGetAdGenderStats](https://selesnow.github.io/rvkstat/#получить-статистику-по-охвату-аудитории-по-рекламным-кампаним-или-объявления-в-разрезе-пола) - Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе пола
    - [vkGetAdAgeStats](https://selesnow.github.io/rvkstat/#получить-статистику-по-охвату-аудитории-по-рекламным-кампаним-или-объявления-в-разрезе-возраста) - Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе возраста
    - [vkGetAdGenderAgeStats](https://selesnow.github.io/rvkstat/#получить-статистику-по-охвату-аудитории-по-рекламным-кампаним-или-объявления-в-разрезе-пола-и-возраста) - Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе пола и возраста
    - [vkGetAdBudget](https://selesnow.github.io/rvkstat/#получить-остаток-средств-из-рекламного-кабинета) - Получить остаток средств из рекламного кабинета
    - [vkGetAdPostsReach](https://selesnow.github.io/rvkstat/#получить-подробную-статистику-по-охвату-рекламных-записей-из-объявлений-и-кампаний-для-продвижения-записей-сообщества) - Получить подробную статистику по охвату рекламных записей из объявлений и кампаний для продвижения записей сообщества
  - [Функции для загрузки данных из сообществ Вконтакте](https://selesnow.github.io/rvkstat/#функции-для-загрузки-данных-из-сообществ-вконтакте)
    - [vkGetGroupStat](https://selesnow.github.io/rvkstat/#получить-данные-о-количестве-просмотров-посетителях-подписавшихся-и-отписавшихся-посетителей-по-дням) - Получить общую статистику по сообществу
    - [vkGetGroupStatAge](https://selesnow.github.io/rvkstat/#получить-данные-о-возрастных-группах-посетителей-по-дням) - Получить данные о посетителях сообщества по возрасту
    - [vkGetGroupStatCity](https://selesnow.github.io/rvkstat/#получить-данные-о-городах-посетителей) -Получить данные о посетителях сообщества по городам
    - [vkGetGroupStatCountries](https://selesnow.github.io/rvkstat/#получить-данные-о-странах-посетителей) - Получить данные о посетителях сообщества по странам
    - [vkGetGroupStatGender](https://selesnow.github.io/rvkstat/#получить-данные-о-поле-посетителей-по-дням) - Получить данные о посетителях сообщества по полу
    - [vkGetGroupStatGenderAge](https://selesnow.github.io/rvkstat/#получить-данные-о-половозрастной-структуре-ваших-посетителей-по-дням) - Получить данные о посетителях сообщества по полу и возрасту
    - [vkGetGroupStatPostReach ]() - Получить детальные данные по охвату по записяписям сообществ
  - [Функции для загрузки справочной инормации из Вконтакте](https://selesnow.github.io/rvkstat/#функции-для-загрузки-справочной-информации-из-вконтакте)
    - [vkGetDbCountries](https://selesnow.github.io/rvkstat/#получить-id-и-название-стран) - Получить id и название стран
    - [vkGetDbCities](https://selesnow.github.io/rvkstat/#получить-справочник-городов) - Получить справочник городов
    - [vkGetDbRegions](https://selesnow.github.io/rvkstat/#получить-справочник-регионов) - Получить справочник регионов
  - [Функции для загрузки инормации о пользователе Вконтакте](https://selesnow.github.io/rvkstat/#функции-для-загрузки-инормации-о-пользователе-Вконтакте)
    - [vkGetUserFriends](https://selesnow.github.io/rvkstat/#получиить-список-друзей-пользователя-Вконтакте) - Получить список друзей пользователя Вконтакте
    - [vkGetUserDialogs](#%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B8%D1%82%D1%8C-%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA-%D0%B4%D0%B8%D0%B0%D0%BB%D0%BE%D0%B3%D0%BE%D0%B2-%D1%82%D0%B5%D0%BA%D1%83%D1%89%D0%B5%D0%B3%D0%BE-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-%D0%B8%D0%BB%D0%B8-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B0) - Получить список диалогов текущего пользователя или сообщества
    - [vkGetUserGroups](https://selesnow.github.io/rvkstat/#получить-список-групп-и-сообществ-в-которых-состоит-пользователь-Вконтакте) - Получить список групп и сообществ в которых состоит пользователь Вконтакте
    - [vkGetUserWall](https://selesnow.github.io/rvkstat/#получить-сообщения-со-стены-пользователя-с-количеством-комментариев-лайков-и-рипостов) - Получить сообщения со стены пользователя с количеством комментариев, лайков и рипостов
- **[Список статей с примерами работы с пакетом rvkstat](https://github.com/selesnow/rvkstat/blob/master/README.md#Список-статей-с-примерами-работы-с-пакетом-rvkstat)**
	- [Как перенести данные из ВКонтакте в Power BI (Алексей Селезнёв)](https://netpeak.net/ru/blog/kak-perenesti-dannyye-iz-vkontakte-v-power-bi/)
	- [Загрузка статистики из «ВКонтакте» и Facebook в Google BigQuery — руководство (Михаил Гусев)](https://ppc.world/articles/zagruzka-statistiki-iz-vkontakte-i-facebook-v-google-bigquery/)
- **[Информация об авторе пакета](https://selesnow.github.io/rvkstat/#автор-пакета-алексей-селезнёв-head-of-analytics-dept-at-netpeak)**

### Краткое описание пакета rvkstat
Пакет rvkstat является R клиентом для работы с API социальной сети [Вконтакте](url), с помощью функций данного пакета можно получить статистику из рекламного кабинета Вконтакте, а так же данные о посетителях сообществ вконтакте по дням, в разрезе возрастных групп, пола и геолокации посетителей.

Все функции входящие в пакет rvkstat имеюи префикс vk.

Все функции пакета разделены на блоки, определить к какому блоку относится функция можно из её названия, название блока к которому относится функция идёт сразу после префикса vk:

* Блок функция **GetGroupStat** предназначем для загрузки статистики по сообществам Вконтакте.
* Блок функций **GetAd** направлен на загрузку данных из рекламного кабинета Вконтакте.
* Блок функций **GetDb** даёт возможность загрузки справочной информации из Вконтакте.
* Блок функций **GetUser** используется для загрузки данных о конкретном пользователе Вконтакте.

### Как получить подробную справку по функциям пакета rvkstat
Все функции пакета имеют подробное описание на русском языке, получить детальную справку по любой функции пакета rvkstat можно с помощь команды `help`, если вы работаете в RStudio справку так же можно получить указав `?` перед названием комапнды:

`help("vkGetAdStatistics")`	

`?vkGetAdStatistics`

### Что необходимо для начала работы с API Вктонтакте с помощью пакета rvkstat
Для работы с api вконтакте вам необходимо создать приложение, в большинстве случаев вам потребуется при создании приложения указать платформу Веб-сайт, но если вы планируете загрузить диалоги из сообщества а не из пользовательского аккаунта то необходио указать платформу Standalone-приложение.

### Создание приложения Вкнтакте для работы с API

Для создания приложения перейдите по этой <a href="https://vk.com/editapp?act=create">ссылке</a>, и выберите в разделе платформа Веб-сайт, если вы планируете загрузить диалоги из сообщества выбирайте - Standalone-приложение. 
 <p align="center"><img src="http://img.netpeak.ua/alsey/152232828829_kiss_19kb.png" data-canonical-src="http://img.netpeak.ua/alsey/152232828829_kiss_19kb.png" style="max-width:100%;"></p>

Далее, если вы создали веб приложение перейдите в меню настроек приложения, и влючите Open API:
![настройки приложения - Open API - Включить](http://img.netpeak.ua/alsey/152232852842_kiss_39kb.png)

После чего появятся настройки Open API, введите в них следующие значения:
<b>Адрес сайта: </b>http://selesnow.github.io <Br>
<b>Адрес сайта: </b>selesnow.github.io <Br>
<b>Доверенный redirect URI: </b>https://selesnow.github.io/rvkstat/getCode/get_code.html <Br>
<b>Доверенный redirect URI: </b>https://selesnow.github.io/rvkstat/getCode/get_token.html <Br>
<b>Доверенный redirect URI: </b>https://oauth.vk.com/blank.html <Br>
![Настройка Open API](http://img.netpeak.ua/alsey/152232876897_kiss_27kb.png)

Для начала работы с функциями пакета и для того, что бы с помощью [формы получения токена](##Форма-для-получения-токена-доступа-пользователя-по-схеме-implict-flow) или функции авторизации в Вконтакте получить токен разработчика используйте ID и Защищённый ключ приложения, вы в любой момент сможете найти их в настройках вашего приложения.

![ID и секрет приложения](http://img.netpeak.ua/alsey/152232895640_kiss_14kb.png)

### Как работать с API сервисом Вконтакте на Украине
Обойти блокировку API Вконтакте на Украине можно с помощью пакета [getProxy](https://github.com/selesnow/getProxy).
Процесс обхода блокировки с помозью пакета getProxy:

1. Устанавливаем пакет getProxy с помощью приведённого ниже кода:
```r
if(!"devtools" %in% installed.packages()[,1]){install.packages("devtools")}
library(devtools)
install_github("selesnow/getProxy")
```
2. Подключаем пакет getProxy с помощью комманды `library(getProxy)`.
3. Далее с помощью функции `getProy` обходим блокировку через прокси сервер, пример кода ниже:

```r
#Направляем интернет соединение через прокси сервер
getProxy(port = "3128", country = "RU", supportsHttps = TRUE, action = "start")

#Пишем код для работы с API Вконтакте с помощью функций пакета rvkstat

#Отключаемся от прокси сервера
getProxy(action = "stop")
```

### Установка пакета
Пакет rvkstat может быть установлен непосредственно из репозитория Github с помощью приведённого ниже программного кода.

#### Установка на Windows
```r
if(!"devtools" %in% installed.packages()[,1]){install.packages("devtools")}
devtools::install_github('selesnow/rvkstat')
```
#### Установка на Ubuntu, Linux, Mac
```r
if(!"devtools" %in% installed.packages()[,1]){install.packages("devtools")}
devtools::install_github('selesnow/rvkstat', subdir = "en")
```
### Авторизация вконтакте для работы с API.
Для прохождения процесса авторизации в пакете rvkstat есть три функции:

+ vkGetToken - Упрощённая авторизация по методу [Implicit Flow](https://vk.com/dev/implicit_flow_user), токен доступа пользователя выдаётся с привязкой к IP адресу, в связи с чем при смене IP адреса прийдётся проходить процедуру авторизации. Такой ключ требуется для работы почти со всеми методами нашего API, за исключением методов секции secure. Некоторые методы (как, например, users.get) можно вызывать и без access_token, но часть данных в таком случае может быть недоступна, поскольку имеет значение, для какого пользователя их нужно получить. 
+ vkGetGroupToken - Упрощённая авторизация по методу [Implicit Flow](https://vk.com/dev/implicit_flow_group), токен доступа сообщества выдаётся с привязкой к IP адресу, в связи с чем при смене IP адреса прийдётся проходить процедуру авторизации. Такой ключ позволяет работать с API от имени группы, встречи или публичной страницы. Например, с его помощью Вы можете отвечать подписчикам сообщества на сообщения, поступившие в его адрес. С ключом доступа сообщества можно вызывать те методы, которые имеют специальную пометку в общем [списке](https://vk.com/dev/methods). 
+ vkAuth - Для прохождение процесса авторизации с помощью метода [Authorization Code Flow](https://vk.com/dev/authcode_flow_user), токен полученный с помощью данной функции будет работать с любого IP.

### Форма для получения токена доступа пользователя по схеме Implict Flow
<center>
<form name="form_user_token" method="get" action="https://oauth.vk.com/authorize?">
ID приложения в Вконтакте: <br />
<input name="client_id" type="text" size="25" maxlength="30" value="" /> 
<input name="display" type="hidden" value="popup" /> 
<input name="redirect_uri" type="hidden" value="https://selesnow.github.io/rvkstat/getCode/get_token.html" />
<input name="response_type" type="hidden" value="token" /> 
<input name="scope" type="hidden" value="offline,groups,ads,stats" /> 
<input type="submit" name="enter" value="Получить токен!" />
</form> 
</center>    
<Br>

### Форма для получения токена доступа гуппы по схеме Implict Flow
<center>
<form name="form_group_token" method="get" action="https://oauth.vk.com/authorize?">
ID приложения в Вконтакте: <br />
<input name="client_id" type="text" size="25" maxlength="30" value="" /> <br /><br />
ID сообществ Вконтакте разделённых запятыми, без пробелов: <br />
<i>пример: 0001,0002,0003</i> <br />
<input name="group_ids" type="text" size="25" maxlength="30" value="" /> <br />
<input name="display" type="hidden" value="popup" /> 
<input name="redirect_uri" type="hidden" value="https://oauth.vk.com/blank.html" />
<input name="response_type" type="hidden" value="token" /> 
<input name="scope" type="hidden" value="messages,manage,photos,docs,stories" /> 
<input type="submit" name="enter" value="Получить токен!" />
</form> 
</center>    
<Br>
	
#### Пример прохождения авторизации с помощью функции vkGetToken
Для получения [ключа доступа пользователя](https://vk.com/dev/access_token?f=1.%20%D0%9A%D0%BB%D1%8E%D1%87%20%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F) по схеме [Implicit Flow](https://vk.com/dev/implicit_flow_user) воспользуйтесь следующим кодом:

`myToken <- vkGetToken(app_id = <ID Вашего Приложения>)`

Измените <ID Вашего Приложения> на ID вашего приложения, ID приложения можно получить на странице настройки приложения, как показано в разделе "[Что необходимо для начала работы с API Вктонтакте с помощью пакета rvkstat](https://github.com/selesnow/rvkstat/blob/master/README.md#Требование)".

После запуска функции откроется окно браузера, в котором вам необходимо предоставить приложению все необходимые для работы разрешения.
<p align="center"><img src="http://img.netpeak.ua/alsey/150608813338_kiss_49kb.png" data-canonical-src="http://img.netpeak.ua/alsey/150608813338_kiss_49kb.png" style="max-width:100%;"></p>

После предоставления разрешения вы будете перенаправлены на страницу https://selesnow.github.io/rvkstat/getCode/get_token.html где вам будет сгенерирован токен доступа.

 <p align="center"><img src="http://img.netpeak.ua/alsey/150608783702_kiss_86kb.png" data-canonical-src="http://img.netpeak.ua/alsey/150608783702_kiss_86kb.png" style="max-width:100%;"></p>

Скопируйте его значение и вставьте в R, в качестве ответа на запрос "Your vk token from URL parameter access_token: ".

#### Пример прохождения авторизации с помощью функции vkGetGroupToken
Для получения [ключа доступа сообществ](https://vk.com/dev/access_token?f=2.%20%D0%9A%D0%BB%D1%8E%D1%87%20%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0%20%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B0) по схеме [Implicit Flow](https://vk.com/dev/implicit_flow_group) воспользуйтесь следующим кодом:
`group_token <- vkGetGroupToken(app_id = <ID Вашего Приложения>, group_ids = <ID Сообщества>)`

После чего откроется окно браузера, в котором вам необходимо подтвердить разрещение на доступ к данным
![](http://img.netpeak.ua/alsey/151999759566_kiss_80kb.png)

Далее скопируйте токен доступа из URL на который вы были перенаправлены и вставьте в R, в качестве ответа на запрос "Your vk token from URL parameter access_token: ".
![](http://img.netpeak.ua/alsey/151999776264_kiss_15kb.png)

#### Пример прохождения авторизации с помощью функции vkAuth
`myToken <- vkAuth(app_id = <ID Вашего Приложения>, app_secret = <Защищённый Ключ Вашего Приложения>)`

Вместо <ID Вашего Приложения> укажите ID вашего приложения, вместо <Защищённый Ключ Вашего Приложения> укажите защищёный ключ вашего приложения, оба аргумента можно посмотреть на странице настройки приложения как описано в разделе "[Что необходимо для начала работы с API Вктонтакте с помощью пакета rvkstat](https://github.com/selesnow/rvkstat/blob/master/README.md#Требование)". 

После запуска функции откроется окно браузера, в котором вы должны подтвердить разрешение доступ к данным в вконтакте.
<p align="center"><img src="http://img.netpeak.ua/alsey/150608813338_kiss_49kb.png" data-canonical-src="http://img.netpeak.ua/alsey/150608813338_kiss_49kb.png" style="max-width:100%;"></p>

После предоставления разрешения вы будете перенаправлены на страницу https://selesnow.github.io/rvkstat/getCode/get_code.html где вам будет сгенерирован код для получения токена доступа.

 <p align="center"><img src="http://img.netpeak.ua/alsey/150608845717_kiss_69kb.png" data-canonical-src="http://img.netpeak.ua/alsey/150608845717_kiss_69kb.png" style="max-width:100%;"></p>

Скопируйте его значение и вставьте в R, в качестве ответа на запрос "Enter code from URL: ". После чего в рабочем окружении R появится объект myToken, который будет содержать токен доступа, срок действия токена (в данном случае токен бессрочный) и id пользователя которому был предоставлен токен доступа к API.

### Функции доступные в пакете rvkstat

#### Функции для загрузки данных из рекламного кабинета Вконтакте

#### Получить список возможных тематик рекламных объявлений и их подразделов.
```r
##Авторизация в вк
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
##Получение списка возможных тематик рекламных объявлений
vk_ad_categories <- vkGetAdCategories(access_token = my_tok$access_token)
```
##### Аргументы
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).

#### Получить список доступных рекламных кабинетов Вконтакте
```r
##Авторизация в вк
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
##Запрос списка доступных рекламных кабинетов
my_vk_acc <- vkGetAdAccounts(my_tok$access_token)
```
##### Аргументы
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).

#### Получить список клиентов из агентского аккаунта Вконтакте
```r
##Авторизация в вк
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
##Запрос списка доступных рекламных кабинетов
my_vk_clients <- vkGetAdClients(account_id = 11111111, access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).

#### Получить список объявлений из рекламного кабинета вконтакте
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
#Получаем список объявлений
my_vk_ads <- vkGetAds(account_id = 11111111, 
                      access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>client_id</b> - Идентификатор клиента, у которого запрашиваются рекламные объявления. Доступно и обязательно для рекламных агентств.
* <b>include_deleted</b> - Логическое TRUE или FALSE, флаг, задающий необходимость вывода архивных объявлений.
* <b>campaign_ids</b> - Числовой вектор, фильтр по рекламным кампаниям.
* <b>ad_ids</b> - Числовой вектор, фильтр по рекламным объявлениям.
* <b>status_names</b> - Логическое TRUE или FALSE, если значение TRUE то формат объявления, статус модерации объявления, тип оплаты, метка о возрастном ограничении объявления и статус объявления будут возвращены в виде строковых значений, если передать в аргумент status_names значение FALSE то перечисленные значения будут возвращены в виде их ID.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить описания внешнего вида рекламных объявлений.
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
#Получаем список объявлений с описанием их внешнего вида
my_vk_ads <- vkGetAdsLayout(account_id = 11111111, 
                            access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>client_id</b> - Идентификатор клиента, у которого запрашиваются рекламные объявления. Доступно и обязательно для рекламных агентств.
* <b>include_deleted</b> - Логическое TRUE или FALSE, флаг, задающий необходимость вывода архивных объявлений.
* <b>campaign_ids</b> - Числовой вектор, фильтр по рекламным кампаниям.
* <b>ad_ids</b> - Числовой вектор, фильтр по рекламным объявлениям.
* <b>status_names</b> - Логическое TRUE или FALSE, если значение TRUE то формат объявления и тип оплаты будут возвращены в виде строковых значений, если передать в аргумент status_names значение FALSE то перечисленные значения будут возвращены в виде их ID.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id - идентификатор объявления.
* campaign_id - идентификатор кампании.
* ad_format - формат объявления
* cost_type - тип оплаты (0 — оплата за переходы, 1 — оплата за показы)
* video - 1 — объявление является видеорекламой.
* title - заголовок объявления.
* description - описание объявления.
* link_url - ссылка на рекламируемый объект.
* link_domain - домен рекламируемого сайта.
* preview_link - ссылка, перейдя по которой можно просмотреть рекламное объявление так, как оно выглядит на сайте. Ссылка доступна в течение 30 минут после выполнения метода ads.getAdsLayout функции.
* image_src - url изображения объявления.

#### Получить список рекламных кампаний из рекламного кабинета вконтакте
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
#Получаем список рекламных кампаний
my_vk_campaigns <- vkGetAdCampaigns(account_id = 11111111, 
                                    access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>client_id</b> - Идентификатор клиента, у которого запрашиваются рекламные объявления. Доступно и обязательно для рекламных агентств.
* <b>include_deleted</b> - Логическое TRUE или FALSE, флаг, задающий необходимость вывода архивных объявлений.
* <b>campaign_ids</b> - Числовой вектор, фильтр по рекламным кампаниям.
* <b>status_names</b> - Логическое TRUE или FALSE, если значение TRUE то статус кампании будет возвращён в виде строкового значения, если указать значение FALSE будет возвращён ID статуса кампании.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить статистику показателей эффективности по рекламным объявлениям, кампаниям, клиентам или всему кабинету.
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

##Получаем статистику по рекламным кампаниям по дням
vk_stat_by_campaign <- vkGetAdStatistics(account_id = 11111111,
                                         ids_type = "campaign",
                                         ids = camp$id ,
                                         period = "day",
                                         date_from = "2010-01-01", 
                                         date_to = "2017-09-10",
                                         access_token = my_tok$access_token)
										
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
  * client — клиенты
  * office — кабинет
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>period</b> - Способ группировки данных по датам, допустимые значения:
  * day — статистика по дням
  * month — статистика по месяцам
  * overall — статистика за всё время
* <b>date_from</b> - Начальная дата выводимой статистики. Используется разный формат дат для разного значения параметра period
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>date_to</b> - Конечная дата выводимой статистики. Используется разный формат дат для разного значения параметра period:
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — id объекта из параметра ids
* type — тип объекта из параметра ids_type
* day (если period равен day) — день в формате YYYY-MM-DD
* month (если period равен month) — день в формате YYYY-MM
* overall (если period равен overall) — 1
* spent — потраченные средства
* impressions — просмотры
* clicks — клики
* reach (если ids_type равен ad или campaign и period равен day или month) — охват
* video_views (если ids_type равен ad) — просмотры видеоролика (для видеорекламы)
* video_views_half (если ids_type равен ad) — просмотры половины видеоролика (для видеорекламы)
* video_views_full (если ids_type равен ad) — просмотры целого видеоролика (для видеорекламы)
* video_clicks_site (если ids_type равен ad) — переходы на сайт рекламодателя из видеорекламы (для видеорекламы)
* join_rate (если ids_type равен ad или campaign) — вступления в группу, событие, подписки на публичную страницу или установки приложения (только если в объявлении указана прямая ссылка на соответствующую страницу ВКонтакте)

#### Получить остаток средств из рекламного кабинета
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")
#Получаем остаток средств из рекламного кабинета
vk_budget <- vkGetAdBudget(account_id = 11111111, 
                           access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).

#### Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе городов
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

##Получаем статистику по рекламным кампаниям по дням
vk_ad_city_stat_day <- vkGetAdCityStats(account_id = 11111111,
                                        ids_type = "campaign",
                                        ids = camp$id ,
                                        period = "day",
                                        date_from = "2010-01-01", 
                                        date_to = "2017-09-10",
                                        access_token = my_tok$access_token)
										
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>period</b> - Способ группировки данных по датам, допустимые значения:
  * day — статистика по дням
  * month — статистика по месяцам
  * overall — статистика за всё время
* <b>date_from</b> - Начальная дата выводимой статистики. Используется разный формат дат для разного значения параметра period
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>date_to</b> - Конечная дата выводимой статистики. Используется разный формат дат для разного значения параметра period:
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — id объекта из параметра ids
* type — тип объекта из параметра ids_type
* day (если period равен day) — день в формате YYYY-MM-DD
* month (если period равен month) — день в формате YYYY-MM
* overall (если period равен overall) — 1
* city_id — id города или other для остальных городов
* city_name — id города или other для остальных городов
* impressions_rate — часть аудитории, просмотревшая объявление, от 0 до 1.
* clicks_rate — часть аудитории, кликнувшая по объявлению, от 0 до 1.

#### Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе пола
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

##Получаем статистику по рекламным кампаниям по дням
vk_ad_gender_stat_day <- vkGetAdGenderStats(account_id = 11111111,
                                            ids_type = "campaign",
                                            ids = camp$id ,
                                            period = "day",
                                            date_from = "2010-01-01", 
                                            date_to = "2017-09-10",
                                            access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>period</b> - Способ группировки данных по датам, допустимые значения:
  * day — статистика по дням
  * month — статистика по месяцам
  * overall — статистика за всё время
* <b>date_from</b> - Начальная дата выводимой статистики. Используется разный формат дат для разного значения параметра period
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>date_to</b> - Конечная дата выводимой статистики. Используется разный формат дат для разного значения параметра period:
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — id объекта из параметра ids
* type — тип объекта из параметра ids_type
* day (если period равен day) — день в формате YYYY-MM-DD
* month (если period равен month) — день в формате YYYY-MM
* overall (если period равен overall) — 1
* gender — пол, f - женский, m - мужской
* impressions_rate — часть аудитории, просмотревшая объявление, от 0 до 1.
* clicks_rate — часть аудитории, кликнувшая по объявлению, от 0 до 1.

#### Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе возраста
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

##Получаем статистику по рекламным кампаниям по дням
vk_ad_age_stat_day <- vkGetAdAgeStats(account_id = 1,
                                      ids_type = "campaign",
                                      ids = camp$id ,
                                      period = "day",
                                      date_from = "2010-01-01", 
                                      date_to = "2017-09-10",
                                      access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>period</b> - Способ группировки данных по датам, допустимые значения:
  * day — статистика по дням
  * month — статистика по месяцам
  * overall — статистика за всё время
* <b>date_from</b> - Начальная дата выводимой статистики. Используется разный формат дат для разного значения параметра period
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>date_to</b> - Конечная дата выводимой статистики. Используется разный формат дат для разного значения параметра period:
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — id объекта из параметра ids
* type — тип объекта из параметра ids_type
* day (если period равен day) — день в формате YYYY-MM-DD
* month (если period равен month) — день в формате YYYY-MM
* overall (если period равен overall) — 1
* age — возрастная группа (12-18, 18-21, 21-24, 24-27, 27-30, 30-35, 35-45, 45-100)
* impressions_rate — часть аудитории, просмотревшая объявление, от 0 до 1.
* clicks_rate — часть аудитории, кликнувшая по объявлению, от 0 до 1.

#### Получить статистику по охвату аудитории по рекламным кампаним или объявления в разрезе пола и возраста
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

##Получаем статистику по рекламным кампаниям по дням
vk_ad_gender_age_stat_day <- vkGetAdGenderAgeStats(account_id = 11111111,
                                                   ids_type = "campaign",
                                                   ids = camp$id ,
                                                   period = "day",
                                                   date_from = "2010-01-01", 
                                                   date_to = "2017-09-10",
                                                   access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>period</b> - Способ группировки данных по датам, допустимые значения:
  * day — статистика по дням
  * month — статистика по месяцам
  * overall — статистика за всё время
* <b>date_from</b> - Начальная дата выводимой статистики. Используется разный формат дат для разного значения параметра period
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>date_to</b> - Конечная дата выводимой статистики. Используется разный формат дат для разного значения параметра period:
  * day: YYYY-MM-DD, пример: 2011-09-27 - 27 сентября 2011
  * month: YYYY-MM, пример: 2011-09 - сентябрь 2011
  * overall: 0
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — id объекта из параметра ids
* type — тип объекта из параметра ids_type
* day (если period равен day) — день в формате YYYY-MM-DD
* month (если period равен month) — день в формате YYYY-MM
* overall (если period равен overall) — 1
* gender - пол (f — женщины, m — мужчины)
* age — возрастная группа (12-18, 18-21, 21-24, 24-27, 27-30, 30-35, 35-45, 45-100)
* impressions_rate — часть аудитории, просмотревшая объявление, от 0 до 1
* clicks_rate — часть аудитории, кликнувшая по объявлению, от 0 до 1

#### Получить подробную статистику по охвату рекламных записей из объявлений и кампаний для продвижения записей сообщества
```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 11111111,app_secret = "H2Pk8htyFD8024mZaPHm")

##Получаем список рекламных кампаний
camp <- vkGetAdCampaigns(account_id = 11111111, access_token = my_tok$access_token)

#Получаем данные по охвату в разрезе рекламных кампаний
post_reach <- vkGetAdPostsReach(account_id = 11111111,
                                ids_type = "campaign",
                                ids = camp$id,
                                access_token = my_tok$access_token)
```
##### Аргументы
* <b>account_id</b> - Идентификатор рекламного кабинета, список всех доступных рекламных кабинетов можно получить с помщью функции vkGetAdAccounts.
* <b>ids_type</b> - Тип запрашиваемых объектов, которые перечислены в параметре ids, допустимые значения:
  * ad — объявления
  * campaign — кампании
* <b>ids</b> - Перечисленные через запятую id запрашиваемых объявлений, кампаний, клиентов или кабинета, в зависимости от того, что указано в параметре ids_type. 
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* id — ID объекта из параметра ids
* reach_subscribers - Охват подписчиков
* reach_total - Суммарный охват
* links - Переходы по ссылке
* to_group - Переходы в сообщество
* join_group - Вступления в сообщество
* report - Количество жалоб на запись
* hide - Количество скрытий записи
* unsubscribe - Количество отписавшихся участников
* video_views_start - Количество стартов просмотра видео
* video_views_3s - Количество досмотров видео до 3 секунд
* video_views_25p - Количество досмотров видео до 25 процентов
* video_views_50p - Количество досмотров видео до 50 процентов
* video_views_75p - Количество досмотров видео до 75 процентов
* video_views_100p - Количество досмотров видео до 100 процентов

### Функции для загрузки данных из сообществ Вконтакте
Во всех примерах этого раздела подразумевается что вы сначала прошли процесс авторизации с помощью функции vkAuth, пример кода ниже:

```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 1,app_secret = "H2Pk8htyFD8024mZaPHm")
```

#### Получить данные о количестве просмотров, посетителях, подписавшихся и отписавшихся посетителей по дням

```r
communityData <- vkGetGroupStat(date_from = "2016-01-01", 
                                date_to = "2016-04-01", 
                                group_id = 1, 
                                access_token = my_tok$access_token)
``` 
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные о возрастных группах посетителей по дням.

```r
communityDataAge <- vkGetGroupStatAge(date_from = "2016-01-01", 
                                      date_to = "2016-04-01", 
                                      group_id = 1, 
                                      access_token = my_tok$access_token)
```
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные о поле посетителей по дням.

```r
communityDataGender <- vkGetGroupStatGender(date_from = "2016-01-01", 
                                            date_to = "2016-04-01", 
                                            group_id = 1, 
                                            access_token = my_tok$access_token)
```
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные о половозрастной структуре ваших посетителей по дням.

```r
communityDataGenderAge <- vkGetGroupStatGenderAge(date_from = "2016-01-01", 
                                                  date_to = "2016-04-01", 
                                                  group_id = 1, 
                                                  access_token = my_tok$access_token)
```
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные о городах посетителей.

```r
communityDataCity <- vkGetGroupStatCity(date_from = "2016-01-01", 
                                        date_to = "2016-04-01", 
                                        group_id = 1, 
                                        access_token = my_tok$access_token)
```
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные о странах посетителей.

```r
communityDataCountries <- vkGetGroupStatCountries(date_from = "2016-01-01", 
                                                  date_to = "2016-04-01", 
                                                  group_id = 1, 
                                                  access_token = my_tok$access_token)
```
##### Аргументы
* <b>date_from</b> - Начальная дата выводимой статистики в формате YYYY-MM-DD.
* <b>date_to</b> - Конечная дата выводимой статистики в формате YYYY-MM-DD.
* <b>group_id</b> - Идентификатор сообщества.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить данные по охвату записей на стене сообщества
```r
## Авторизация в вк
my_tok <- vkAuth(app_id = 1, app_secret = "H2Pk8htyFD8024mZaPHm")

## Получаем список сообщений сообщества
my_vk_wall  <- vkGetUserWall(user_id = -111111,
                             access_token = my_tok$access_token) 
							 
## Получаем подрубную статистику по последним 300 записям сообщества							 
post_reach <- vkGetGroupStatPostReach(owner_id = -2222222,
                                      post_ids = my_vk_wall$id,
                                      access_token = my_tok$access_token)
```
##### Аргументы
* <b>owner_id</b> - Идентификатор сообщества — владельца записи. Указывается со знаком «минус».
* <b>post_ids</b> - Векор содержащий идентификаторы записей, обратите внимание — данные по статистике доступны только для 300 последних (самых свежих) записей на стене сообщества.
* <b>api_version</b> - Необзательный аргумент, номер версии API к которой будет выполнен запрос.
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken.

### Функции для загрузки справочной информации из Вконтакте
Во всех примерах этого раздела подразумевается что вы сначала прошли процесс авторизации с помощью функции vkAuth, пример кода ниже:

```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 1,app_secret = "H2Pk8htyFD8024mZaPHm")
```

#### Получить id и название стран
```r
##Получаем список стран
vk_countries <- vkGetDbCountries(need_all = T,
                                 code = c("RU","UA","BY"),
                                 access_token = my_tok$access_token)
```
##### Аргументы
* <b>need_all</b> - Логическое TRUE или FALSE, флаг - вернуть список всех стран.
* <b>code</b> - Текстовый вектор, двухбуквенные коды стран в стандарте ISO 3166-1 alpha-2, для которых необходимо выдать информацию. Пример c("RU","UA","BY"), список всех кодов можно посмотреть по ссылке - https://vk.com/dev/country_codes. Не обязательный аргумент.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить справочник городов
```r
##Получаем справочник городов Украины, т.к. id Украины = 2
vk_cities <- vkGetDbCities(country_id = 2,
                           access_token = my_tok$access_token)
```
##### Аргументы
* <b>country_id</b> - Идентификатор страны, полученный с помощью функции vkGetDbCountries.
* <b>region_id</b> - Идентификатор региона, города которого необходимо получить. (параметр не обязателен).}
* <b>q</b> - Строка поискового запроса. Например, "Санкт". Максимальная длина строки — 15 символов.
* <b>need_all</b> - Логическое TRUE или FALSE, флаг - вернуть список всех городов страны указанной в аргументе country_id.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

#### Получить справочник регионов
```r
##Получаем справочник городов Украины, т.к. id Украины = 2, по запросу "Оде"
vk_regions_search  <- vkGetDbRegions(country_id = 2,
                                     q = "Оде",
                                     access_token = my_tok$access_token)
```
##### Аргументы
* <b>country_id</b> - Идентификатор страны, полученный с помощью функции vkGetDbCountries.
* <b>q</b> - Строка поискового запроса. Например, "Санкт". Максимальная длина строки — 15 символов.
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

### Функции для загрузки инормации о пользователе Вконтакте
Во всех примерах этого раздела подразумевается что вы сначала прошли процесс авторизации с помощью функции vkAuth, пример кода ниже:

```r
##Авторизация в вконтакте
my_tok <- vkAuth(app_id = 1,app_secret = "H2Pk8htyFD8024mZaPHm")
```

#### Получиить список друзей пользователя Вконтакте.
```r
my_vk_friends <- vkGetUserfriends(user_id = 7437995,
                                  access_token = my_tok$access_token)
```
##### Аргументы
* <b>user_id</b> - Идентификатор пользователя, для которого необходимо получить список друзей. Если параметр не задан, то считается, что он равен идентификатору текущего пользователя.
* <b>name_case</b> - Падеж для склонения имени и фамилии пользователя. Возможные значения:
	* именительный – nom
	* родительный – gen
	* дательный – dat
	* винительный – acc
	* творительный – ins 
	* предложный – abl
	* По умолчанию - nom
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b>Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* user_id - Идентификатор пользователя.
* first_name - Имя.
* last_name - Фамилия.
* gender - Пол.
* nickname - Никнейм (отчество) пользователя.
* domain - Короткий адрес страницы. Возвращается строка, содержащая короткий адрес страницы (например, andrew). Если он не назначен, возвращается "id"+user_id, например, id35828305.
* bdate - Дата рождения. Возвращается в формате D.M.YYYY или D.M (если год рождения скрыт). Если дата рождения скрыта целиком, поле отсутствует в ответе.
* city - ID города, название города можно получить с помощью функции vkGetDbCities.
* country - ID страны, название страны можно получить с помощью функции vkGetDbCountries.
* photo_50 - Url квадратной фотографии пользователя, имеющей ширину 50 пикселей. В случае отсутствия у пользователя фотографии возвращается http://vk.com/images/camera_c.gif.
* photo_100 - Url квадратной фотографии пользователя, имеющей ширину 100 пикселей. В случае отсутствия у пользователя фотографии возвращается http://vk.com/images/camera_b.gif.
* photo_200_orig - Url фотографии пользователя, имеющей ширину 200 пикселей. В случае отсутствия у пользователя фотографии возвращается http://vk.com/images/camera_a.gif.
* has_mobile - Информация о том, известен ли номер мобильного телефона пользователя. Возвращаемые значения: 1 — известен, 0 — не известен.
* online - Информация о том, находится ли пользователь сейчас на сайте.
* can_post - Информация о том, может ли текущий пользователь оставлять записи на стене. Возможные значения: 
	* 1 — может
	* 0 — не может.
* can_see_all_posts - Информация о том, может ли текущий пользователь видеть чужие записи на стене. Возможные значения: 
	* 1 — может
	* 0 — не может.
* can_write_private_message - Информация о том, может ли текущий пользователь отправить личное сообщение. Возможные значения: 
	* 1 — может
	* 0 — не может.
* status - Статус пользователя. Возвращается строка, содержащая текст статуса, расположенного в профиле под именем пользователя.
* last_seen_time - Дата и время время последнего посещения.
* last_seen_platform - Тип платформы, через которую был осуществлён последний вход. Возможные значения: 
	* 1 — мобильная версия
	* 2 — приложение для iPhone
	* 3 — приложение для iPad
	* 4 — приложение для Android
	* 5 — приложение для Windows Phone
	* 6 — приложение для Windows 10
	* 7 — полная версия сайта.
* university - Идентификатор университета.
* university_name - Название университета.
* faculty - Идентификатор факультета.
* faculty_name - Название факультета.
* graduation - Год окончания.
* education_form - Форма обучения
* education_status - Статус (например, "Выпускник (специалист)")
* relation - Семейное положение пользователя. Возможные значения: 
	* 1 — не женат/не замужем
	* 2 — есть друг/есть подруга
	* 3 — помолвлен/помолвлена
	* 4 — женат/замужем
	* 5 — всё сложно
	* 6 — в активном поиске
	* 7 — влюблён/влюблена
	* 8 — в гражданском браке
	* 0 — не указано.}

#### Получить список групп и сообществ в которых состоит пользователь Вконтакте
```r
my_vk_community <- vkGetUserGroups(user_id = 7437995,
                                   access_token = my_tok$access_token)
```
##### Аргументы
* <b>user_id</b> - Идентификатор пользователя, для которого необходимо получить список друзей. Если параметр не задан, то считается, что он равен идентификатору текущего пользователя.
* <b>filter</b> - Текстовый вектор фильтров сообществ, которые необходимо вернуть. Возможные значения
	* admin - сообщества, в которых пользователь является администратором
	* editor - администратором или редактором
	* moder – администратором, редактором или модератором
	* groups – группы
	* publics – публичные страницы 
	* events – мероприятия
	* По умолчанию возвращаются все сообщества пользователя. 
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b>Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken

##### Возвращаемые значения
* gid - Идентификатор сообщества.
* name - Название сообщества.
* screen_name - Короткий адрес, например, apiclub.
* is_closed - Является ли сообщество закрытым. Возможные значения: 
	* 0 — открытое
	* 1 — закрытое
	* 2 — частное
* type - Тип сообщества: 
	* group — группа
	* page — публичная страница
	* event — мероприятие.
* description - Текст описания сообщества.
* wiki_page - Название главной вики-страницы.
* members_count - Количество участников.
* start_date - Дата основания.
* can_post - Информация о том, может ли текущий пользователь оставлять записи на стене сообщества. Возможные значения: 
	* 1 — может
	* 0 — не может.
* can_see_all_posts - Информация о том, разрешено ли видеть чужие записи на стене группы. Возможные значения: 
	* 1 — может
	* 0 — не может.
* activity - Строка состояния публичной страницы. У групп возвращается строковое значение, открыта ли группа или нет, а у событий дата начала.
* status - Статус сообщества.
* fixed_post - Идентификатор закрепленной записи.
* verified - Информация о том, верифицировано ли сообщество. Возможные значения: 
	* 1 — может
	* 0 — не может.
* site - Адрес сайта из поля «веб-сайт» в описании сообщества.
* can_create_topic - Информация о том, может ли текущий пользователь создать новое обсуждение в группе. Возможные значения: 
	* 1 — может,
	* 0 — не может.
* photo - URL главной фотографии с размером 50x50px.
* photo_medium - URL главной фотографии с размером 100х100px.
* photo_big - URL главной фотографии в максимальном размере.

#### Получить список диалогов текущего пользователя или сообщества
```r
library(rvkstat)
#Получаем ключ доступа для сообщества
group_token <- vkGetGroupToken(app_id = 111111, group_ids = 222222)

#Получаем список диалогов
message <- vkGetUserDialogs(access_token = group_token)
```
##### Аргументы
* <b>offset</b> - Целое число, смещение, необходимое для выборки определенного подмножества диалогов.}
* <b>count</b> - Положительное число, по умолчанию 20, максимальное значение 200, количество диалогов, которое необходимо получить. }
* <b>start_message_id</b> - Положительное число, идентификатор сообщения, начиная с которого нужно вернуть список диалогов. Деали смотрите ниже.}
* <b>preview_length</b></b> - Положительное число, количество символов, по которому нужно обрезать сообщение. Укажите 0, если Вы не хотите обрезать сообщение. (по умолчанию сообщения не обрезаются). Обратите внимание, текст обрезается по словам, точное число символов может не совпадать с указанным значением. }
* <b>unread</b> - 1 — вернуть только диалоги, в которых есть непрочитанные входящие сообщения. По умолчанию: 0.}
* <b>important</b> - 1 — вернуть диалоги с пометкой «Важные» (для сообщений сообществ).}
* <b>unanswered</b> - 1 — вернуть диалоги с пометкой «Неотвеченные» (для сообщений сообществ).}
* <b>api_version</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken}
* <b>access_token</b> - Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken}

##### Возвращаемые значения
* id	- идентификатор сообщения (не возвращается для пересланных сообщений).
* date - дата отправки сообщения.
* out - тип сообщения (0 — полученное, 1 — отправленное, не возвращается для пересланных сообщений).
* user_id	- идентификатор пользователя, в диалоге с которым находится сообщение.
* read_state - статус сообщения (0 — не прочитано, 1 — прочитано, не возвращается для пересланных сообщений).
* title - заголовок сообщения или беседы.
* body - текст сообщения.
* random_id - идентификатор, используемый при отправке сообщения. Возвращается только для исходящих сообщений.

#### Получить сообщения со стены пользователя с количеством комментариев, лайков и рипостов
```r
my_vk_wall <- vkGetUserWall(user_id = 7437995,
                            access_token = my_tok$access_token)
```
##### Аргументы
* <b>user_id</b> - Идентификатор пользователя, для которого необходимо получить список друзей. Если параметр не задан, то считается, что он равен идентификатору текущего пользователя.
* <b>domain</b> - Короткий адрес пользователя
* <b>filter</b> - определяет, какие типы записей на стене необходимо получить. Возможные значения:
	* suggests — предложенные записи на стене сообщества
	* postponed — отложенные записи
	* owner — записи владельца стены
	* others — записи не от владельца стены
	* all — все записи на стене (owner + others) 
	* По умолчанию: all. 
* <b>api_version</b> - Версия API к который вы будете обращаться, список актуальных версий доступен по [ссылке](https://vk.com/dev/versions).
* <b>access_token</b>Токен доступа к API, полученный с помощью функций vkAuth или vkGetToken


##### Возвращаемые значения
* id - Идентификатор записи.
* from_id - Идентификатор автора записи.
* to_id - Идентификатор владельца стены, на которой размещена запись.
* date - Время публикации записи
* post_type - Тип записи, может принимать следующие значения: post, copy, reply, postpone, suggest.
* text - Текст записи.
* can_delete - Информация о том, может ли текущий пользователь удалить запись 
	* 1 — может
	* 0 — не может.
* comments_count - Кличество комментариев.
* likes_count - Число пользователей, которым понравилась запись.
* reposts_count - Число пользователей, скопировавших запись.
* attachment_type - Тип медиавложения записи (фотографии, ссылки и т.п.)

## Список статей с примерами работы с пакетом rvkstat
* [Как перенести данные из ВКонтакте в Power BI](https://netpeak.net/ru/blog/kak-perenesti-dannyye-iz-vkontakte-v-power-bi/) ([Блог Netpeak](https://netpeak.net/ru/blog/)), *[Алексей Селезнёв](https://www.facebook.com/selesnow)*
* [Загрузка статистики из «ВКонтакте» и Facebook в Google BigQuery — руководство](https://ppc.world/articles/zagruzka-statistiki-iz-vkontakte-i-facebook-v-google-bigquery/) ([ppc.world](https://ppc.world/)), *[Михаил Гусев](https://ppc.world/profile/12937/)*

---

## *Автор пакета: Алексей Селезнёв, Head of Analytics Dept. at Netpeak*
<table>
    <tr>
      <td>
      <img align="right" src="https://lh3.googleusercontent.com/R-0jgJSxIIhpag2L6YCIhJVIcIWx6-Jt5UCTRJjWzJewo47u2QBnik5CRF2dNB79jmsN_BFRjVOAYfvCqFcn3UNS_thGbbxF-99c9lwBWWlFI7JCWE43K5Yk9HnIW8i8YpTDx3l28IuYswaI-qc9QosHT1lPCsVilTfXTyV2empF4S74daOJ6x5QHYRWumT_2MhUS0hPqUsKVtOoveqDnGf3cF_VsN-RfOAwG9uCeGOgNRgv_fhSr41rw4LBND4gf05nO8zMp4TZMrrcUjKvvx6qNgYDor5LFOHiRmfKISYRVkWYe4wLyGO1FgkgTDjg0300lcur2t3txVwZUgROLZdaxOLx4owa8Rc8B8VKwd3vHxjov_aVfNPT4xf9jSFBBEOI-mfYpa55ejKDw-rqTQ6miFRFWpp_hjrk9KbGyB-Z6iZvYL-2dZ6mzgpUfs2I0tEAGsV07yTzboJ0RNCByC2-U-ZVjWdp2_9Au3FFoUcdQUAmPYOVqOv4r3oLbkkJKLj2A5jp7vf4IAoExLIfJuqEf7XN7fFcv4geib029qJjBt28wnqSO6TKEwB2fesR3uPHvGB6_6NHD70UDH-aCRCK4UBeoajtU0Y8Ks8Vwxo0oZBwmoEu8gudTFBF6mDT7GjLoGLDeNxE-TG7OtWUdxsJk7yzXGW3hE-VxsMD9g=s351-no?w=100" height="150">
      </td>
      <td>
        <b>Контакты</b>
        <br>email: selesnow@gmail.com
        <br>skype: selesnow
        <br>telegram: @AlexeySeleznev
      </td>
    </tr>
    <tr>
     <table>
    <tr>
      <td>
        <a href="https://facebook.com/selesnow/">Facebook</a>
      </td>
      <td>
        <a href="https://vk.com/selesnow">Vkontakte</a>
      </td>
      <td>
        <a href="https://linkedin.com/in/selesnow">Linkedin</a>
      </td>
      <td>
        <a href="https://alexeyseleznev.wordpress.com/">Blog</a>
      </td>
      <td>
        <a href="https://github.com/selesnow/">GitHub</a>
      </td>
      <td>
        <a href="https://stepik.org/users/792428">Stepic</a>
      </td>
    </tr>
</table>
    </tr>
</table>
