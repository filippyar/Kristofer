# Во вкладке "Счета" собраны данные за 8 лет продаж.

Первый год (по февраль 2016 включительно) в качестве KPI использовался показатель валовых продаж.
План был обозначен на уровне 500 000 в месяц.
Бонус считался по формуле 5% от продаж, если план выполнен, и 2% - если нет. Дополнительно к бонусу прибавлялось 2% от продаж новым клиентам.
Новым клиентом считался клиент, с которым мы сотрудничаем первый месяц. Начиная со следующего календарного месяца клиент теряет этот статус.

С марта 2016 ввели новое KPI - маржа, то есть разница между стоимостью продажи и стоимостью закупки без учета других расходов.
Было установлено 2 уровня выполнения плана - 150 000 и 250 000.
Бонус расчитывается как 5% от маржи независимо от суммы маржи. При марже более 150 000 дополнительно 7% от маржи (то есть 12% всего).
При марже свыше 250 000 плюс еще 5%, то есть 17% всего. Дополнительно к бонусу прибавляется 6% от маржи по продажам новым клиентам.
Статус нового клиента определяется как раньше.

# Далее я разделил эти данные на 2 листа: до марта 16 и после марта 16. 
Данные по каждому месяцу я выделил в отдельную умную таблицу и назал их по типу "месяц год".
В каждом месяце отдельно прописывалась фактическая сумма бонуса. Как правило, она была больше рассчетной, поэтому я не был заинтересован выяснять причины этих расхожений.

Итоговые данные по каждому месяцу я собрал в листе "Помесячно", где в столбцах с окончанием "Олд" я просчитал, 
какие выплаты я бы получил, если бы систему премирования в марте 16 года не изменили. В столбце "Разница" я вычислил разность между новым и старым бонусом.
В итоге получилось, что, если бы систему мотиваций не сменили, то я за 7 лет получил бы почти на 580 000 больше.
В столбцах, где есть слово "Итого", был добавлен оклад, который за минусом налога всегда был равен 14 790.

# Следующим этапом я собрал все продажи в 1 таблицу на листе "Общая". 
В столбце "ИД" я объединил номер счета и год, чтобы каждая продажа имела уникальный идентификатор. В столбце "НК" были проставлены 1, если клиент имел статус нового.

На вкладке "Графики" с помощью сводных таблиц я построил столбчатые диаграммы.
Изначально мы распределяли маржу по месяцам, отталкиваясь от месяца оплаты счетов.
Однако, часто постоянные клиенты платили с большой отсрочкой. Либо наоборот, доставка товара занимала много времени и отгрузка товара была гораздо позже оплаты.
Две диаграммы позволили сравнить, как бы изменилась картина, если бы мы вели учет по дате отгрузки.
Вторая диаграмма получилась более ровная, тренд на увеличение был менее выражен.
На третьей диаграмме я отобразил динамику изменения средней зарплаты.
