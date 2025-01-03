# Игра в BlackJack с возможностью удвоения ставки

Этот проект реализует игру в BlackJack с дополнительными функциями, такими как разделение парных карт и удвоение ставки. Игра позволяет игрокам интерактивно играть против дилера, управлять своим балансом и достигать различных достижений.

## Авторы
- **Мекеда Богдан Сергеевич**
- **Меркушев Алексей Алексеевич**

## Вклад в проект
Работа над этим проектом была разделена между двумя авторами следующим образом:

- **Мекеда Богдан Сергеевич**:
  - Реализовал основную логику игры, включая раздачу карт, действия игрока и дилера, а также правила игры.
  - Разработал систему достижений, которая отслеживает этапы игрока.


- **Меркушев Алексей Алексеевич**:
  - Добавил поддержку цветов для улучшения визуального опыта игры.
  - Создал систему статистики для отслеживания производительности игрока за несколько игр.
  - Улучшил элементы пользовательского интерфейса, такие как подсказки и запросы, для улучшения взаимодействия пользователя.


!!!(2проект это зимнее обновления)
Новые функции и улучшения:

Достижения:

Добавлена система достижений с несколькими разблокируемыми наградами.
Добавлены достижения:
"Новичок": Сыграть первую игру.
"Счастливчик": Выиграть с блэкджеком.
"Богач": Накопить 5000 фишек.
"Везунчик": Выиграть 3 раза подряд.
"Храбрец": Поставить максимальную ставку (all-in).
"Стратег": Выиграть, имея на руках два туза (и у игрока, и у дилера).
"Снеговик": Собрать на руке три семерки.
"Дед Мороз": Выиграть в канун Нового года (31 декабря).
При разблокировке достижения выводится уведомление в игре.
Сплит:

Добавлена возможность разделять (сплитовать) парные карты.
При сплите игрок получает две отдельные руки и делает дополнительную ставку, равную первоначальной.
Каждая рука играется отдельно.
Добавлено удвоение ставки на каждой руке после сплита (если хватает баланса)
Добавлена выплата за блекджек после сплита 3 к 2
Удвоение ставки:

Добавлена возможность удвоить ставку после получения первых двух карт (если хватает баланса).
После удвоения игрок получает только одну дополнительную карту и автоматически завершает ход.
Добавлено удвоение ставки на сплите
Специальные события:

Добавлены случайные специальные события, которые могут повлиять на игровой процесс.
Шанс возникновения специального события - 10% в начале каждой игры.
Виды специальных событий:
"Счастливый час": Все выигрыши удваиваются.
"Страховка от проигрыша": Следующий проигрыш вернёт половину ставки.
"Бонусные фишки": +100 к балансу игрока.
Новогоднее достижение:

Добавлено специальное достижение "Дед Мороз", которое можно получить, выиграв игру 31 декабря.
Визуальные улучшения:

Обновлено приветствие, добавлена пометка "(ЗИМНЯЯ ВЕРСИЯ)".
Добавлены небольшие паузы в действиях дилера для улучшения визуального восприятия.
Доработана логика для корректного отображения карт дилера до и после его хода.
Другие изменения:

Добавлена выплата за блекджек после сплита 3 к 2
Улучшена логика проверки на выигрыш с тремя семерками.
Улучшена логика определения конца игры при нехватке фишек.
Исправлены мелкие недочеты в коде.
Улучшена читаемость кода, добавлены комментарии на русском языке.
При старте игры автоматически разблокируется достижение "Новичок".
Обновлены правила игры, с учетом новых функций.

## Как запустить игру
Для запуска игры убедитесь, что у вас установлен Python, и выполните следующую команду в терминале или командной строке:

```bash
python blackjack_with_double.py
python winterjack.py


