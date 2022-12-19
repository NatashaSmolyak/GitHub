<b>Задание по GitHub  №1 </b> <a href="https://github.com/NatashaSmolyak/GitHub/blob/main/GIT_HUB_HW_1.txt">Home Work 1</a> <p>
<b>Задание по GitHub  №2 </b> <a href="https://github.com/NatashaSmolyak/GitHub/blob/main/GIT_HUB_HW_2_Branches.txt">Home Work 2 </a>
<hr>
<p dir="auto"><strong>Задание по GitHub_1</strong></p>
<p dir="auto"><strong>JSON</strong></p>
<ol start="1" dir="auto">
<li>
<p dir="auto"> Создать внешний репозиторий c названием JSON. <code>New</code><code>Create repository</code>
</li>
</ol>
<ol start="2" dir="auto">
<li>
 <p dir="auto"> Клонировать репозиторий JSON на локальный компьютер: <code>$ git clone git@github.com:NatashaSmolyak/JSON.git</code></p>
</li>
</ol>
<ol start="3" dir="auto">
<li>
<p dir="auto">Внутри локального JSON создать файл “new.json”.     <code>$ touch  new.json</code></p>
</li>
<li>
<p dir="auto">Добавить файл под гит.          <code>$ git add new.json</code></p>
</li>
<li>
<p dir="auto">Закоммитить файл.               <code> $ git commit -m "Add new.json"</code></p>
</li>
<li>
<p dir="auto">Отправить файл на внешний GitHub репозиторий.  <code>$ git push</code></p>
</li>
<li>
<p dir="auto">Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.</p>
</li>
</ol>
<p dir="auto">Открываем для редактирования: <code>$ vim new.json</code></p>
<p dir="auto">Нажимаем клавишу <code>"i"</code> Вводим текст в формате JSON</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>{
 "Person name": "Natasha Smolyak",
 "Person age": 51,
 "Number of pets": 0,
 "Salary": "2500"
}
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
 &quot;Person name&quot;: &quot;Natasha Smolyak&quot;,
 &quot;Person age&quot;: 51,
 &quot;Number of pets&quot;: &quot;0&quot;,
 &quot;Salary&quot;: &quot;2500&quot;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">Cохраняем и выходим: <code>"ESC" ":wq"</code></p>
<ol start="8" dir="auto">
<li>
<p dir="auto">Отправить изменения на внешний репозиторий.  <code>$ git commit -am "Modified new.json"</code>
<code>$ git push</code></p>
</li>
<li>
<p dir="auto">Создать файл preferences.json    <code>$ touch preferences.json</code></p>
</li>
<li>
<p dir="auto">В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.</p>
</li>
</ol>
<p dir="auto">Открываем файл для редактирования: <code>$ vim preferences.json</code></p>
<p dir="auto">Нажимаем клавишу <code>"i"</code> Вводим текст в формате JSON</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>{
 "Favorite movie": "Brilliantovaya ruka",
 "Favorite series": "Interni",
 "Favorite food": "Golubtsy",
 "Favorite time of year": "Spring",
 "Country you'd like to visit": "Iceland"
}
</code> 

</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
 &quot;Favorite movie&quot;: &quot;Brilliantovaya ruka&quot;,
 &quot;Favorite series&quot;: &quot;Interni&quot;,
 &quot;favorite food&quot;: &quot;Golubtsy&quot;,
 &quot;favorite time of year&quot;: &quot;Spring&quot;,
 &quot;country you'd like to visit&quot;: &quot;Iceland&quot;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
   
