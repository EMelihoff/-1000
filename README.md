# -1000

ВЫБРАТЬ
	0 КАК Цифра
ПОМЕСТИТЬ ВТ_Цифры

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	1

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	2

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	3

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	4

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	5

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	6

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	7

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	8

ОБЪЕДИНИТЬ ВСЕ

ВЫБРАТЬ
	9
;

////////////////////////////////////////////////////////////////////////////////
ВЫБРАТЬ
	
	ВТ_Цифры0.Цифра + 10 * ВТ_Цифры1.Цифра + 100 * ВТ_Цифры2.Цифра КАК РядЧиселОтНуляДоТысячи
ИЗ
	ВТ_Цифры КАК ВТ_Цифры0
		ВНУТРЕННЕЕ СОЕДИНЕНИЕ ВТ_Цифры КАК ВТ_Цифры1
		ПО (ИСТИНА)
		ВНУТРЕННЕЕ СОЕДИНЕНИЕ ВТ_Цифры КАК ВТ_Цифры2
		ПО (ИСТИНА)

УПОРЯДОЧИТЬ ПО
	РядЧиселОтНуляДоТысячи
