# Календарь для выбора даты доставки

### Описание
Календарь используется в корзине интернет-магазина для ограничения выбора даты доставки покупателем, исходя из специфики службы доставки.</br>
Код написан на JS. Встраивается в HTML

### Особенности
1. Покупатель может выбрать любую дату доставки, начиная со следующего рабочего дня, в горизонте 21 календарного дня, которая не включает в себя:
- выходные дни
- праздничные дни

2. При оформлении заказа после 15-45 местного времени, покупатель не сможет выбрать дату доставки, выпадающую на следующий рабочий день, а только через 1 рабочий день.</br>
Например, если заказ делается в понедельник до 15-45, доступная дата доставки - со вторника и дальше.</br>
Если заказ делается в понедельник после 15-45, доступная дата доставки - со среды и дальше.</br>
Если заказ делается в пятницу после 15-45, то доступная дата доставки - со вторника следующей недели и дальше.</br>
