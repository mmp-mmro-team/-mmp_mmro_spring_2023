# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, весенний семестр 2022/2023
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2022/2023"

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/kernel_trick.jpg" height=200pt>
</p>

:white_check_mark: **Курс сдается через систему [anytask](https://anytask.org/course/907). Инвайт можете получить у преподавателя**

:white_check_mark: На семинары и работу ассистентов можно [оставить отзыв](https://docs.google.com/forms/d/e/1FAIpQLSeCww7kQZRBbPDFW_dTRpKdBl1pL0jx4nezhciAof8b22O05Q/viewform)

:white_check_mark: **Полезные ссылки:**

* Текущие связанные курсы
    * [Курс Практикума, весна](https://github.com/mmp-practicum-team/mmp_practicum_spring_2023) 
    * [Общий курс ML](https://github.com/MSU-ML-COURSE/ML-COURSE-22-23)

* Осенний семестр
    * [Курс ММРО 22/23, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2022)
    * [Курс Практикума на ЭВМ, осень](https://github.com/mmp-practicum-team/mmp_practicum_fall_2022)

* Материалы прошлых лет:
  * [Материалы древних времен](https://github.com/esokolov/ml-course-msu)
  * [Вышкинский аналог курса](https://github.com/esokolov/ml-course-hse)
  * [Курс лекций по ММРО 20/21 (в те времена он читался эксклюзивно для ММП)](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Общий курс по МЛ 21/22](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)
  * [Курс ММРО 19/20, весна](https://github.com/mmp-mmro-team/mmp_mmro_spring_2020)
  * [Курс ММРО 20/21, весна](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021)
  * [Курс ММРО 21/22, весна](https://github.com/mmp-mmro-team/mmp_mmro_spring_2022)

# Правила выставления оценок

:white_check_mark: **По этому курсу (ММРО) в конце семестра будет экзамен**

Общая оценка по нему выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/formula.png)
, где 

* Check — 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs — min(5, 5 * <сумма баллов за лабораторные + теор. дз.> / <суммарный макс балл за (лабораторные + теор.дз) (без бонусов)>
* Exam — оценка за экзамен, до 5 баллов

:white_check_mark: **Обратите внимание, что проверочные проходят в рамках общекурсовых лекций по ML (называются тесты)**

Причем
* Для общей оценки 5 необходимо сдать **все (4)** _лабораторные работы_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 3-х** работ из _всего множества лабораторных работ_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor — округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

## Оценивание контеста (В ЭТОМ ГОДУ КОНТЕСТ ОБЪЯВЛЕН БОНУСНЫМ)

* Преодоление бейзлайна (Benchmark (MMRO)) на привате --- 5 баллов (основной балл). Бенчмарк скоро появится
* Распределение 10 **бонусных** баллов на рейтингу по приватной части -- аналогично оцениванию, описанному на странице с контестом (только вместо 30 -- 10 баллов, остается разделение на 10 групп)
* Последний семинар в этом семестре будет посящен контесту. От студентов, попаших в первую (топовую) группу, мы ожидаем короткое (10 минут) выступление с презентацией по вашему решению. Без него вы сможете получить только максимум 9 бонусных баллов (вместо 10). Выступления от остальных -- по желанию (за дополнительные бонусные 0.5 балла) (при наличии большого числа желающих возможна предварительная запись на выступление). Нам будет интересно вам послушать! :)
* Итого, у контеста -- 5 основных баллов, до 10 бонусных

## Связь с общекурсовыми лекциями по ML

:white_check_mark: **По курсу лекций в конце семестра будет экзамен с оценкой**

_Если ММРО у вас обязательный курс, то:_

:white_check_mark: **Ваша оценка по общекурсовым лекциям по ML = итоговой оценке по курсу ММРО**

_В иных случах эти два курса сдаются каждый по своей системе оценивания_

# Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 9 февраля  | Семинар 1 | <ul><li>Аппроксимация ядер</li><li>Ядра для строк</li></ul> | <ul><li>[Семинар по аппроксимации](https://github.com/esokolov/ml-course-22/blob/main/files/Spotify%20tracks%20popularity%20prediction.pdf)| [домашка на ядра](https://github.com/mmp-mmro-team/-mmp_mmro_spring_2023/blob/main/homework_practice/homework-practice-01-random-features.ipynb) | 
| 16 февраля | Семинар 2 | Задачи на байесовский подход | <ul><li>[Презентация](https://github.com/mmp-mmro-team/mmp_mmro_spring_2022/blob/main/seminars/PresentationPPD.pdf)</li><li>[Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2022/blob/main/seminars/Sem13_bayes.pdf)</li></ul> | ¯\\\_(ツ)\_/¯ |
| 2 марта | Семинар 3 | <ul><li>Вывод линейного дискриминанта Фишера</li><li>Ядровой дискриминант Фишера</li></ul> | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2022/blob/main/seminars/sem15-fld.pdf) | ¯\\\_(ツ)\_/¯ |
| 9 марта | Семинар 4 |  EM-алгоритм: сходимость, скорость сходимости, связь с градиентным подъёмом | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/lecture-notes/lecture15-em.pdf) | [Крещение огнем](https://github.com/mmp-mmro-team/-mmp_mmro_spring_2023/blob/main/homework_practice/em/homework-practice-09-em.ipynb) |
| 16 марта | Семинар 5 | EM-алгоритм | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem15-em.pdf) | ¯\\\_(ツ)\_/¯  | 
| 23 марта | Семинар 6 | Multilabel-задачи | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem21-multilabel.pdf) |¯\\\_(ツ)\_/¯ |
| 30 марта | Семинар 7 | <ul><li>Спектральная кластеризация</li><li>Внешняя оценка качества кластеризации</li></ul>  | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/lecture17-clusterization.pdf)  |  ¯\\\_(ツ)\_/¯  |
| 6 апреля | Семинар 8 | Тематическое моделирование  |  [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2022/blob/main/seminars/topic_modeling_.ipynb) | [изи дз](https://github.com/mmp-mmro-team/-mmp_mmro_spring_2023/blob/main/homework_practice/homework-practice-10-unsupervised.ipynb) |
| 13 апреля | Семинар 9 | Обучение метрик  | [Семинар](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021/blob/main/seminars/sem20-knn.pdf) |  |
| 20 апреля | Семинар 10 | Top secret  | --- |  |
| 27 апреля | Семинар 11 | Рекомендательные системы  | см. [запись семинара](https://youtu.be/1CiEGJSw0zA) |  |
| 4 мая | Семинар 12 | Семинара не будет  |  |  |
| 11 мая | Семинар 13 | нелинейное снижение размерности  | [Материал 1](https://github.com/esokolov/ml-course-hse/blob/master/2022-spring/seminars/sem14-pca.pdf) [Материал 2](https://docs.yandex.ru/docs/view?url=ya-disk-public%3A%2F%2FpL9BbVRS9%2FKiBW%2F5gASIejjgvrLtzV6cG58fTBaAVPc%3D&name=300-Nonlinear%20dimensionality%20reduction.pdf&nosw=1 ) |  |
| 18 мая | Семинар 14 | Разбор контеста  |  |  |
