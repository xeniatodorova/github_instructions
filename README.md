**Что такое GitHub и чем он отличается от Git**
-------------------------------------

[Git](https://skillbox.ru/media/code/chto_takoe_git_obyasnyaem_na_skhemakh/) — это система контроля версиями. [GitHub](https://github.com/) это облачная платформа для хранения кода. Здесь можно попрактиковаться в разработке и придумать что-то свое, найти множество open-source проектов, передовых технологий, различных функций и дизайнов. А еще вы можете создавать сайты бесплатно напрямую из репозитория!

### **Регистрация и установка**

Зайдите на GitHub и создайте свой аккаунт. В принципе, этим можно и ограничиться. При желании можете установить Git. Но для работы с GitHub это вовсе не обязательно. Однако если вы планируете заниматься проектами на локальном компьютере, то установка вам все-таки нужна.

### **Репозиторий и работа с ним**

**Репозиторий** — это место, в котором вы систематизируете свой проект. Здесь вы храните файлы, папки, видео, изображения, блокноты Jupyter Notebook, наборы данных и т.д.

Загрузить в репозиторий можно всё что угодно, но предполагается, что вы будете хранить в нём файлы с исходным кодом и какие-нибудь дополнительные материалы.

Репозитории могут быть публичными и приватными, в них можно создавать другие папки и отслеживать изменения версий.

Перед началом работы с Git необходимо *инициализировать* репозиторий для проекта и правильно его подготовить. Это можно сделать на сайте GitHub.

Лучше сразу добавлять в репозиторий _**README-файл**_ с информацией о проекте. Это можно сделать в момент создания репозитория, поставив галочку в соответствующем поле.

1. Перейдите на сайт GitHub. Нажмите на значок **+** в верхнем правом углу, а затем выберите _**New repository**_.
![create repository](https://miro.medium.com/v2/resize:fit:828/format:webp/1*M3pPptyTNLOcFnWyhtiBjQ.png)
2. Придумайте имя репозитория и добавьте короткое описание.
3. Решите, будет ли этот репозиторий размещаться в открытом доступе или останется закрытым для просмотра.
![add description to the repository](https://miro.medium.com/v2/resize:fit:1050/1*gwswZ6UaUG-vbU368qEVug.png)
4. Нажмите **Initialize** this repository with a README для добавления README-файла. Настоятельно рекомендуется снабжать все проекты __*файлом-описанием*__, ведь **README** — это первая вещь, на которую люди обращают внимание при просмотре репозитория. К тому же, здесь можно разместить нужную информацию для понимания или запуска проекта.
5. Для загрузки файлов нужно зайти в нужный репозиторий, щёлкнуть на **Add file** и выбрать **Upload files**.

При желании можно уже сейчас начинать работать над проектом. Добавлять файлы, вносить в них изменения и т.д. напрямую с сайта GitHub.

Вносить изменения в проект можно двумя способами. Изменять файлы/блокноты на компьютере либо делать это на сайте GitHub.

Допустим, вам захотелось подкорректировать README-файл на сайте GitHub.

1. Для начала *перейдите* в ваш репозиторий.
2. Для выбора файла кликните по его названию (например, кликните по **README.md** для перехода к файлу-описанию).
3. В верхнем правом углу вы увидите иконку с карандашом. Нажмите на нее для внесения изменений.
4. Напишите короткое сообщение, передающее суть изменений (и подробное описание, если сочтете это нужным).
5. Нажмите кнопку Commit changes.

Но для обучения Тёмной стороне Силы работе с GitHub полезно потренироваться выполнять и другие необходимые в процессе разработки действия: клонирование/форк, объединение веток, просмотр и разрешение конфликтов и другие.

### **Просмотр файлов в репозитории**

![](https://skillbox.ru/upload/setka_images/11102921112022_e3039f248dd555899a396179b51a05be377f9973.png)

Согласитесь, что в ряде случаев удобно не скачивать исходники, а просто бегло ознакомиться с ними. Для таких простых операций вовсе не нужен десктопный клиент: все файлы можно быстро открыть в веб-версии (и код, и те же картинки). Просто щёлкните по ним для просмотра!

### **Как работать с чужим репозиторием, присоединится к проекту. Pull request.**

* Получить
Посмотреть все изображения
Today I Learned for programmers
tiloid.com
ссылку на чужой репозиторий (который собираемся клонировать)

* Залогиниться в свой github

* На новой вкладке браузера : копируем в адресную строку ссылку на чужой репозиторий

* В интерфейсе github нажимаем кнопку Fork
![pic01 :](pic01.jpg "pic01")

* Заполняем форму создания новой "вилки" и нажимаем **Create fork**
![pic02 :](pic02.jpg "pic02")

* В списке собственных репозиториев появляется ссылка на чужой репозиторий
![pic03 :](pic03.jpg "pic03")

* Заходим в форк чужого репозитория, нажимаем кнопку Code, на закладке HTTPS копирем адрес форка в clipboard
![pic04 :](pic04.jpg "pic04")

* На локальной рабочей станции, в терминале VS Code делаем clone своей версии репозитория:
git clone https://github.com/akulovokille/test345.git

* В интерфейсе VS Code (explorer) переходим в клонированный репозиторий

* Создаем новую ветку
_**git branch version2**_

* Переходим в ветку
_**git checkout version2**_

* Открываем какие-либо файлы на редактирование, вносим изменения, сохраняем локально

* Готовим изменные файлы для нового коммита
_**git add**_ .

* Делаем коммит
_**git commit**_ -m "Lines 05 and 10 have been changed"

* Отправляем свою версию в свой GitHub
_**git push**_

* На сайте GitHub нажимаем кнопку **Pull request** для отправки изменений на модерацию хозяину репозитория. 

P.s. У меня случилась накладка, поэтому не будет всех коммитов. Прошу прощения.