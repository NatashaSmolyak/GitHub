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
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
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
    "9.": " Снифинг http web трафика через Charles и Fiddler.",
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
    "24.": " Нереляционная база данных Redis (установка, настройка и использование).",
    "25.": "Нагрузочное тестирование в Jmeter.",
    "26.": "Методология разработки Scrum.",
    "27.": "Основы Java Script."
    "28.": "Python. (Изучение основ. Создание клиент серверного приложения)."
}
