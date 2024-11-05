# Базовый шаблон для проекта с Three.js

## Описание

В ходе освоения библиотеки Three.js на курсе, не редко встречается практика. Именно для этого, был создан шаблонный репозиторий, для быстрого старта очередного проекта.

Внутри шаблона:

-   Настроенная Webpack сборка
-   Настроен eslint и prettier
-   Предустановленные библиотеки `three` и `gsap`
-   Есть стартовая инициализция `three.js` сцены

## Начало работы

1. Воспользоваться данным репозиторием как шаблонным и создать себе свой репозиторий
2. Клонировать себе свой репозиторий и установить зависимости:
    ```bash
    npm i
    ```
3. Для запуска сервера разработки с hot realod:
    ```bash
    npm run dev
    ```
4. Для сборки исходников:
    ```bash
    npm run build
    ```
5. Для запуска `eslint` на коде проекта:
    ```bash
    npm run lint
    ```
6. Для запуска `eslint` на коде проекта с возможными исправлениями:
    ```bash
    npm run lint:fix
    ```
