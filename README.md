# Infostart Extension Library (библиотека для расширений)
Повторное использование кода и функциональности для расширений. Поставка подсистема или расширение.
Поставка в виде подсистемы нужна для работы механизма подсказок и удобной разработки. Установка, обновление через обработку установщик.

## Подсистемы
Базовая, Редактор

## Требования и поддержка
Режим запуска: Управляемое приложение, режим совместимости: 8.3.10+
ОС: Win + Linux, языки: Русский, Английский (язык представлений: Русский, Английский)

## Принципы разработки
* Принцип - Обратная совместимость т.е. можно смело ставить последнию версию весь старый код должен работать
* Разработка ведется в виде подсистемы при генерации релиза собирается вариант расширение. Использоватся может только один вариант подсистема либо расширение.
  Обработка установщик должна установить при необходимости расширение библиотеку и ваш продукт.
* Префикс объектов БР1 по мере развития БР2, БР3. Также расширения функционала будет производится через параметр ДополнительныеПараметры.

### Разработка (внутреннее)
* Модули ПовтИсп это часть служебного интерфейса (т.к. это часть реализации)
* Рекомендуется использовать только часть областей ПрограммныйИнтерфейс
* Различные перечисления обрамляем областью ВариантыЗначений и располагаем в конце
* Именование объектов должно группировать объекты рядом по алфавиту (по аналогии с общими модулями Общий, ОбщийСервер...),
  например картинки: БР1_ВырезатьВБуферОбмена и БР1_КопироватьВБуферОбмена лучше назвать БР1_БуферОбменаВырезать, БР1_БуферОбменаКопировать

## Распространение
Коммерческое распространение. В целях развития думаю можно будет давать бесплатно.
Продукты - Расширения: 5-20% (в зависимости от ценности внутри решения) прибыли от продажи, 50-100 тыс.р. для организация желающих использовать в своих подсистемых.
Не будет допускться конкуренцция с решениями Infostart Toolkit и Infostart DataFormWizard (УДиФ). А также решения перепродающие библиотеку.


