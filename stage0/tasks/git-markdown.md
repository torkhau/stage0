#  Markdown & Git

Ваша задача - создать своё [CV](https://ru.wikipedia.org/wiki/Curriculum_vitae) в формате markdown

## Советы от EPAM HR department о том, что желательно включить в CV:

> 1. Имя и фамилия
> 2. Контакты для связи
> 3. Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении и способности быстро учиться и узнавать новое)
> 4. Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
> 5. Примеры кода \*
> 6. Опыт работы. Junior Dev может указать пройденные курсы и тренинги, перечислить учебные проекты, или проекты, выполненные на фрилансе с указанием использованных навыков и ссылками на исходный код.\** 
> 7. Образование (включая курсы, семинары, лекции, онлайн-обучение)
> 8. Английский язык (уровень английского языка, если была языковая практика, расскажите о ней)

\* Обычно идёт речь о коде, размещённом на GitHub. Но так как проект учебный, разместите небольшой примеры кода, чтобы показать, что вы умеете работать с подсветкой кода в markdown.

\** Если проектов нет, временно оставьте данный блок пустым и заполняйте его по мере выполнения заданий курса RS School.

**Обратите внимание.**  

- CV составляется на английском языке.
- при составлении CV рекомендуется указывать реальные данные, но в данном задании это не является обязательным требованием
- контакты для связи укажите актуальные: они могут использоваться будущим работодателем, ментором, студентами RS School, проверяющими ваши работы в ходе cross-check.

## Порядок работы

1. В своём GitHub аккаунте создайте публичный репозиторий с названием `rsschool-cv`
2. В главной ветке данного репозитория (`main` или `master`) должен находиться только один файл `README.md`
3. В файл `README.md` добавьте ссылку вида `https://your-github-account.github.io/rsschool-cv/cv`, в которой вместо `your-github-account` укажите свой GitHub username. После завершения работы по этой ссылке будет открываться страница CV
4. Создайте ветку `gh-pages`. В ветке `gh-pages` создайте файл `cv.md`. 
5. Используя markdown-разметку в файле `cv.md` создайте своё CV 
6. После завершения работы откройте Pull Request из ветки `gh-pages` в ветку `master`. **Мержить Pull Request не нужно!** 

## Деплой CV на GitHub Pages

CV нужно разместить на GitHub Pages. Такая страница создаётся автоматически при создании ветки `gh-pages`, если в корне этой ветки находится файл в формате .md или .html.  

Страница вашего приложения будет доступна по адресу `https://your-github-account.github.io/rsschool-cv/cv`, где вместо `your-github-account` необходимо указать свой GitHub username.

Составить ссылку на GitHub Pages можно вручную, но удобнее и проще её найти настройках репозитория. Для этого откройте настройки репозитория (кнопка с надписью Settings справа вверху) и прокрутите страницу с настройками до блока GitHub Pages). Там вы увидете надпись "Your site is published at ..." и ссылку на GitHub Pages.

Если в ветке `gh-pages` на верхнем уровне находится файл в формате .html, ссылка на GitHub Pages, которая находится в настройках репозитория, откроет html-страницу, созданную на основе этого файла. Если в ветке `gh-pages` на верхнем уровне находится файл в формате .md, к окончанию ссылки, которая находится в настройках репозитория, нужно добавить имя этого файла. 

## Требования к коммитам

- В ветке `gh-pages` должно быть не меньше 3-х коммитов.
- [Названия коммитов дайте согласно гайдлайну](https://docs.rs.school/#/git-convention)

## Требования к Pull Request

- Название Pull Request дайте по названию задания. В данном случае название Pull Request - Markdown & Git
- [Описание Pull Request дайте по схеме](https://docs.rs.school/#/pull-request-review-process?id=Требования-к-pull-request-pr)

## Как сабмитить задание

Markdown & Git - автопроверяемый таск.  
После окончания работы над заданием зайдите в rs app https://app.rs.school/, выберите **Auto-Test**, в выпадающем списке выберите **Markdown & Git**, нажмите кнопку **Submit**. Справа отобразится результат проверки.

Сабмитить задание можно сколько угодно раз, каждый следующий сабмит перезаписывает предыдущий.

## Критерии оценки

**Максимальный балл за задание +100**

- выполнены требования к репозиторию +50
- выполнены требования к коммитам и Pull Request +50

<details>
<summary>Уведомления об ошибках и их вероятные причины</summary>

1. 0 баллов и статус "Failed task requirements: No CV at ..."
   Отсутствует страница по адресу  `https://your-github-account.github.io/rsschool-cv/cv`.  
   Возможные причины: в вашем  github аккаунте нет репозитория "rsschool-cv" с веткой "gh-pages" и файлом "cv.md". Или в ветке master нет файла README.md.

3. 50 баллов и статус "Failed commit requirements: Less than 3 commits"  
   Ответ: В вашей ветке "gh-pages" менее 3 коммитов.  
   Вы можете проверить свои коммиты здесь: `https://your-github-account.github.io/rsschool-cv/commits/gh-pages`. Коммиты "Merge ..." или "Initial commit" игнорируются.

3. 50 баллов и статус "Failed commit requirements: Commits do no follow guideline ..."  
   Не все коммиты выполняются по правилам: https://docs.rs.school/#/en/git-convention Все коммиты, не отвечающие правилам, будут перечислены в статусе.   

4. 50 баллов и статус "Failed PR requirements: No Pull Request with task name (Markdown & Git)"  
   Вы не отправили Pull Request с `gh-pages` в `master`или название Pull Request не "Markdown & Git".  
   Увидеть свой PR, вы можете здесь: `https://your-github-account.github.io/rsschool-cv/pulls`
</details>

## Материалы:

- [Что такое Markdown](https://guides.hexlet.io/markdown/)
- [Полезные команды для работы с Git](https://htmlacademy.ru/blog/boost/tools/useful-commands-for-working-with-git)
