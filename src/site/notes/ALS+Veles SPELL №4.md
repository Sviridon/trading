---
{"dg-publish":true,"permalink":"/als-veles-spell-4/"}
---

*Сделка в рамках учебного курса [[ДЗ по курсу ALS+Veles\|ДЗ по курсу ALS+Veles]]. С Initial Stop Loss

![Pasted image 20250924214406.png|450](/img/user/media/Pasted%20image%2020250924214406.png)
![Pasted image 20250924214531.png|450](/img/user/media/Pasted%20image%2020250924214531.png)

Велес собрал все три ордера по сетке:

![Pasted image 20250924231840.png|400](/img/user/media/Pasted%20image%2020250924231840.png)

Первый (из семи) хэдж+Initial Stop Loss на следущий день:
![Pasted image 20250924232231.png|400](/img/user/media/Pasted%20image%2020250924232231.png)
****
> [!NOTE]
> Initial Stop Loss Break Even Hedge. Опциональный параметр для выставления первоначального стоп-ордера. Включение данного параметра активирует механизм условного трейлинга стоп-ордера. Данный стоп выставляется сразу при открытии хэджа (части хэджа), а при достижении ценой уровня “Min ROI for hedge stop” передвигается на значение “Stop Loss Break Even Hedge”. Задается в процентах движения цены.

Стоп лосс установлен:
![Pasted image 20250924232350.png|400](/img/user/media/Pasted%20image%2020250924232350.png)

Второй (из семи) хэдж+Initial Stop Loss:
![Pasted image 20250924232441.png|400](/img/user/media/Pasted%20image%2020250924232441.png)
Стоп лосс
![Pasted image 20250924232557.png|400](/img/user/media/Pasted%20image%2020250924232557.png)

Третий (из семи) хэдж+Initial Stop Loss:
![Pasted image 20250924232641.png|400](/img/user/media/Pasted%20image%2020250924232641.png)
Стоп лосс
![Pasted image 20250924232848.png|400](/img/user/media/Pasted%20image%2020250924232848.png)

Четвертый (из семи) хэдж+Initial Stop Loss:
![Pasted image 20250924232929.png|400](/img/user/media/Pasted%20image%2020250924232929.png)

Отменен уже выставленный SL третьего хэджа и Initial четвертого:
![Pasted image 20250924233034.png|400](/img/user/media/Pasted%20image%2020250924233034.png)

Отменен уже выставленный SL второго хэджа закрыты сейф-зоны:
![Pasted image 20250924233552.png|400](/img/user/media/Pasted%20image%2020250924233552.png)

Вернулся Второй (из семи) хэдж+Initial Stop Loss, ТВХ совсем сместилась незначительно:
![Pasted image 20250924234510.png|700](/img/user/media/Pasted%20image%2020250924234510.png)

Сейчас на бирже выставлены два SL от хэджей:
![Pasted image 20250924234810.png](/img/user/media/Pasted%20image%2020250924234810.png)

Бот на Велесе остановлен, поэтому после закрытия хэджа и возврата к лонговой ТВХ нужно будет закрыть сделку вручную.