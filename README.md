# WebFont Ubuntu

Пакет для установки веб-шрифта: Ubuntu.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-ubuntu
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-ubuntu": "github:getscope/npm-webfont-ubuntu"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Ubuntu', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-ubuntu/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-ubuntu/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-ubuntu/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-ubuntu/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-ubuntu/src/scss/_all-normal.scss";
```
