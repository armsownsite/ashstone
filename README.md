# Тестовое задание (Front-End React)

# Верстка

Необходимо сверстать тестовую страницу согласно дизайн-макетам.

Дизайн-макеты доступны в Figma по [ссылке](https://www.figma.com/file/5dPAPZRin0lfmgrmvVkg8R/frontend-trial?node-id=0%3A2). 

## Меню

### Горизонтальное меню

Горизонтальное меню должно прилипать к верхнему краю экрана, когда пользователь скроллит вниз. Спустя 200px дальнейшей прокрутки вниз меню должно плавно уезжать наверх за пределы экрана. При прокрутке наверх меню должно плавно выезжать. При прокрутке до верха страницы меню должно вставать на исходное положение.

Для прилипания использовать свойство `position: sticky`.

При изменении высоты верхней части шапки, где расположен логотип, положение и поведение прилипающего меню должны оставаться корректными.

На мобильных и планшетах горизонтальное меню не показывать.

### Мобильное меню

На дизайн-макете в левой части экрана отображено мобильное меню. На десктопе его не показывать.

Мобильное меню должно плавно выезжать при клике на иконку-гамбургер и закрываться при клике на неактивную область или иконку-крестик.

### Подменю

По ховеру на элемент меню показывать подменю. Использовать только CSS.

## Шрифты

Использовать Google Fonts. Размеры шрифтов указывать в `rem`.

## Размеры

Для отступов использовать `rem` за исключением отступов между колонками с постами, где нужно использовать `px`.

## Retina

Все изображения должны поддерживать Retina экраны и включать `srcset` атрибут (в json файле есть пути к двум картинкам).

## Посты

Использовать flex для создания трехколоночной сетки. На планшетах отображать две колонки, на мобильных одну.

Отступ между постами и горизонтальным меню - `3rem`.

# React

## **Задача**

Ваша задача - создать список постов, реализовать поиск, а также отобразить полную информацию о выбранном посте в попапе.

### **Шаг 1: Получение данных**

Вы можете получить данные с помощью **`fetch()`** или любой другой библиотеки (такой как Axios).

<aside>
💡 https://cloud.codesupply.co/endpoint/react/data.json

</aside>

### **Шаг 2: Отображение списка постов**

Создайте компонент, который будет отображать список постов в виде карточек, используя данные, полученные в шаге 1. Каждая карточка должна содержать заголовок и краткое описание поста, изображение, мета информацию.

### **Шаг 3: Поиск постов**

При вводе пользователем текста в поле поиска (визуально поле сделайте на свое усмотрение, в макете его нет), должны отображаться только те посты, заголовки или описания которых содержат этот текст.

### **Шаг 4: Полная информация о посте**

При клике на карточку поста, должен отображаться попап с полной информацией о посте (заголовок и описание). Попап должен быть закрываемым при нажатии на кнопку "Закрыть" или при клике на фон вне попапа.

### Технические моменты:

- Код должен быть написан с использованием функциональных компонентов и хуков (React Hooks).
- Для управления состоянием компонентов следует использовать хук **`useState`**.
- При обновлении состояния и/или производительности компонентов следует использовать хук **`useEffect`**.

## Конечный результат

Конечным результатом является ZIP архив.

Название файла архива должно быть в формате `front-ivanov.zip`, где `ivanov` - Ваша фамилия. 

Архив пришлите нам на почту, или закачайте на сайт/файлообменник и пришлите ссылку на скачивание.

Готовый скомпилированный проект закачайте на публичный сервер (например GitHub) и пришлите ссылку.
