### Общая информация
- Bullet как и Rocket питается по технологии [PoE](https://ru.wikipedia.org/wiki/Power_over_Ethernet). Это значит, что 
по тому Ethernet кабелю, который втыкается в точку доступа, течет где-то от 8 до 24 В. То есть если вы перепутаете, 
какой провод, куда втыкать, в лучшем случае вы лишитесь только сетевой карты. Отсюда два простых правила:  

  - ***ПОЕ В ПУЛЮ***. 
  - **Первой всегда подключается Пуля.** Тогда, даже если вы перепутаете провод, пуля просто не включится, но ничего не 
  сгорит.  
- Провод для подключения к роботу изготавливается самостоятельно, лучше под присмотром знающего человека (в идеале - 
руководителя). Берется Ethernet кабель подходящей длины (**обязательно чтобы каждый провод был многожильным**), в 
изоляции делается надрез и извлекаются 4 провода: синий, бело-синий, коричневый, бело-коричневый. Их кончики зачищаются, 
и скручиваются попарно: синий - с синим, коричневый - с коричневым. После этого, ***ВНИМАНИЕ,*** **коричневый - это 
минус, синий - это плюс**. (Но лучше все еще уточнять у руководителя, или сверять с уже готовым проводом, который точно 
работал.)

- Разъем, который по умолчанию установлен на Bullet называется 
[N-Type](https://ru.wikipedia.org/wiki/N-%D0%BA%D0%BE%D0%BD%D0%BD%D0%B5%D0%BA%D1%82%D0%BE%D1%80),который бывает Male и 
Female. Рекомендую смотреть по факту, какой именно понадобится.

- Поскольку этот разъем очень большой, для установки на робота он перепаивается на разъем 
[SMA](https://www.chipdip.ru/product/gsa-1139-rp).