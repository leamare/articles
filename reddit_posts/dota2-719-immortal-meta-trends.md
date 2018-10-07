Published: https://www.reddit.com/r/DotA2/comments/9cskst/immortal_rank_meta_trends_719_edition/

---

Spectral stats guy here. This post is based on data collected during patch 7.19. It includes most of ranked matches that were played on Immortal rank in patch 7.19 (except ones that had abandons, ended in less than 10 minutes or had insignificantly low score).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_719). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region spacific data.

[Ranked meta trends hub](https://spectralalliance.ru/reports/?cat=ranked)

> Fun fact: It was available ever since the patch started and it was possible to get predictions right for the TI8 compendium. Shame I haven't thought about it myself.

---

# Short FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using mostly OpenDota API.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** It's ranked version of `(wins_picked+wins_banned)/matches_total`. It will be replaced later on, but right now it's here mostly to see most effective heroes in the meta.

# Summary

* **Matches total:** 55045
* **Missing replays:** 40
* **Individual players spotted in matches:** 19320
* **Radiant winrate:** 53.60%
* **Average match duration:** 36:20
* **Total Buybacks:** 309539 (5.62 per match on average)
* **Total Creeps Killed:** 89997755

### Game Modes

* **All Draft:** 85.54% (47087)
* **Random Draft:** 14.46% (7958)

### Regions

* **Europe West:** 21900
* **Southeast Asia:** 15097
* **China:** 7963
* **US East:** 7416
* **Europe East:** 1171
* **Australia:** 554
* **South America:** 510
* **Russia:** 372
* **US West:** 59
* **Japan:** 3 -- *PigChamp*

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
|GPM | 4069263560 | 1,403 | ☼DyrA1L.(Fy)- | Alchemist
|XPM | 4087951222 | 1,408 | mode : BERSERKER | Meepo
|Kills | 4054431353 | 51 | Toga Himiko | Phantom Assassin
|Deaths | 4040752793 | 53 | SlowMotion | Silencer
|Assists | 4053604607 | 68 | Ma - Nic | Phoenix
|KDA with 0 deaths | 4088762349 | 49.00 | 疯了 | Weaver
|KDA with 1+ deaths | 4033392209 | 64.00 | VP.artstyle | Zeus
|Networth | 4053604607 | 122,160 | elevated | Treant Protector
|Last hits | 4053604607 | 2,020 | elevated | Treant Protector
|Damage to heroes | 4053604607 | 250,943 | Awakening | Spectre
|Damage to buildings | 4089483540 | 25,819 | 莫得感情的沙手 | Clinkz
|Hero healing | 4076874787 | 110,289 | need teammates not primates | Treant Protector
|Damage taken from heroes | 4062980697 | 184,178 | Gorox | Wraith King
|Efficiency on lane | 4056989918 | 234% | dog | Broodmother
|Observer wards placed | 4053604607 | 53 | AGGRESSOR | Omniknight
|Sentries placed | 4048960621 | 125 | <Torgai Atajan> | Ogre Magi
|Teamfight participation | 4054634902 | 267% WutFace | responsible citizen | Terrorblade
|Obs Wards destroyed | 4053604607 | 21 | AGGRESSOR | Omniknight
|Map pings | 4081823359 | 13,293 | PUMz | Spirit Breaker
|Stuns | 4053604607 | 975.98 | elevated | Treant Protector
|Couriers killed by a player | 4036587634 | 7 | ZeDisBuGG | Bounty Hunter

Notes:
1. It seems like NP wasn't feeding intentionally. Altho, EUW deaths record was set by intentional feeding by a NP player as well.

# Heroes

**[Hero Graph](https://spectralalliance.ru/reports/?league=imm_ranked_718&mod=heroes-meta_graph)**

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Crystal Maiden | 24076 | 43.74% | 100.00 | 19625 | 52.93% | 4451 | 52.51%
| Ursa | 22732 | 41.30% | 99.14 | 18304 | 54.36% | 4428 | 54.02%
| Weaver | 23206 | 42.16% | 98.28 | 18419 | 51.02% | 4787 | 50.60%
| Necrophos | 20901 | 37.97% | 97.41 | 17080 | 52.94% | 3821 | 51.48%
| Dark Willow | 20378 | 37.02% | 96.55 | 16595 | 51.04% | 3783 | 50.65%
| Wraith King | 18972 | 34.47% | 95.69 | 15568 | 54.78% | 3404 | 53.29%
| Spectre | 17442 | 31.69% | 94.83 | 13807 | 56.12% | 3635 | 55.54%
| Treant Protector | 16922 | 30.74% | 93.97 | 13412 | 55.34% | 3510 | 54.81%
| Silencer | 16048 | 29.15% | 93.10 | 12942 | 54.50% | 3106 | 54.19%
| Pudge | 18079 | 32.84% | 92.24 | 14844 | 47.74% | 3235 | 46.89%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Picks | Winrate | - | Hero | Picks | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Crystal Maiden | 8617 | 51.78%| - | Weaver | 13216 | 51.20%
| Pudge | 7785 | 47.05%| - | Ursa | 13062 | 54.48%
| Dark Willow | 7169 | 50.17%| - | Necrophos | 11081 | 52.70%
| Treant Protector | 6960 | 55.62%| - | Spectre | 10716 | 56.75%
| Grimstroke | 5526 | 52.28%| - | Storm Spirit | 9113 | 49.72%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Warlock + Spectre | 1597 | 53.04% | 658.306 | 938.694 | 58.78% | 93.61%
| Vengeful Spirit + Weaver | 1928 | 55.91% | 1,422.959 | 505.041 | 26.20% | 45.18%
| Drow Ranger + Vengeful Spirit | 846 | 56.74% | 355.064 | 490.936 | 58.03% | 49.29%
| Wraith King + Grimstroke | 1387 | 59.12% | 936.003 | 450.997 | 32.52% | 69.00%
| Wraith King + Dark Willow | 2742 | 56.35% | 2,346.725 | 395.275 | 14.42% | 62.07%
| Zeus + Spectre | 1583 | 56.66% | 1,194.834 | 388.166 | 24.52% | 5.31%

## Lane Combos

| Heroes | Matches | Winrate | Most Common Lane
|:-:|:-:|:-:|:-:|
| Crystal Maiden + Ursa | 1821 | 58.70% | Safelane
| Wraith King + Dark Willow | 1702 | 58.17% | Offlane
| Warlock + Spectre | 1495 | 53.44% | Safelane
| Spectre + Silencer | 1462 | 63.75% | Safelane
| Crystal Maiden + Spectre | 1440 | 57.64% | Safelane
| Crystal Maiden + Weaver | 1339 | 53.55% | Safelane


# Hero positions

## Most popular

### Core Safelane

* **Spectre:** 12667 (**56.82%** wr)
* **Weaver:** 10199 (50.73% wr)
* **Ursa:** 9675 (54.91% wr)
* **Phantom Lancer:** 8342 (50.96% wr)
* **Necrophos:** 4949 (51.30% wr)

Just look at this gap between Top 4 carries and... the others.

### Core Midlane

* **Storm Spirit:** 9677 (49.80% wr)
* **Invoker:** 7635 (51.30% wr)
* **Lina:** 6972 (**44.54%** wr)
* **Tinker:** 6180 (50.73% wr)
* **Broodmother:** 5901 (53.36% wr)

### Core Offlane

* **Wraith King:** 10573 (**56.24%** wr)
* **Necrophos:** 8130 (54.50% wr)
* **Weaver:** 7507 (52.02% wr)
* **Enchantress:** 7364 (52.57% wr)
* **Ursa:** 5840 (54.97% wr)

### Support

* **Crystal Maiden:** 19003 (53.03% wr)
* **Dark Willow:** 14750 (51.65% wr)
* **Pudge:** 13631 (47.99% wr)
* **Treant Protector:** 13184 (**55.56%** wr)
* **Silencer:** 12582 (54.80% wr)
* **Earthshaker:** 8859 (51.65% wr)
* **Shadow Shaman:** 7527 (51.38% wr)
* **Vengeful Spirit:** 7201 (53.67% wr)
* **Phoenix:** 6329 (52.17% wr)
* **Lion:** 5888 (46.81% wr)

### Core Jungle

* **Bloodseeker:** 98 (44.90% wr) -- 1.33% of matches
* **Wraith King:** 72 (43.06% wr) -- 0.46% of matches
* **Alchemist:** 59 (42.37% wr) -- 1.24% of matches
* **Ursa:** 55 (41.82% wr) -- 0.3% of matches
* **Enigma:** 53 (**37.74%** wr) -- 2.20% of matches

# Regions Meta

Not popular regions were sorted out. Pickban stats were gotten only for the most popular regions.

## Europe West

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Weaver | 11340 | 51.78% | 100.00 | 8708 | 50.96% | 2632 | 50.19%
| Ursa | 10039 | 45.84% | 99.14 | 7815 | 53.37% | 2224 | 53.91%
| Crystal Maiden | 8691 | 39.68% | 98.28 | 6799 | 53.52% | 1892 | 53.12%
| Dark Willow | 8971 | 40.96% | 97.41 | 6925 | 50.71% | 2046 | 50.10%
| Spectre | 7848 | 35.84% | 96.55 | 5954 | 56.40% | 1894 | 56.12%
| Silencer | 7978 | 36.43% | 95.69 | 6202 | 54.55% | 1776 | 53.94%
| Necrophos | 8098 | 36.98% | 94.83 | 6319 | 52.76% | 1779 | 51.04%
| Treant Protector | 6735 | 30.75% | 93.97 | 5197 | 55.07% | 1538 | 55.59%
| Wraith King | 6687 | 30.53% | 93.10 | 5154 | 54.06% | 1533 | 53.29%
| Pudge | 7102 | 32.43% | 92.24 | 5587 | 47.99% | 1515 | 46.86%

## US East

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Crystal Maiden | 3440 | 46.39% | 100.00 | 2783 | 51.85% | 657 | 52.97%
| Ursa | 3088 | 41.64% | 99.14 | 2485 | 54.89% | 603 | 52.57%
| Weaver | 2878 | 38.81% | 98.28 | 2321 | 52.87% | 557 | 56.01%
| Necrophos | 2801 | 37.77% | 97.41 | 2216 | 52.21% | 585 | 52.48%
| Dark Willow | 2668 | 35.98% | 96.55 | 2183 | 52.18% | 485 | 55.67%
| Pudge | 2800 | 37.76% | 95.69 | 2254 | 48.45% | 546 | 47.99%
| Silencer | 2456 | 33.12% | 94.83 | 1959 | 53.09% | 497 | 55.33%
| Treant Protector | 2314 | 31.20% | 93.97 | 1788 | 55.65% | 526 | 55.70%
| Wraith King | 2199 | 29.65% | 93.10 | 1765 | 56.43% | 434 | 51.15%
| Spectre | 1991 | 26.85% | 92.24 | 1581 | 57.31% | 410 | 56.34%

## Southeast Asia

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Crystal Maiden | 8773 | 58.11% | 100.00 | 7111 | 53.06% | 1662 | 52.59%
| Ursa | 6712 | 44.46% | 99.14 | 5358 | 55.69% | 1354 | 55.24%
| Wraith King | 6536 | 43.29% | 98.28 | 5266 | 55.77% | 1270 | 53.39%
| Treant Protector | 6361 | 42.13% | 97.41 | 5068 | 55.70% | 1293 | 53.83%
| Necrophos | 6422 | 42.54% | 96.55 | 5170 | 53.00% | 1252 | 51.92%
| Weaver | 6299 | 41.72% | 95.69 | 4969 | 49.27% | 1330 | 48.87%
| Spectre | 5090 | 33.72% | 94.83 | 3963 | 55.29% | 1127 | 54.21%
| Dark Willow | 5482 | 36.31% | 93.97 | 4422 | 49.80% | 1060 | 49.43%
| Earthshaker | 5198 | 34.43% | 93.10 | 4275 | 49.78% | 923 | 49.30%
| Pudge | 5005 | 33.15% | 92.24 | 4049 | 47.52% | 956 | 45.61%

## China

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Wraith King | 2764 | 34.71% | 100.00 | 2763 | 53.28% | 1 | 0.00%
| Necrophos | 2698 | 33.88% | 99.14 | 2696 | 53.52% | 2 | 0.00%
| Dark Willow | 2263 | 28.42% | 98.28 | 2263 | 52.41% | 0 | 0.00%
| Crystal Maiden | 1927 | 24.20% | 97.41 | 1927 | 52.41% | 0 | 0.00%
| Pudge | 2143 | 26.91% | 96.55 | 2143 | 46.90% | 0 | 0.00%
| Zeus | 1911 | 24.00% | 95.69 | 1911 | 51.91% | 0 | 0.00%
| Ursa | 1775 | 22.29% | 94.83 | 1773 | 54.77% | 2 | 50.00%
| Spectre | 1662 | 20.87% | 93.97 | 1660 | 56.08% | 2 | 0.00%
| Broodmother | 1698 | 21.32% | 93.10 | 1697 | 52.21% | 1 | 100.00%
| Enchantress | 1595 | 20.03% | 92.24 | 1595 | 54.17% | 0 | 0.00%

# 7.19b heroes, Grimstroke and other stuff

In brackets you can see how the value changed in 7.19b patch day one results. It doesn't say much about how 7.19b changes affected heroes (amount of matches played is kinda too low), but it may paint a close picture.

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Alchemist | 5831 | 10.59% (+5.34%) | 65.52 | 4757 | 52.51% (+3.08%) | 1074 | 52.14% (+1.91%)
| Bloodseeker | 9010 | 16.37% (-2.00%) | 80.17 | 7378 | 52.20% (-3.66%) | 1632 | 50.43% (+2.03%)
| Broodmother | 8240 | 14.97% (-2.36%) | 77.59 | 6666 | 52.99% (+5.13%) | 1574 | 53.18% (+5.15%)
| Chen | 981 | 1.78% (+0.54%) | 10.34 | 827 | 45.10% (+0.14%) | 154 | 39.61% (+2.06%)
| Clinkz | 11533 | 20.95% (+6.94%) | 87.93 | 9099 | 52.68% (-2.48%) | 2434 | 52.59% (-6.94%)
| Crystal Maiden | 24076 | 43.74% (-19.93%) | 100.00 | 19625 | 52.93% (-0.62%) | 4451 | 52.51% (-1.12%)
| Dark Willow | 20378 | 37.02% (+3.52%) | 96.55 | 16595 | 51.04% | 3783 | 50.65%
| Drow Ranger | 5752 | 10.45% (+2.03%) | 64.66 | 4596 | 51.44% (-5.80%) | 1156 | 53.11% (-13.77%)
| Enchantress | 11290 | 20.51% (-1.12%) | 84.48 | 9096 | 51.34% (-2.67%) | 2194 | 51.73% (+4.85%)
| Gyrocopter | 1418 | 2.58% (+1.07%) | 14.66 | 1197 | 41.60% (-5.31%) | 221 | 41.18% (-14.49%)
| Grimstroke | 8549 | 15.53% (+45.00%) | 78.45 | 6619 | 52.44% (-0.71%) | 1930 | 53.11% (-0.34%)
| Huskar | 4895 | 8.89% (+0.61%) | 61.21 | 4013 | 52.83% (-1.72%) | 882 | 51.93% (-0.71)
| Io | 2445 | 4.44% (+1.35%) | 37.07 | 1970 | 51.17% (+5.71%) | 475 | 51.16% (+18.07%)
| Mirana | 12860 | 23.36% (-6.62%) | 90.52 | 10476 | 48.75% (-3.40%) | 2384 | 48.45% (+5.79%)
| Nature's Prophet | 3512 | 6.38% (+0.70%) | 48.28 | 2854 | 44.22% (-0.25%) | 658 | 46.20% (-4.53%)
| Necrophos | 20901 | 37.97% (-10.81%) | 97.41 | 17080 | 52.94% (-4.78%) | 3821 | 51.48% (+4.66)
| Phantom Lancer | 11860 | 21.55% (+6.03%) | 86.21 | 9478 | 50.57% (-2.36%) | 2382 | 51.22% (-8.77%)
| Silencer | 16048 | 29.15% (+11.78%) | 93.10 | 12942 | 54.50% (-1.06%) | 3106 | 54.19% (-4.19%)
| Spectre | 17442 | 31.69% (+12.11%) | 94.83 | 13807 | 56.12% (-2.94%) | 3635 | 55.54% (-1.82%)
| Tiny | 12941 | 23.51% (+2.13%) | 85.34 | 10687 | 45.58% (+0.11%) | 2254 | 42.15% (+7.85%)
| Ursa | 22732 | 41.30% (-2.35%) | 99.14 | 18304 | 54.36% (-0.80%) | 4428 | 54.02% (-2.49%)
| Vengeful Spirit | 10471 | 19.02% (+1.83%) | 82.76 | 8505 | 53.37% (-3.24%) | 1966 | 55.24% (-0.29%)
| Weaver | 23206 | 42.16% (+9.90%) | 98.28 | 18419 | 51.02% (+0.28%) | 4787 | 50.60% (-3.43%)
| Wraith King | 18972 | 34.47% (+18.77%) | 95.69 | 15568 | 54.78% (+3.48%) | 3404 | 53.29% (+6.16%)

* Total Buybacks: 13347 in 2331 matches (5.72 per game on average)

# Notable Matches

* Most Roshan kills in match [4097162534](https://dotabuff.com/matches/4097162534) (6)
* Biggest Networth stomp by a team in a match [4096015580](https://dotabuff.com/matches/4096015580) (55,854)
* Biggest Networth comeback by a team in a match [4096518482](https://dotabuff.com/matches/4096518482) (38,653)
* The Longest match was [4097162534](https://dotabuff.com/matches/4097162534) (1:24:00)
* The Shortest match is [4095407844](https://dotabuff.com/matches/4095407844) (10:53)
* Bloodbath with most kills combined was in match [4095437530](https://dotabuff.com/matches/4095437530) (162)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_719)

[The International 2018 Stats and Trends](https://www.reddit.com/r/DotA2/comments/9amzvb/the_international_2018_stats_and_trends/)

[Immortal Rank Meta Trends - 7.18 Edition](https://www.reddit.com/r/DotA2/comments/93jz3u/immortal_rank_meta_trends_718_edition/)

[Spectral Alliance twitter](https://twitter.com/SpectralDota) - for english speakers

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.

And huge thanks to my Patreon pledger *Speedy Gonzales*. Your support helps to keep up.
