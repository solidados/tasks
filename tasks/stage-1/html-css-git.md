# HTML, CSS & Git Basics

| Deadline         | Repository name | Branch name |
| ---------------- | ----------- | ----------- |
| 20.09.2020 23:59 | rsschool-cv    | rsschool-cv-html    |

Ваша задача - создать своё [CV](https://ru.wikipedia.org/wiki/Curriculum_vitae) в виде html-страницы с css-стилями.  
Основу содержания данной страницы составят данные, которые вы добавили в markdown-документ из предыдущего задания [Git & Markdown](git-markdown.md)

Кроме текста на страницу необходимо добавить ваше фото или аватарку.  
Страницу нужно размещаете на GitHub Pages. Она будет доступна по адресу `https://your-github-account.github.io/rsschool-cv/`, где вместо `your-github-account` необходимо указать свой github username.

## Требования к вёрстке

- вёрстка валидная, семантическая
- при написании кода следуйте гайдлайну https://codeguide.co/
- контент размещается в блоке, который горизонтально центрируется на странице 
- страница СV должна корректно отображаться в браузере Google Chrome последней версии

## Порядок работы

1. Работу ведёте в репозитории `rsschool-cv`, созданном при выполнении предыдущего задания [Git & Markdown](git-markdown.md) 
2. От ветки `gh-pages` создайте ветку `rsschool-cv-html`
3. В ветке `rsschool-cv-html` разместите файлы вёрстки. Обратите внимание, что файл `index.html` должен находиться на верхнем уровне
4. Создайте и замержите Pull Request из ветки `rsschool-cv-html` в ветку `gh-pages`
3. В файл `README.md` в ветке `master` добавьте ссылку вида `https://your-github-account.github.io/rsschool-cv/`, в которой вместо `your-github-account` укажите свой github username. По этой ссылке будет открываться GitHub Pages с вашим CV

## Требования к коммитам

- [Названия коммитов дайте согласно гайдлайну](https://docs.rs.school/#/git-convention)

## Требования к Pull Request

- Название Pull Request даёте по названию задания
- [Описание Pull Request дайте по схеме](https://docs.rs.school/#/stage2?id=Описание-pull-request-должно-содержать)

## Как сабмитить задание

HTML, CSS & Git Basics - таск, который проверяется автоматически и в ходе кросс-чека. 

Для автоматической проверки после окончания работы над заданием и до наступления дедлайна зайдите в rs app https://app.rs.school/ выберите **Auto-Test**, в выпадающем списке выберите **HTML, CSS & Git Basics**, нажмите кнопку **Submit**. Справа отобразится результат проверки.  
До наступления дедлайна сабмитить задание можно сколько угодно раз, каждый следующий сабмит перезаписывает предыдущий.

Для проверки задания в ходе кросс-чека после создания Pull Request и до наступления дедлайна зайдите в rs app https://app.rs.school/ вкладка **Cross-Check: Submit**, выберите задание **HTML, CSS & Git Basics** и добавьте в форму ссылку на Pull Request.  
Для проверки приложения в ходе кросс-чека ссылки на проверяемые работы будут находиться в rs app вкладка **Cross-Check: Review**

## Критерии оценки

**Максимальный балл за задание 100 баллов при автотесте / 100 баллов при кросс-чеке**

## Критерии оценки при автоматической проверке

- выполнены требования к заданию +25
- выполнены требования к вёрстке +25
- выполнены требования к репозиторию, коммитам и Pull Request +50

## Критерии оценки при кросс-чеке

**Максимальный балл за задание  100**

- [ ] вёрстка валидная +10
  Для проверки валидности вёрстки используйте сервис [https://validator.w3.org/](https://validator.w3.org/#validate_by_input). Откройте код страницы CV (клик правой кнопкой по странице - в меню выберите "Просмотр кода страницы" или нажмите сочетание клавиш Ctrl+U), скопируйте его, вставьте в input, кликните Check. 
  - Надпись "Document checking completed. No errors or warnings to show." +20
  - Наличие warning + 5
  - Наличие error 0 баллов
- [ ] вёрстка семантическая +10
  В коде страницы присутствуют семантические теги HTML5, например, `article, aside, details, figcaption, figure, footer, header, main, mark, nav, section, summary, time`
  - 2 балла за каждый уникальный семантический тег HTML5, но не больше 10 баллов
- [ ] используются заголовки `h1-h6` +10 
  - 5 баллов за каждый уникальный заголовок, но не больше 10 баллов
- [ ] для оформления СV используются css-стили +10  
- [ ] контент размещается в блоке, который горизонтально центрируется на странице +10
- [ ] на странице СV присутствует изображение, пропорции изображения не искажены, у изображения есть атрибут alt +10
- [ ] контакты указаны в виде списка `ul > li` +10
- [ ] CV содержит контакты, краткую информацию о себе, навыки, примеры кода, образование, уровень английского +10
- [ ] CV выполнено на английском языке +10
- [ ] выполнены требования к репозиторию: есть ссылка на задание, скриншот страницы СV, ссылка на деплой страницы CV на GitHub Pages, указана дата дедлайна, выполнена самооценка +10

## Cross-check

- инструкция по проведению cross-check: https://docs.rs.school/#/cross-check-flow
- форма для проверки задания https://html-css-git-cross-check.netlify.app/

## Материалы

- Семантические теги в HTML https://youtu.be/bQRmGxhARhc
- Семантические теги HTML5 https://www.youtube.com/watch?v=_ih1xJyPk4A
- HTML5 Семантические элементы https://html5css.ru/html/html5_semantic_elements.php