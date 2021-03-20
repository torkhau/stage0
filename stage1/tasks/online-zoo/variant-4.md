# Вариант #4

Выполнить задание согласно макету автора *Маргарита Григориева*: **[online zoo](https://www.figma.com/file/aBvQMVmI665DtzprpiniuH/online-zoo?node-id=0%3A1)**


## Создание макета: неделя #1+2

Выполняется создание всех страниц для ширины экрана **1920px**.


### Технические требования

Максимальный балл: **80**


#### Общие

Все фоновые элементы макета должны растягиваться на всю доступную ширину экрана, если ширина больше 1920px. При этом направляющие должны сохраняться в исходном размере, 1160px. Важно, что ни в коем случае, на странице не должна появляться горизонтальная полоса прокрутки. О таких случаях будет сказано в технических требованиях соотвествующих блоков.

Для создания вертикальных отступов лучше использовать вертикальные margin на блоках высшего порядка, насколько это возможно. При этом иметь ввиду, что вертикальные margin могут схлопнуться.

Для создания многоколоночных структур, или элементов имеющих относительное горизонтальное расположение, должно быть использовано одно из свойств:
- display: flex
- display: grid
- display: inline-block


#### Landing (20 баллов)

1. **Header** (`<header>` содержит только логотип, панель навигации и иконки соц. сетей)
- Логотип находится слева. Нажатие на логотип работает по принципу нажатия на `About`, перебрасывает нас на текущую страницу, на Landing.
- Интерактивная панель навигации.
- Нажатие на `Map` перебрасывает нас на Map.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Нажатие на `Design` перебрасывает нас на оригинальную страницу [Figma](https://www.figma.com/file/aBvQMVmI665DtzprpiniuH/online-zoo?node-id=0%3A1).
- Должен быть подсвечен первый элемент `About`. И он должен перестать быть интерактивным.
- На странице обязательно должен присутствовать один элемент `<h1>`. В нем должен быть текст `Online Zoo`.
- Хедер "липким" делать не нужно. Т.е. при скролле он остается на своей позиции.

2. Блок **Watch your favorite animal online**
- Кнопка `play` должна быть интерактивной. Нажатие перебрасывает нас на Zoos_panda.
- Бекграунд является одной картинкой.

3. Блок **How it works**
- Картинки должны находиться внутри списка с элементами `ul > li`. Размеры картинок должны быть достигнуты с помощью CSS. за исходный размер будем считать картинку на заднем плане (картинки орла или слона)
- Внтури текста есть ссылки - но они должны никуда вести, в будущем - будет открываться всплывающее окно.

4. Блок **Pets in zoo**
- Кнопки влево и вправо должны быть интерактивными.
- Карточки расположить сеткой 4х2.
- Карточки животных должны быть интерктивными. При наведении, карточка увелечивается по ширине на 20px, по высоте на 30px. Можно добавить всплывающие пояснительные надписи снизу.
- Нажатие на любую область карточки должно вести на страницу с животным. Если таких страниц не существует в дизайне, нужно запретить переход (при нажатии ничего происходить не должно).
- Кнопка `Choose your favorite` должна быть интерактивной. Нажатие ведет нас на страницу `Map`.

5. Блок **Pay and feed**
- Стрелки и иконки - это все отдельные картинки.

6. Блок **Testimonials**
- Кнопки влево и вправо должны быть интерактивными.
- Отзывы расположить сеткой 4х1.
- Кнопка `Leave Feedback` должна быть интерактивной. Нажатие никуда не ведет, в будущем - будет открываться всплывающее окно.

7. Блок **Care fro the animals you love**
- Картинки без надписей не должны быть интерактивными
- Карточки животных должны быть интерктивными (хотя бы должен меняться курсор). Нажатие на любую область карточки должно вести на страницу с животным.
- Кнопка `Choose your favorite` должна быть интерактивной.
- При нажатии на карточку ничего не должно происходить. Но рекомендуется сделать верстку модального окна `Pop up`.

8. **Footer** (`<footer>` содержит меню, доготипы, кнопки доната и соц. сетей):
- Интерактивная панель навигации. По умолчанию, элементы не имеют подсветки.
- Нажатие на `About` перебрасывает нас в верх страницы. Просто ссылка на эту же страницу.
- Нажатие на `Map` перебрасывает нас на Map.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Кнопка `Donate for volunteers` должна быть интерактивной. Нажатие никуда не ведет, в будущем - будет открываться всплывающее окно.
- Нажатие на основной логотип работает по принципу нажатия на `About`, перебрасывает нас на текущую страницу, на Landing.
- Остальные Логотипы не интерактивные. Они не должны реагировать на нажатие. Но должен появлятся тултип (атрибут title) с соотвествующей надписью (Yem Digital, Rolling Scopes School).
- Интерактивная панель соцсетей. Нажатия на соцсети могут вести просто на заглавные страницы соотвествующих ресурсов.


#### Map (10 баллов)

1. **Header** (`<header>` содержит только логотип, панель навигации и иконки соц. сетей)
- Логотип находится слева. Нажатие на логотип работает по принципу нажатия на `About`, перебрасывает нас на Landing.
- Интерактивная панель навигации.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Нажатие на `Design` перебрасывает нас на оригинальную страницу [Figma](https://www.figma.com/file/aBvQMVmI665DtzprpiniuH/online-zoo?node-id=0%3A1).
- Должен быть подсвечен элемент `Map`. И он должен перестать быть интерактивным.
- На странице обязательно должен присутствовать один элемент `<h1>`. В нем должен быть текст `Online Zoo`.
- Хедер "липким" делать не нужно. Т.е. при скролле он остается на своей позиции.

2. Блок **Map**
- Иконки животных должны занимать свою позицию относительно карты.
- При наведении на иконку животного должен появится тултип с названием животного, локация. Обязательно для 4х животных, упомянутых в дизайне. Для остальных нужно иконки сделать неинтерактивными. По желанию, можно добавить подходящее описание в тултип.

3. **Footer** (`<footer>` содержит меню, доготипы, кнопки доната и соц. сетей):
- Интерактивная панель навигации. По умолчанию, элементы не имеют подсветки.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Map` перебрасывает нас в верх страницы. Просто ссылка на эту же страницу.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Кнопка `Donate for volunteers` должна быть интерактивной. Нажатие никуда не ведет, в будущем - будет открываться всплывающее окно.
- Нажатие на основной логотип работает по принципу нажатия на `About`, перебрасывает нас на текущую страницу, на Landing.
- Остальные Логотипы не интерактивные. Они не должны реагировать на нажатие. Но должен появлятся тултип (атрибут title) с соотвествующей надписью (Yem Digital, Rolling Scopes School).
- Интерактивная панель соцсетей. Нажатия на соцсети могут вести просто на заглавные страницы соотвествующих ресурсов.


#### Zoos page (10 x 4 = 40 баллов)
Требования для типовой страницы. Переход осуществляется по ссылкам типа `.../zoos/panda` или `.../zoos/alligator`

1. **Header** (`<header>` содержит только логотип, панель навигации и иконки соц. сетей)
- Логотип находится слева. Нажатие на логотип работает по принципу нажатия на `About`, перебрасывает нас на Landing.
- Интерактивная панель навигации.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Map` перебрасывает нас на Map.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Нажатие на `Design` перебрасывает нас на оригинальную страницу [Figma](https://www.figma.com/file/aBvQMVmI665DtzprpiniuH/online-zoo?node-id=0%3A1).
- На странице обязательно должен присутствовать один элемент `<h1>`. В нем должен быть текст `Online Zoo`.
- Хедер "липким" делать не нужно. Т.е. при скролле он остается на своей позиции.

2. **Side bar** (`<aside>`)
- Панель слева: Должно быть подсвечено выбранное животное.
- Панель слева: При скролле меню с животными должно "прилипнуть" сбоку экрана. На этот счет ознакомьтесь с [position: fixed](https://developer.mozilla.org/ru/docs/Web/CSS/position#fixed_positioning).
- При наведении на иконку животного должен появится тултип с названием животного, локация.
- Выбранное животное становится не интерактивным.

3. Блок **Animal**
- Блок видео - это элемент `iframe` с видео трансляции, его можно добавить на страницу по [инструкции](https://support.google.com/youtube/answer/171780?hl=ru).
- Картинки в списке снизу - это должны быть либо превью с youtube, либо такие же `iframe` с видео. Можно все одинаковые.
- Кнопка `Feed` должна быть интерактивной.

4. Блок **Information**
- Выпадающие панели с информацией должны быть полностью раскрыты на момент верстки.

5. **Footer** (`<footer>` содержит меню, доготипы, кнопки доната и соц. сетей):
- Интерактивная панель навигации. По умолчанию, элементы не имеют подсветки.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Map` перебрасывает нас в верх страницы. Просто ссылка на эту же страницу.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Кнопка `Donate for volunteers` должна быть интерактивной. Нажатие никуда не ведет, в будущем - будет открываться всплывающее окно.
- Нажатие на основной логотип работает по принципу нажатия на `About`, перебрасывает нас на текущую страницу, на Landing.
- Остальные Логотипы не интерактивные. Они не должны реагировать на нажатие. Но должен появлятся тултип (атрибут title) с соотвествующей надписью (Yem Digital, Rolling Scopes School).
- Интерактивная панель соцсетей. Нажатия на соцсети могут вести просто на заглавные страницы соотвествующих ресурсов.

#### Contact us (10 баллов)

1. **Header** (`<header>` содержит только логотип, панель навигации и иконки соц. сетей)
- Логотип находится слева. Нажатие на логотип работает по принципу нажатия на `About`, перебрасывает нас на Landing.
- Интерактивная панель навигации.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Map` перебрасывает нас на Map.
- Нажатие на `Design` перебрасывает нас на оригинальную страницу [Figma](https://www.figma.com/file/aBvQMVmI665DtzprpiniuH/online-zoo?node-id=0%3A1).
- Должен быть подсвечен элемент `Contact Us`. И он должен перестать быть интерактивным.
- На странице обязательно должен присутствовать один элемент `<h1>`. В нем должен быть текст `Online Zoo`.
- Хедер "липким" делать не нужно. Т.е. при скролле он остается на своей позиции.

5. **Footer** (`<footer>` содержит меню, доготипы, кнопки доната и соц. сетей):
- Интерактивная панель навигации. По умолчанию, элементы не имеют подсветки.
- Нажатие на `About` перебрасывает нас на Landing.
- Нажатие на `Map` перебрасывает нас в верх страницы. Просто ссылка на эту же страницу.
- Нажатие на `Contact Us` перебрасывает нас на Contact Us (либо 404).
- Кнопка `Donate for volunteers` должна быть интерактивной. Нажатие никуда не ведет, в будущем - будет открываться всплывающее окно.
- Нажатие на основной логотип работает по принципу нажатия на `About`, перебрасывает нас на текущую страницу, на Landing.
- Остальные Логотипы не интерактивные. Они не должны реагировать на нажатие. Но должен появлятся тултип (атрибут title) с соотвествующей надписью (Yem Digital, Rolling Scopes School).
- Интерактивная панель соцсетей. Нажатия на соцсети могут вести просто на заглавные страницы соотвествующих ресурсов.


## Адаптивность: неделя #3

Сверстанные страницы адаптируюятся под следующую ширину экрана устройства:
- 1920px (уже будет готово)
- 1200px
- 640px
- 320px

### Технические требования

Максимальный балл: **40**

🚧 Задание в процессе разработки 🚧


## Функционалная часть и пользовательские события: неделя #4-5

Добавление JavaScript.

### Технические требования

Максимальный балл: **80**

🚧 Задание в процессе разработки 🚧