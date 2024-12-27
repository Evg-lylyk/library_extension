# Infostart Extension Library (библиотека для расширений и конфигураций)
Начиная разрабатывать расширение в 1С у нас нет библиотеки. IS Extension Library - это библиотека для расширений, в т.ч. может использоваться
и без БСП с конфигурациями на различных языках. Можно использовать как подсистему в любых конфигурациях.
Работая над Infostart Toolkit была наработана хорошая база общего кода для работы с редактором Монако, конструктором запросов, конструктором СКД,
взамодействие с БСП, форма выбора типов и т.д. Именно этот функционал ложится в фундамент.
Обратная совместимость т.е. можно смело ставить последнию версию весь старый код должен работать.

**Какие сложности на себе берет библиотека:**
* Наиболее функциональное решение по работе с редактором Монако (доработанный тонкий конструктор запросов, подскази к общим модулям, шаблоны st)
* Облегчение работы с метаданными (ИмяКоллекции, ЭтоДокумент и т.д.)
* Поддержка конфигураций с английским втроенным языком
* Поддержка конфигураций с БСП и без
* _Работа динамически с формами (добавление элементов, ревизитов, команд) (план)_
* _Общее взамодействие с различными версиями БСП в т.ч. английскими (план)_

## Подсистемы
* Базовая
* Редактор
* Конструктор запросов

## Требования и поддержка
Режим запуска: Управляемое приложение, режим совместимости: 8.3.15+,
ОС: Win + Linux, языки: Русский, Английский (язык представлений: Русский, Английский)

## Коммерческое распространение (код открыт)
1. Продукты - Расширения: 5-15% прибыли от продажи (в зависимости от ценности внутри решения)
2. Организации: 50-100 т.р.

Не приветствуется конкуренция с решениями [Infostart Toolkit](https://infostart.ru/marketplace/toolkit/)
и [Infostart DataFormWizard (УДиФ)](https://infostart.ru/marketplace/udif/), а также решения перепродающие библиотеку.