<path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">Cохраняем и выходим: <code>"ESC" ":wq"</code></p>
<ol start="14" dir="auto">
<li>Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON</li>
</ol>
<p dir="auto">Создаём файл: <code>$ touch skills.json</code></p>
<p dir="auto">Открываем файл для редактирования: <code> $ vim skills.json</code></p>
<p dir="auto">нажать клавишу <code>"i"</code> ввести текст</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>{
    "1.": "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",
    "2.": "Клиент-серверная архитектура.",
    "3.": "HTTP Методы запросов на сервер.",
    "4.": "Коды ответов HTTP сервера.",
    "5.": "Структуры HTTP запросов и ответов.",
    "6.": "Что такое JSON, XML. Их структура.",
    "7.": "Тестирование API через Postman (JS, автотесты API).",
    "8.": "Снятие и чтение логов c внешнего сервера.",
    "9.": "Сниффинг http web трафика через Charles и Fiddler.",
    "10.": "Dev Tools веб браузеров (Google Chrome, FireFox).",
    "11.": "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов).",
    "12.": "Мобильное тестирование.",
    "13.": "Особенность iOS, Android, гайдлайны.",
    "14.": "Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят).",
    "15.": "Сборка Android приложений на Android Studio.",
    "16.": "ADB (управление андройд девайсами).",
    "17.": "Настройка прокси и vpn на iOS и Android.",
    "18.": "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
    "19.": "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса).",
    "20.": "Основы bash скриптинг, автоматизация рутинных задач на сервере.",
    "21.": "Доступ к удалённым серверам.",
    "22.": "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join, Group, функции SUM, COUNT, AVG, MAX, MIN, подзапросы).",
    "23.": "База данных Postgres (установка, настройка и использование).",
    "24.": "Нереляционная база данных Redis (установка, настройка и использование).",
    "25.": "Нагрузочное тестирование в Jmeter.",
    "26.": "Методология разработки Scrum.",
    "27.": "Основы Java Script."
    "28.": "Python. (Изучение основ. Создание клиент серверного приложения)."
} </code>

</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
    &quot;1.&quot;: &quot;Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.&quot;,
    &quot;2.&quot;: &quot;Клиент-серверная архитектура.&quot;,
    &quot;3.&quot;: &quot;HTTP Методы запросов на сервер.&quot;,
    &quot;4.&quot;: &quot;Коды ответов HTTP сервера.&quot;,
    &quot;5.&quot;: &quot;Структуры HTTP запросов и ответов.&quot;,
    &quot;6.&quot;: &quot;Что такое JSON, XML. Их структура.&quot;,
    &quot;7.&quot;: &quot;Тестирование API через Postman (JS, автотесты API).&quot;,
    &quot;8.&quot;: &quot;Снятие и чтение логов c внешнего сервера.&quot;,
    &quot;9.&quot;: &quot;Сниффинг http web трафика через Charles и Fiddler.&quot;,
    &quot;10.&quot;: &quot;Dev Tools веб браузеров (Google Chrome, FireFox).&quot;,
    &quot;11.&quot;: &quot;VPN. (Как работает, зачем нужен, как использовать, варианты инструментов).&quot;,
    &quot;12.&quot;: &quot;Мобильное тестирование.&quot;,
    &quot;13.&quot;: &quot;Особенность iOS, Android, гайдлайны.&quot;,
    &quot;14.&quot;: &quot;Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят).&quot;,
    &quot;15.&quot;: &quot;Сборка Android приложений на Android Studio.&quot;,
    &quot;16.&quot;: &quot;ADB (управление андройд девайсами)&quot;,
    &quot;17.&quot;: &quot;Настройка прокси и vpn на iOS и Android.&quot;,
    &quot;18.&quot;: &quot;Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.&quot;,
    &quot;19.&quot;: &quot;Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса).&quot;,
    &quot;20.&quot;: &quot;Основы bash скриптинг, автоматизация рутинных задач на сервере.&quot;,
    &quot;21.&quot;: &quot;Доступ к удалённым серверам.&quot;,
    &quot;22.&quot;: &quot;CОсновы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join, Group, функции SUM, COUNT, AVG, MAX, MIN, подзапросы).&quot;,
    &quot;23.&quot;: &quot;База данных Postgres (установка, настройка и использование).&quot;,
    &quot;24.&quot;: &quot;Нереляционная база данных Redis (установка, настройка и использование).&quot;,
    &quot;25.&quot;: &quot;Нагрузочное тестирование в Jmeter.&quot;,
    &quot;26.&quot;: &quot;Методология разработки Scrum.&quot;,
    &quot;27.&quot;: &quot;Основы Java Script.&quot;,
    &quot;28.&quot;: &quot;Python. (Изучение основ. Создание клиент серверного приложения).&quot;
}" tabindex="0" role="button" style="display: inherit;">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success m-2 d-none">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">Cохраняем и выходим: <code>"ESC" ":wq"</code></p>

