# the_ark
Дорогие разработчики, здесь сводка правил по работе над проектом.
Прошу вас дополнить её своими комментариями.
Так мы вместе сможем сделать спокойную рабочую обстановку и быстро читать код друг друга

## Кодстайл
- Между знаками сложения, умножения, деления и т.д. ставим пробелы
	(2 + 2 = 4; a = d * c и так далее).
- Переменные назваем максимально полно, чтобы после прочнения назания можно было понять, зачем она
или/и хотя бы что означает
	(speed_of_the_ark <- скорость коробля).
- Переменные, которые не предполагают изменения давайте писать КАПСОМ
	(SPEED_OF_LIGHT).
- Минимум непонятных значений. Числа, особенно если они неочевидные, выносить в const/enum. Например, "CELL_WIDTH = 12" вместо просто "12" в куче мест.	
	
## ООП
- По максимуму const, override, final и всего остального, что помогает нам в прочтении кода.

## Документация
- Небольшие комментарии в нужных по вашему мнению местах
- Комментарии на английском (!) - ради спокойной переносимости между разными машинами и ОС

## Коммиты
- Писать коммиты сделующим образом:

	Название
	
	Что произошло (логические изменения в работе того или иного объекта)
	
- Не пушить папки по типу .idea, clion-debug... и тому подобное.
- Коммиты на английском (!)
- Перед началом работы делать pull репозитория, чтобы потом не заниматься корректным слиянием 

