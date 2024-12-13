# SASS/SCSS: работа и компиляция разными способами

В [презентации](sass.pptx) рассказывается про основной функционал препроцессора, плюсы минусы.

В репозитории есть примеры компиляции SASS/SCSS в разных проектах:
- Live Sass Compiler [(sass-LiveSass)](sass-LiveSass) - расширение VSCode с его базовыми настройками в .vscode/
- PhpStorm File Watchers [(sass-PhpStorm-FileWatch)](sass-PhpStorm-FileWatch) - встроенная утилита для отслеживания изменений и компиляции файлов, настройки для SASS находятся в файле watchers.xml. Его можно импортировать в Tools/File Watchers.
- Пример с sass-cli [(sass-CompileCmd)](sass-CompileCmd) - Npm пакет sass установлен в проекте, указаны команды для компиляции и запуска в терминале.
*Можно установить и глобально*.
- Примеры со сборщиками, которые смог откопать в интернете:
  - Gulp [(sass-Gulp)](sass-Gulp)
  - Webpack [(sass-Webpack)](sass-Webpack)
  - Vite [(sass-Vite)](sass-Vite)

Также есть пример с Докером Белоцицко [compose](https://github.com/BkycHblu-6oPwuK/compose), в котором установлен node.js в контейнер [(sass-Docker)](sass-Docker).

Это даже не всё.

## Битрикс

На маркетплейсе есть два модуля компилятора, которые используют [SassPHP](https://github.com/absalomedia/sassphp) или [ScssPHP](https://github.com/scssphp/scssphp):
- https://marketplace.1c-bitrix.ru/solutions/atum.scss/
- https://marketplace.1c-bitrix.ru/solutions/olegpro.csscompiler/

Можно использовать их вместо npm.

В целом для битрикса лучше подойдёт способ со сборщиками, если сайт достаточно сложный.


#### Полезные материалы:
- Sass для самых маленьких - подробное руководство - https://webdesign-master.ru/blog/tools/sass.html
- Sass для веб-разработки - https://www.dev-notes.ru/articles/frontend/sass-for-web-development/
- The Main Features of SASS - https://dev.to/timothyrobards/the-main-features-of-sass-47k2
- Difference between @import and @use in Sass/scss - https://www.cloudhadoop.com/sass-import-vs-use
- 10 Awesome SASS (SCSS) Mixins - https://dev.to/alemesa/10-awesome-sass-scss-mixins-5ci2#font-size