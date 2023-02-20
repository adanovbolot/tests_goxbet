# Задание No1: Пройдите тест.

### 1. В чём задача тест-дизайна?

1.Ранее обнаружение дефектов

2.Мониторинг процесса тестирования

3.Оптимизация работы тестировщика 

4.Всё вышеперечисленное

    ответ: задача тест-дизайна включает все перечисленные пункты
    и направлена на обеспечение максимально эффективного и качественного тестирования продукта.

### 2. Какие виды тестирования относятся к нефункциональному? (выберите все подходящие ответы)

1. Тестирование производительности
2. Регрессионное тестирование
3. Тестирование удобства использования
4. Приёмочное тестирование

#### Тестирование производительности

    ответ: Оценка скорости, масштабируемости,
    надежности, эффективности и других аспектов работы приложения в реальных
    условиях эксплуатации. 

#### Регрессионное тестирование
    
    ответ: Тестирование функциональности
    приложения после внесения изменений в код, чтобы убедиться,
    что ранее работавшие функции продолжают работать корректно.

#### Тестирование удобства использования

    ответ: Оценка удобства и интуитивности интерфейса,
    уровня удовлетворенности пользователя, понятности документации
    и других аспектов, связанных с взаимодействием пользователя с приложением.

    
    ответ: Приемочное тестирование, хотя и не относится к функциональному тестированию,
    но тоже не является прямым видом нефункционального тестирования.
    Оно выполняется для того, чтобы оценить соответствие функциональности приложения
    ожиданиям и требованиям заказчика.

### 3. В каких случаях наиболее важно тестирование стабильности?

1. Только в случае, если приложение подразумевает работу под большой нагрузкой
2. Только в случае, если приложение подразумевает работу длительное время
3. Если заказчик настаивает
4. Всегда


    ответ: 
    Тестирование стабильности важно всегда, так как устойчивость приложения
    является одним из ключевых аспектов качества программного обеспечения.
    Ошибки, связанные с нестабильностью приложения, могут привести к сбоям,
    потере данных и даже краху системы, что может нанести ущерб бизнесу
    и пользователю.

    Однако в случаях, когда приложение подразумевает работу под большой
    нагрузкой или длительное время, тестирование стабильности
    может быть особенно критичным. В таких условиях
    приложение может столкнуться с проблемами,
    которые не проявятся при обычных условиях использования.
    Настояние заказчика на проведение тестирования стабильности также может быть
    причиной для выполнения такого тестирования, но обычно это уже включено
    в общий процесс тестирования качества программного обеспечения.

### 4. Какой из видов тестирование подразумевает отсутствие у тестировщика познания овнутренних процессах системы?

1. Тестирование серого ящика
2. Тестирование белого ящика
3. Тестирование чёрного ящика
4. Monkey-тестирование

#### Тестирование чёрного ящика
    
    Ответ:
    Тестирование чёрного ящика подразумевает отсутствие у тестировщика знания
    о внутренних процессах системы. При таком тестировании тестировщик проверяет
    функциональность приложения, не имея доступа к внутренним механизмам и коду.
    Он тестирует приложение на основе его спецификаций,
    требований и функциональных возможностей, не заботясь о том, как код был реализован.

### 5. Какой из представленных сценариев является негативным?

1. Запуск игры в демо-режиме гостем
2. Запуск игры на деньги при нулевом балансе
3. Запуск игры на деньги при положительном балансе
4. Запуск игры в демо-режиме авторизованным игроком

#### Запуск игры на деньги при нулевом балансе

    Ответ:
    Негативным сценарием является запуск игры на деньги при нулевом балансе.
    Это может привести к негативным последствиям для пользователя,
    таким как потеря денег, если он случайно запустит игру на деньги вместо
    демо-режима или если у него не хватит денег на продолжение игры.
    В таком случае следует предупредить пользователя о необходимости
    пополнения баланса перед игрой на деньги или блокировать возможность
    запуска игры на деньги при нулевом балансе.

### 6. Когда должен начинаться тест-дизайн?

1. Когда формулируются требования к системе
2. Когда готово техническое задание
3. Когда начинается разработка задачи/системы
4. Когда завершена разработка задачи/системы

#### Когда формулируются требования к системе
    
    Ответ:
    Тест-дизайн должен начинаться, когда формулируются требования к системе.
    Это позволит определить, какие требования нужно протестировать,
    а также какие виды тестирования необходимы для достижения полного покрытия
    функциональности системы. Раннее начало тест-дизайна также поможет избежать
    некоторых ошибок в процессе разработки и ускорить процесс тестирования в целом.

### 7. Что из перечисленного не является разновидностью требования?

1. Функциональные требования
2. Требования ограничения
3. Бизнес - требования
4. Регрессионные требования

#### Регрессионные требования не являются разновидностью требования.

    Ответ:
    Регрессионные требования не являются разновидностью требования.

    Регрессионное тестирование - это процесс тестирования, который
    используется для проверки, не привели ли изменения в системе
    к неожиданным побочным эффектам. Таким образом, регрессионные
    тесты не являются разновидностью требования.

### 8. Что из перечисленного позволяет проверить полноту требований? (выберите все подходящие ответы)

1. Анализ аналогичных приложений
2. Критический подход к изучению описания требования
3. Личный опыт работы с аналогичными приложениями
4. Отсутствие функциональных дефектов на данное требование

