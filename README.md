﻿# Проект команды 01 hotwinter-team

## Запуск сборки проекта
В адресе вашего проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и разместите в нее папку вашего проекта. У вас может получится что то похожее на это: C:\projects\hotwinter-team

1. Клонирование проекта к себе на ПК               
```sh
git clone https://github.com/EvgeniyaRo/hotwinter-team.git
```

2. Переходим в созданную папку
```sh
cd hotwinter-team
```

3. Устанавливаем все зависимости
```sh 
npm install
```

### code guide

Соглашение по написанию кода. Общие правила которых будут придерживаться все члены команды:

* [less] - CSS препроцессор
* [Flexbox] - Для построения структуры страниц спользуем флексы
* [Bootstrap grid 4] - В сборке уже есть сетка от bootstrap-4
* [Табы] - Проверьте, что бы настройки отступов в редакторе были сделаны табами (это важно для PUG файлов)
* [Bem] - При написании кода используем BEM naming (Блок, Элемент, Модификатор)
