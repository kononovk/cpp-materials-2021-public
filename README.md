
## Описание курса

Первая часть курса дает базовые знания и навыки для написания программ с помощью *С++*. Для освоения курса необходимо быть уверенным пользователем вашей любимой ОС и иметь базовое представление о системе контроля версий `git`.

*C++* знаменит своей производительностью, которая дается, в том числе, и ценой уменьшения безопасности: например, нет проверки выхода индекса за границы массива. Тем не менее, *C++* активно развивается в последнее время, и это явно указывает о заинтересованности IT-сообщества в нем. *C++20* стандарт готов, а ведущие компиляторы поддерживают почти все требования, описанные в нем. Стандарт *C++20* будет рассмотрен во второй части курса, а в первой мы сконцентрируемся на стандартах *C++11,C++13,C++17*, так как именно они активно используется для разработки в настоящее время.

Примерный список тем, которые будут рассмотрены в первой части курса:

 - препроцессор, компиляция, линковка и исполнение программ
 - встроенные типы, основные конструкции языка
 - глобальные и локальные переменные, области видимости
 - массивы, указатели, ссылки
 - функции, способы передачи аргументов в функцию, указатель на функцию, перегрузка, inline, static, конвенции вызова, RVO и NRVO
 - объявление и определение, ODR, внутренняя и внешняя линковка
 - работа с памятью
 - перечисления, объединения
 - классы: поля, методы, области видимости, операторы, наследование, динамический полиморфизм
 - пространства имен
 - анонимные функции
 - шаблонные фукнции и классы
 - move-семантика, категории значений выражений

## Активности и оценки

#### Лекции

На лекциях рассматривается теоретическая часть языка программирования С++. Для лучшего понимания темы мы стараемся показать больше примеров, как в виде код-сниппетов, так и в формате лайв-кодинга.

По окончании лекции могут быть небольшие анонимные опросы по прошедшей теме с возможностью оставить комментарии и предложения о курсе.

#### Семинары

Семинары обязательны для студентов ИТМО и опциональны для студентов CSC.

Студентам CSC дается время на подтверждения участия в семинаре. Если студент CSC подтверждает свое участие в семинаре, то оценки за дорешки и контрольные работы будут учитываться в итоговой оценке за курс, в ином случае они учитываться не будут. *Отказ от семинаров после дедлайна подтверждения участия наказывается штрафом в `1` балл из итоговой оценки за курс.*

##### Дорешки

Семинары рассчитаны на более глубокий разбор тех или иных практических вопросов языка. Обычно семинар состоит из разбора задач прошлого семинара, небольшого обзора тем для новых задач и решение задач с возможностью задать вопросы семинаристу.
На семинарах выдается неcколько небольших задач. Решения проходят два этапа ревью, которые помогут вам с написанием идиоматичного кода и поиском распространенных ошибок.

Подробнее о том, как происходит процесс оценивания дорешек описано [здесь](https://github.com/cpp-practice/cpp-materials-2021-public/blob/master/seminars/README.md).

Итоговая оценка за дорешки рассчитывается следующим образом:

 - Рассчитывается относительный балл `R`: `[Балл за дорешку] / [Максимальный балл за дорешку]`
 - Отбрасывается худшая дорешка
 - Рассчитывается средний относительный балл `avgR`
 - Итоговая оценка: `2 + 3 * avgR`

_Примечание: бонусные коэффициенты и задачи со звездочками не учитываются в максимальном балле за дорешку_

##### Контрольные работы

Примерно каждый 4-5 семинар проводится контрольная работа. За семестр будет проведено 3-4 контрольные работы.
Решения контрольных работ проходят ревью единожды.

Итоговая оценка за контрольные работы рассчитывается следующим образом:

 - Рассчитывается относительный балл `R`: `[Балл за кр] / [Максимальный балл за кр]`
 - Отбрасывается худшая контрольная
 - Рассчитывается средний относительный балл `avgR`
 - Итоговая оценка: `2 + 3 * avgR`

#### Большие домашние задания

*Домашние задания обязательны для всех студентов курса.*

Большое домашнее задание предпологает решение одной большой целостной задачи с последующими тремя попытками ревью. Всего будет три домашних задания.

О том как формируются сроки сдачи домашних работ описано [здесь](https://docs.google.com/document/d/1E3B16FdLuQKTK2VDs6usk5uZHyaA3f6bjYn7S5Xu2QI/edit#heading=h.obdvy97vybx2)

За домашнее задание можно получить либо зачет, либо незачет.

Итоговая оценка за домашние задания: `количество зачетов + 2`


## Допуск к экзамену

*Экзамен опционален для студентов CSC и на оценку за курс не влияет*

Студент считается допущенным к экзамену, если он имеет `>= 2.5` балла за каждую из активностей.

Если имеется `< 2.5` баллов только за одну из активностей, то ее можно досдать на экзамене.

## Экзамен

Экзамен состоит из 3 блоков: теормин, теория, задача. Каждый из них оценивается по 5-бальной шкале.

Если оценка за каждый из блоков `>= 2.5`, то оценка за экзамен рассчитывается как среднее оценок этих 3 блоков, иначе `2`.

## Оценка за курс

#### CSC (без семинаров)

Итоговая оценка -- это оценка за большие домашние работы.

#### CSC (с семинарами)

Если оценка хотя бы за одну из активностей `< 2.5`, то оценка `2`.

Итоговая оценка: `AVG(дорешки, контрольные, домашние)`.

#### ITMO

Если оценка за экзамен `< 2.5`, то оценка `2`.

Иначе, `AVG(AVG(дорешки, контрольные, домашние), экзамен)`.

## Полезные ссылки

- [Общая ведомость](https://docs.google.com/spreadsheets/d/1sio-hlxpEqgwgmUJDnQ8UL76fai3K2npazfroXBB8iM/edit#gid=238053417) (В случае отсутствия доступа, запросите его, указав Фамилию, Имя и ник на github.com)

