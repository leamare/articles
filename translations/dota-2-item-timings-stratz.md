Source: https://medium.com/@STRATZ/dota-2-item-timings-22d2dbd76bc4

# Тайминги предметов в Dota 2
### Определяя наиболее важные тайминги предметов

Во время поездки на Captains Draft 4.0 в Вашингтон, мы побеседовали с [Nahaz](https://twitter.com/NahazDota) из [datdota](http://www.datdota.com/) по поводу недостатка полезной информации о влиянии таймингов предметов на винрейт. Хоть большинство игроков в Dota 2 уверены, что есть предметы, которые более эффективны при покупке в определённое время, никто ещё не пытался рассматривать тайминги предметов достаточно осмысленно, чтобы можно было делать прямые сравнения и сравнивать тайминги между собой.

Так как у нас на STRATZ есть детальная информация о времени покупки предметов на всех героях, мы можем себе позволить закопаться в эти данные и поделиться своими находками.

> Когда мы задаёмся вопросом "Насколько сильно меняется винрейт для каждой минуты упущенного тайминга", мы постулируем, что чем быстрее винрейт снижается, тем важнее этот предмет должен быть для достижения победы.

В математике угловой коэффициент, или градиент, линии -- число, которое описывает сразу и направление, и наклон линии. Таким образом, чем больше градиент винрейта для комбинации герой-предмет, предмет он важнее.

По сути мы приравниваем важность тайминга предмета к частоте изменения винрейта и выражаем частоту изменения как математический градиент.

Давайте для примера рассмотрим изменение винрейта во времени для Phantom Assassin с Black King Bar.

![pa bkb](https://cdn-images-1.medium.com/max/800/1*1D63ayaQNoAI6xRT27Jufg.png")

> Phantom Assassin с BKB

> Phantom Assassin BKB. Blue points show win percentages of item purchases in that minute [error bars indicate 95% confidence interval, calculated by assuming win-loss can be represented by Bernoulli trials]. Orange line represents the distribution of when item was purchased. The dashed lines indicate the times between which approximately 69% of the results lie. Solid lines indicate the mean purchase time of the item on the hero (vertical), as well as hero average winrate (horizontal).
