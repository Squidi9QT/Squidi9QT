<p align="center"><a href="https://github.com/Squidi9QT"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.png"><img src="assets/hero-light.png" width="50.0%" alt="Squidi9QT: дизайнер, который пишет код"></picture></a><a href="https://github.com/Squidi9QT/KuBoring"><img src="assets/kuboring-light.png" width="50.0%" alt="KuBoring: шторка у выреза для macOS"></a><br><a href="https://github.com/Squidi9QT/KubPlay"><img src="assets/kubplay-light.png" width="33.37%" alt="KubPlay: игра, которая учит Python и SQL"></a><a href="https://github.com/Squidi9QT/BrandHub"><img src="assets/brandhub-light.png" width="33.25%" alt="BrandHub: аналитика рекламы в детском парке"></a><a href="https://github.com/Squidi9QT/job-analysis"><img src="assets/jobs-light.png" width="33.37%" alt="job-analysis: вакансии hh.ru с историей SCD2"></a><br><a href="https://github.com/Squidi9QT/Glassfox"><img src="assets/glassfox-light.png" width="37.05%" alt="Glassfox: Firefox в стиле Apple"></a><a href="https://github.com/Squidi9QT/Menu"><img src="assets/menu-light.png" width="32.54%" alt="Menu: меню для Claude Code"></a><a href="https://github.com/Squidi9QT/airport_simulation"><img src="assets/airport-light.png" width="30.4%" alt="airport_simulation: очередь в аэропорту на simpy"></a><br><a href="https://github.com/Squidi9QT"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.png"><img src="assets/stack-light.png" width="100.0%" alt="Стек: требования, ERD, BI, Python, pandas, SQL, PostgreSQL, SQLite, SQLAlchemy, Jupyter, matplotlib, Plotly, Streamlit, pytest, REST API, Docker, Docker Compose, Git, GitHub Actions, Bash, Swift, JavaScript, HTML и CSS. Дизайн: UI/UX, Figma, Photoshop, 3ds Max, AutoCAD"></picture></a><br><a href="https://t.me/Squidi_t9"><img src="assets/telegram-light.png" width="33.37%" alt="Написать в Telegram: @Squidi_t9"></a><a href="mailto:kub.idrissov@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/email-dark.png"><img src="assets/email-light.png" width="33.25%" alt="Почта: kub.idrissov@gmail.com"></picture></a><a href="https://github.com/Squidi9QT"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/place-dark.png"><img src="assets/place-light.png" width="33.37%" alt="Томск (UTC+7) и Алматы (UTC+5)"></picture></a><br><a href="https://github.com/Squidi9QT"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/signature-dark.png"><img src="assets/signature-light.png" width="100.0%" alt="Squidi9QT: дизайн, данные, код. Томск и Алматы"></picture></a></p>

## Кейсы

<details open>
<summary><b>KuBoring</b>: шторка у выреза экрана для macOS</summary>

**Задача.** Хотел держать музыку, файлы и буфер обмена в одном месте, прямо у выреза экрана.

**Решение.** Нативное приложение на Swift и SwiftUI. Музыка из любого плеера с текстом песен, полка для файлов, история буфера по ⌘⇧V, таймер, ИИ-сервисы, календарь с кнопкой «Войти» на созвон. Каждая функция живёт в своём модуле и включается в настройках.

**Итог.** Вышел релиз v1.0, его можно скачать и поставить. [Репозиторий →](https://github.com/Squidi9QT/KuBoring)

</details>

<details>
<summary><b>KubPlay</b>: игра, которая учит Python, pandas и SQL</summary>

**Задача.** Учить Python, pandas и SQL на задаче, похожей на работу аналитика, а не по задачникам.

**Решение.** Браузерная игра: автоматизируешь ежедневный отчёт, пишешь код и SQL-запросы, и они выполняются прямо на странице через Pyodide и SQLite, без сервера. Две кампании, конвейер из пяти станций, бесконечные дни, тёмная тема. Делал вместе с Claude.

**Итог.** Рабочая бета, после первого запуска работает без интернета. [Репозиторий →](https://github.com/Squidi9QT/KubPlay)

</details>

<details>
<summary><b>BrandHub</b>: куда перенести рекламу в детском парке ТРЦ</summary>

**Задача.** Понять, в каких зонах парка бывает нужная бренду аудитория и какие размещения стоят не там.

**Решение.** Модель данных в PostgreSQL из 8 таблиц, 5 SQL-запросов с CTE и оконными функциями, от топа зон до рекомендаций, и дашборд на Streamlit и Plotly. Запускается одной командой.

**Итог.** Дашборд показывает, какие размещения выгоднее перенести и на сколько вырастет совпадение аудитории. Это пересборка с нуля проекта, который я делал по работе, данные синтетические. [Репозиторий →](https://github.com/Squidi9QT/BrandHub)

</details>

<details>
<summary><b>job-analysis</b>: вакансии hh.ru с историей SCD2</summary>

**Задача.** Собирать вакансии с hh.ru и хранить, как каждая менялась со временем.

**Решение.** ETL на Python, хранение в PostgreSQL с историей изменений по SCD2, SQL-аналитика и интерактивное демо.

**Итог.** Демо открывается на [GitHub Pages](https://squidi9qt.github.io/job-analysis/). [Репозиторий →](https://github.com/Squidi9QT/job-analysis)

</details>

<details>
<summary><b>Glassfox</b>: Firefox в стиле Apple</summary>

**Задача.** Firefox хотелось сделать аккуратнее, в духе программ Apple.

**Решение.** Тема с вкладками-капсулами, мягкими тенями и анимациями. К ней расширение: все вкладки и любимые сайты по одному клику и радио со спокойной музыкой в боковой панели.

**Итог.** Расширение подписано в Mozilla и ставится насовсем. [Репозиторий →](https://github.com/Squidi9QT/Glassfox)

</details>

<details>
<summary><b>Menu</b>: Claude Code в одно нажатие</summary>

**Задача.** Когда скиллов и агентов в Claude Code много, команды трудно держать в голове.

**Решение.** Боковое меню прямо в Claude Code: агенты, скиллы и плагины видны списком, нажатие вставляет команду в сообщение. Внутри набор из 7 скиллов и 14 субагентов, ставится одной командой.

**Итог.** Выложил, чтобы другие могли поставить себе. [Репозиторий →](https://github.com/Squidi9QT/Menu)

</details>

<details>
<summary><b>airport_simulation</b>: очередь в аэропорту на simpy</summary>

**Задача.** Посчитать, сколько пассажиры ждут у стоек регистрации.

**Решение.** Модель очереди M/G/N на simpy: 3 стойки, 30 независимых прогонов, 95% доверительный интервал.

**Итог.** Среднее ожидание около 2,97 ± 0,53 минуты. [Репозиторий →](https://github.com/Squidi9QT/airport_simulation)

</details>
