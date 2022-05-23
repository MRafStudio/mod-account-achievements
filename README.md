# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## mod-account-achievements
- Последний статус сборки с azerothcore: [![Build Status](https://github.com/azerothcore/mod-account-achievements/workflows/core-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/mod-account-achievements)
- Следует отметить - именно [ЭТА](https://github.com/MRafStudio/mod-account-achievements) версия на azerotcore.org не опубликована и вряд ли когда нибудь будет, кроме как если предложенные мной изменения примут на AzerothCore.org

# Модуль достижений учетной записи для AzerothCore.

Позволяет делиться достижениями между персонажами вашей учетной записи.

# Оригинальный скрипт:
http://www.ac-web.org/forums/showthread.php?223586-Account-Bound-Achievements

## Порядок установки

### 1) Просто поместите модуль в папку «modules» исходного кода AzerothCore.
### 2) Перезапустите cmake и запустите чистую сборку AzerothCore.

### (Необязательно) Изменение конфигурации модуля

Если возникнет необходимость изменить конфигурацию модуля, перейдите в папку конфигурации вашего сервера и отредактируйте файл `mod_achievements.conf` по своему усмотрению.

## ВНИМАНИЕ!

В качестве действительно стоящего инструмента для создания собственных репаков, категорически рекомендую работу славного [conan513](https://github.com/conan513/TrinityBuilder/releases) выполняющего всю рутиную работу по созданию репака за Вас.
Признаюсь - не будь его, этого инструмента, возможно я никогда бы не сподвигся внести свою лепту в проект [AzerothCore](https://www.azerothcore.org/catalogue.html#/).

А по сути - просто экономьте своё время и нервы, особенно на начальном этапе познания создания своего сервера SPP WoW.
Это не реклама, это опыт - сын ошибок трудных.