#### Анализ аналогичных приложений

    Ответ: 
    Анализ аналогичных приложений, поскольку сравнение требований с уже
    реализованными решениями может помочь выявить пропущенные требования.    

#### Критический подход к изучению описания требования

    Ответ:
    Критический подход к изучению описания требования, чтобы убедиться, что все требования покрывают
    необходимые функциональные возможности.

#### Личный опыт работы с аналогичными приложениями

    Ответ: 
    Личный опыт работы с аналогичными приложениями, что позволит определить, какие функции и возможности могут
    быть пропущены в требованиях.

### В случае, если поле ввода позволяет ввести возраст человека (до 99 лет включительно), какие из перечисленных проверок являются исчерпывающими и наиболее подходящими для корректного тестирования?
1. “0”, “18”, “56”, “99”
2. “0”, “1”, “23”, “98”, “99”
3. “-1”, “0”, “1”, “23”, “98”, “99”, “100”
4. “-1”, “0”, “1”, “35”, “98”, “99”, “100”, “”, “rr”, “1.0”, “$”
5. “-1”, “0”, “1”, “18”, “35”, “77”, “98”, “99”, “100”, “”, “rr”, “1.0”, “$”

#### 5
    
    Таким образом, ответ 5 является исчерпывающим
    и наиболее подходящим для корректного тестирования.

### Чем определяется стратегия работы с риском?
1. Целесообразностью избегания риска
2. Результатом анализа риска
3. Вероятностью возникновения риска
4. Приоритетом риска

#### Стратегия работы с риском

    
    Ответ:
    стратегия работы с риском определяется всеми перечисленными факторами:
    целесообразностью избегания риска, результатом анализа риска,
    вероятностью возникновения риска и приоритетом риска.

### Что из перечисленного является преимуществом чек - листа, по сравнению с тест кейсами? (выберите все подходящие ответы)
1. Возможность использования начинающим тестировщиком
2. Уменьшение «эффекта пестицида»
3. Лёгкость создания
4. Облегчение заведения дефектов

#### Преимущества чек-листа по сравнению с тест-кейсами:

    Ответы:
    1. Возможность использования начинающим тестировщиком.
    2. Уменьшение "эффекта пестицида" (т.е. повышение вероятности обнаружения дефектов, которые были упущены ранее).
    3. Лёгкость создания.

# Задание No2: Тест-дизайн.

### Существует игровая платформа, предоставляющая клиентам площадку для размещения их игр. В игры можно играть на деньги (только авторизованным пользователем) и в демо- режиме. В команду разработки поступило ТЗ на интеграцию новой игры в платформу. Необходимо:
1. Составить чек-лист для тестирования доработки.
2. Описать в развернутом виде по одному позитивному и негативному сценарию с
заполнением всех необходимых полей.

Требование001:

Необходимо добавить на платформу новую игру провайдера.
Провайдер: Microgaming
Игра: Goldaur Guardians
Game id: goldaurGuardiansDesktop, goldaurGuardians
Наличие джекпота – да
Тип игры – слот
Раздел: новинки
Ограничения по гео, если есть – недоступна в РФ
Валюта: USD, EUR

###  чек-лист для тестирования интеграции новой игры Microgaming Goldaur Guardians на игровой платформе:

    1. Проверьте, что новая игра добавлена на платформу в разделе "новинки".
    2. Проверьте, что игра отображается только авторизованным пользователям.
    3. Проверьте, что игру можно играть на деньги и в демо-режиме.
    4. Проверьте, что игроки могут ставить деньги в USD и EUR.
    5. Проверьте, что игра доступна для игры во всех странах, кроме РФ 
    (если есть ограничения по гео).
    6. Проверьте, что игра соответствует типу "слот" и имеет джекпот.
    
    Примеры позитивного и негативного сценариев:
    
    Позитивный сценарий:

    1. Пользователь авторизуется на платформе.
    2. Пользователь находит игру Microgaming Goldaur Guardians в разделе "новинки".
    3. Пользователь запускает игру в демо-режиме.
    4. Игра запускается и пользователь может играть в нее.
    5. Пользователь выигрывает в игре и получает выигрыш в выбранной им валюте.

    Негативный сценарий:

    1. Пользователь авторизуется на платформе.
    2. Пользователь находит игру Microgaming Goldaur Guardians в разделе "новинки".
    3. Пользователь запускает игру на деньги.
    4. Игра не запускается, и пользователю выводится сообщение об ошибке.
    5. Пользователь связывается с поддержкой и сообщает о проблеме.
    6. Технический специалист из команды разработки проводит дополнительные
    тесты и находит ошибку.
    7. Ошибка устраняется, и игра становится доступна для игры на деньги.

# Задание No3: Поиск багов
    
### Протестировать сайт https://goxbet2.com/ 
### Оформить один баг в полном виде с заполнением всех необходимых полей. Остальные найденные баги перечислить в виде списка.

# ОТВЕТЫ:

### 1. Проверьте, что новая игра добавлена на платформу в разделе "новинки".

        Позитивный сценарий:

    Зайти на платформу https://goxbet2.com/.
    1. Пользователь авторизуется на платформе.
    2. Пользователь находит игру Microgaming Goldaur Guardians в разделе "новинки".
    3. Пользователь запускает игру в демо-режиме.
    4. Игра запускается и пользователь может играть в нее.
    5. Пользователь выигрывает в игре и получает выигрыш в выбранной им валюте.