<ol start="15" dir="auto">
<li>Отправить сразу 2 файла на внешний репозиторий.</li>
</ol>
<p dir="auto"><code>$ git add .</code></p>
<p dir="auto"><code>$ git commit -m "Add two files: Preference and Skills"</code></p>
<p dir="auto"><code>$ git push</code></p>
<ol start="16" dir="auto">
<li>На веб интерфейсе создать файл bug_report.json.        </li>
</ol>
<p dir="auto"><code>- Add file</code></p>
<p dir="auto"><code>- Create new file</code></p>
<p dir="auto"><code>- Commit new file</code></p>

<ol start="17" dir="auto">
<li>На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.</li>
</ol>
<p dir="auto"><code>-edit this file</code></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>{
	"ID": Bug#1,
        "Environment": "Windows 10, Chrome, v: 106.0.5249.119",
	"Title": "Не происходит редирект на трейдинговую платформу при клике на кнопку [Go to platform] в pop-up окне 'We are excited to see you here!' после клика на кнопку [SELL] либо  [BUY] в таблице инструментов торговли на странице  Markets",
        "STR": "1. Открыть сайт Capital.com. 2. Выбрать лицензию ASIC. 3. Открыть burger-меню. 4. Перейти в раздел Markets. 5. В таблице инструментов торговли кликнуть по кнопке [SELL] либо [BUY] любого инструмента. 6.В pop-up окне [We are excited to see you here!] кликунть по кнопке [Go to platform]",
	"Actual result": "Не происходит редирект на трейдинговую платформу",
	"Expected result": "Редирект на трейдинговую платформу",
	"Severity": "Major",
	"Priority": "High",
        "Attachments": "Video"
}
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{
	&quot;ID&quot;:Bug#1,
        &quot;Environment&quot;: &quot;Windows 10, Chrome, v: 106.0.5249.119&quot;,
	&quot;Title&quot;: &quot;Не отображаеться предупреждающие окно в приложении при деление на ноль&quot;,
	&quot;STR&quot;: &quot;1. Открыть сайт Capital.com. 2. Выбрать лицензию ASIC. 3. Открыть burger-меню. 4. Перейти в раздел Markets. 5. В таблице инструментов торговли кликнуть по кнопке [SELL] либо [BUY] любого инструмента. 6.В pop-up окне [We are excited to see you here!] кликунть по кнопке [Go to platform]&quot;,
	&quot;Actual result&quot;: &quot;Не происходит редирект на трейдинговую платформу&quot;,
	&quot;Expected result&quot;: &quot;Редирект на трейдинговую платформу&quot;,
	&quot;Severity&quot;: &quot;Major&quot;,
	&quot;Priority&quot;: &quot;High&quot;,
        &quot;Attachments&quot;: &quot;Video&quot;
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>

<ol start="18" dir="auto">
<li>Сделать Commit changes (сохранить) изменения на веб интерфейсе.</li>
</ol>
<p dir="auto"><code>- Edit this file</code></p>
<p dir="auto"><code>- В строке Commit changes записываем Update file Bug_report.json</code></p>
<p dir="auto"><code> - Commit changes</code></p>
<ol start="19" dir="auto">
<li>Синхронизировать внешний и локальный репозиторий JSON.</li>
</ol>	
<p dir="auto"><code> $ git fetch</code></p>
<p dir="auto"><code> $ git pull</code></p>
