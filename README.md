# Project-6 Анализ A/B-теста и приоритизация гипотез

**Описание проекта**

Этот проект посвящен анализу A/B-теста и приоритизации гипотез для увеличения выручки интернет-магазина. Цель проекта - на основе данных о визитах, заказах и рекламных расходах выяснить причины убытков компании и помочь ей выйти в плюс.

**Данные**

**Данные для анализа хранятся в трех файлах:**

hypothesis.csv - список гипотез для увеличения выручки интернет-магазина с указанными параметрами Reach, Impact, Confidence, Effort

orders.csv - информация о заказах

visitors.csv - информация о посетителях

**Описание колонок в файле hypothesis.csv:**

Hypothesis — краткое описание гипотезы

Reach — охват пользователей по 10-балльной шкале

Impact — влияние на пользователей по 10-балльной шкале

Confidence — уверенность в гипотезе по 10-балльной шкале

Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале

**Описание колонок в файле orders.csv:**

transactionId — идентификатор заказа

visitorId — идентификатор пользователя, совершившего заказ

date — дата, когда был совершён заказ

revenue — выручка заказа

group — группа A/B-теста, в которую попал заказ

**Описание колонок в файле visitors.csv:**

date — дата

group — группа A/B-теста

visitors — количество пользователей в указанную дату в указанной группе A/B-теста

**Заключение**

На основе проведенного анализа можно сделать следующие выводы:

Есть статистически значимые различия в среднем количестве заказов на посетителя между группами A и B как по «сырым», так и по «очищенным» данным. Среднее количество заказов на посетителя в группе B выше, чем в группе A.

Нет статистически значимых различий в среднем чеке заказа между группами как по «сырым», так и по «очищенным» данным.

На основе этих выводов можно принять решение остановить тест и зафиксировать победу группы B. Изменения, внесенные в группу B, привели к увеличению среднего количества заказов на посетителя по сравнению с группой A, что может привести к увеличению выручки. Однако, следует отметить, что изменения не привели к значительному изменению среднего чека заказа.

Конечно, решение о том, как действовать дальше, зависит от целей и стратегии компании. Если целью является увеличение количества заказов, то можно рассмотреть возможность внедрения изменений из группы B. Если же целью является увеличение среднего чека заказа, то возможно стоит продолжить тест или провести дополнительные исследования.


**Как запустить проект**

Установите Jupyter Notebook или Jupyter Lab.

Откройте файл с проектом в Jupyter.

Запустите все ячейки по порядку.
