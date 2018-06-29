Published: https://www.reddit.com/r/DotA2/comments/8ukp8k/immortal_rank_meta_trends_717_edition/

---

Just a small note. I finished my graduation and should have a bit more time to work on these now. I was working on making analyzer code a bit more readable and started implementation of regions specific data. I plan to polish it a bit and make a report on TI Qualifiers in a week or two.

---

This data is based on Immortal Ranked Trends report for patch 7.17. It includes most of ranked matches that were played on Immortal rank in patch 7.17 (except ones that had abandons, ended in less than 10 minutes or had insignificantly low score).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

Full report is available [here](https://spectralalliance.ru/reports/?league=imm_ranked_717). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates and Meta Graph.

---

# Short FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches.
* **What criteria are used?** Average rank for every game should be at least Divine 5. That's all.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that.
* **What is Outcome Impact (OI)?** It's special metric we came up at SA. The higher Outcome Impact value - the highest winrate and matches number hero has. Essentially it displays hero's power in current meta and is used for sorting heroes list. Outcome impact for draft stages is based only on this specific draft stage's stats. It will be improved later to become "Hero rank".
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **Why there're three times less matches than was in Divine 5 Meta Trends?** Keep in mind, it's only start of the season. And overall it's *Immortal* rank with exclusively leaderboard players against *Divine 5*.

# Summary

* **Matches total:** 17835
* **Missing replays:** 54
* **Individual players spotted in matches:** 11521
* **Radiant winrate:** 53.55%
* **Average match duration:** 36:27

### Game Modes

* **All Draft:** 78.37% (13978)
* **Random Draft:** 21.63% (3857)

### Regions

* **Europe West:** 7195
* **Southeast Asia:** 4454
* **China:** 3855
* **US East:** 1732
* **Europe East:** 275
* **Australia:** 121
* **South America:** 99
* **Russia:** 96
* **US West:** 8

# Players

You won't be able to find it in report. It's only available in my local database. There are too many players and personal information to include it in reports.

## Most matches

1. **< blank >:** 199 matches (51.26% wr) - SEA
2. **敏夫:** 194 matches (48.45% wr) - EU West
3. **t.tv/Peksi:** 171 matches (53.80% wr) - Russia/EU West
4. **single draft player:** 155 matches (46.45% wr) - EU West
5. **sn1:** 148 matches (51.35% wr) - Russia/EU West/Southeast Asia/South Korea
6. **phantom miria:** 148 matches (39.86% wr) - EU West
7. **有话好好说别叫:** 145 matches (48.97% wr) - China
8. **EndFast:** 145 matches (50.34% wr) - Southeast Asia
9. **twitch.tv/IImlerith:** 143 matches (51.75 wr) - EU West/EU East/Russia
10. **过程是痛苦的:** 142 matches (45.07% wr) - China

# Heroes

**[Hero Graph](https://spectralalliance.ru/reports/?league=imm_ranked_717&mod=heroes-hero_combo_graph)**

## Sorted by OI

| Hero | Matches | Contest Rate | OI | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Windranger | 9671 | 54.22% | 26.26% | 7962 | 48.78% | 1709 | 46.75%
| Warlock | 8523 | 47.79% | 25.53% | 6898 | 53.32% | 1625 | 53.85%
| Skywrath Mage | 8049 | 45.13% | 21.50% | 6677 | 47.60% | 1372 | 47.81%
| Axe | 5284 | 29.63% | 15.98% | 4355 | 54.03% | 929 | 53.50%
| Bloodseeker | 4966 | 27.84% | 14.79% | 4146 | 53.26% | 820 | 52.44%
| Zeus | 4493 | 25.19% | 13.26% | 3728 | 53.06% | 765 | 50.59%
| Doom | 4616 | 25.88% | 13.08% | 3936 | 50.36% | 680 | 51.62%
| Mirana | 4258 | 23.87% | 12.69% | 3616 | 53.57% | 642 | 50.93%
| Phantom Lancer | 4029 | 22.59% | 12.32% | 3300 | 54.03% | 729 | 56.93%
| Ember Spirit | 4312 | 24.18% | 11.96% | 3614 | 49.81% | 698 | 47.71%
| Spectre | 3565 | 19.99% | 11.54% | 2901 | 57.22% | 664 | 60.09%
| Night Stalker | 3894 | 21.83% | 11.31% | 3385 | 52.02% | 509 | 50.29%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Matches | Winrate | - | Hero | Matches | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Windranger | 3508 | 48.75%| - | Bloodseeker | 3179 | 53.22%
| Skywrath Mage | 3206 | 47.04%| - | Phantom Lancer | 2974 | 54.30%
| Warlock | 3078 | 52.53%| - | Ember Spirit | 2968 | 49.63%
| Io | 1516 | 53.10%| - | Monkey King | 2760 | 46.30%
| Night Stalker | 1056 | 49.72%| - | Faceless Void | 2602 | 50.88%
| Jakiro | 948 | 46.84%| - | Spectre | 2545 | 56.97%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation |
|:-:|:-:|:-:|:-:|:-:|
| Axe + Skywrath Mage | 1348 | 53.19% | 815.204 | 532.796
| Warlock + Spectre | 1072 | 59.79% | 561.006 | 510.994
| Beastmaster + Io | 424 | 50.00% | 223.930 | 200.070
| Night Stalker + Io | 417 | 56.59% | 228.039 | 188.961
| Sand King + Leshrac | 346 | 43.35% | 183.288 | 162.712
| Faceless Void + Skywrath Mage | 724 | 50.83% | 601.248 | 122.752
| Tinker + Bounty Hunter | 255 | 50.98% | 133.947 | 121.053
| Mirana + Naga Siren | 241 | 57.26% | 127.832 | 113.168
| Faceless Void + Invoker | 306 | 53.92% | 208.730 | 97.270
| Bane + Mirana | 336 | 59.82% | 243.500 | 92.500
| Bloodseeker + Zeus | 522 | 55.94% | 433.313 | 88.687
| Zeus + Faceless Void | 417 | 54.20% | 335.698 | 81.302

# Highest Hero Averages

This section contains highest average values among heroes. Minimum amount of matches was limited to include only meaningful data.

| Parameter | 1st Place | 2nd Place | 3rd Place |
| :-- | :-: | :-: | :-: |
| Kills | Clinkz (11.82) | Storm Spirit (11.82) | Ursa (11.75)
| Least Deaths | Broodmother (4.38) | Lone Druid (4.63) | Anti-Mage (4.77)
| Most Deaths | Techies (10.47) | Shadow Shaman (10.44) | Pudge (9.93)
| Assists | Spirit Breaker (22.48) | Bounty Hunter (20.08) | Tusk (18.64)
| KDA | Spectre (4.35) | Weaver (4.13) | Mirana (3.83)
| GPM | Meepo (685) | Alchemist (683) | Anti-Mage (650)
| XPM | Meepo (907) | Anti-Mage (690) | Broodmother (686)
| Last Hits / Min | Anti-Mage (9.58) | Meepo (9.52) | Medusa (9.38)
| Creeps Denied | Enigma (26.81) | Clockwerk (24.48) | Morphling (23.38)
| Stuns | Spirit Breaker (127.91) | Lion (112.10) | Nyx Assassin (105.96)
| Neutral Camps Stacked | Keeper of the Light (3.36) | Alchemist (2.95) | Tinker (2.90)
| Courier Kills | Bouty Hunter (0.86) | Nature's Prophet (0.31) | Riki (0.23)
| Roshan Kills with team | Ursa (2.04) | Huskar (1.71) | Meepo (1.68)
| Hero Damage / min | Tinker (995.55) | Zeus (943.54) | Spectre (836.37)
| Tower Damage / min | Lycan (280.35) | Meepo (246.75) | Clinkz (203.99)
| Taken Damage / min | Meepo (1,110.74) | Wraith King (843.69) | Timbersaw (768.96)
| Heal / min | Io (340.25) | Oracle (223.03) | Dazzle (213.43)

KDA Section is quite interesting. I guess Mirana got here because of level 25 talent, but I have no clue about Weaver.

# Hero positions

## Most popular

### Core Safelane

* **Phantom Lancer:** 2858 (53.53 wr)
* **Faceless Void:** 2836 (51.6% wr)
* **Spectre:** 2768 (**57.55%** wr)
* **Slark:** 2533 (46.39% wr)
* **Bloodseeker:** 2484 (52.62% wr)

### Core Midlane

* **Ember Spirit:** 2816 (50.25% wr)
* **Lina:** 2743 (45.72% wr)
* **Tinker:** 2479 (50.34% wr)
* **Invoker:** 2208 (52.36% wr)
* **Storm Spirit:** 2173 (51.54% wr)

### Core Offlane

* **Axe:** 3973 (**55.07%** wr)
* **Doom:** 3406 (52.14% wr)
* **Windranger:** 3205 (**56.44%** wr)
* **Beastmaster:** 2976 (47.45% wr)
* **Night Stalker:** 2455 (54.87% wr)

### Support

* **Warlock:** 6812 (53.04% wr)
* **Skywrath Mage:** 5471 (**43.26%** wr)
* **Windranger:** 3302 (**40.34%** wr)
* **Jakiro:** 3195 (48.01% wr)
* **Bane:** 2384 (51.85% wr)
* **Lion:** 2073 (50.51% wr)
* **Rubick:** 2001 (45.43% wr)
* **Disruptor:** 1906 (**44.23%** wr)
* **Io:** 1882 (46.01% wr)
* **Bounty Hunter:** 1801 (49.53% wr)

### Core Jungle

* **Bloodseeker:** 39 (41.03% wr) -- *1% of total BS matches*
* **Lycan:** 15 (40.00% wr)
* **Wraith King:** 13 (46.15% wr)
* **Enigma:** 12 (50.00% wr)
* **Mirana:** 9 (33.33% wr)

# Regions Meta

Not popular regions were sorted out. Pickban stats were gotten only for the most popular regions.

## Europe West

| Hero | Matches | Contest Rate | OI | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Warlock | 4767 | 66.25% | 34.98% | 3740 | 52.81% | 1027 | 52.78%
| Windranger | 4522 | 62.85% | 29.95% | 3533 | 48.03% | 989 | 46.31%
| Skywrath Mage | 3680 | 51.15% | 24.64% | 2902 | 47.90% | 778 | 49.23%
| Axe | 2755 | 38.29% | 20.49% | 2145 | 53.71% | 610 | 52.79%
| Bloodseeker | 2201 | 30.59% | 15.69% | 1731 | 50.95% | 470 | 52.55%
| Zeus | 1886 | 26.21% | 13.95% | 1478 | 54.19% | 408 | 49.75%
| Doom | 1872 | 26.02% | 13.26% | 1497 | 50.97% | 375 | 50.93%
| Spectre | 1822 | 25.32% | 14.57% | 1424 | 56.67% | 398 | 60.55%
| Phantom Lancer | 1787 | 24.84% | 13.65% | 1352 | 54.66% | 435 | 55.86%
| Lina | 1687 | 23.45% | 10.55% | 1311 | 44.77% | 376 | 45.74%

## US East

| Hero | Matches | Contest Rate | OI | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Windranger | 1065 | 61.49% | 31.00% | 862 | 50.58% | 203 | 49.75%
| Warlock | 976 | 56.35% | 28.35% | 770 | 50.00% | 206 | 51.46%
| Skywrath Mage | 870 | 50.23% | 24.13% | 702 | 48.72% | 168 | 45.24%
| Axe | 532 | 30.72% | 18.36% | 428 | 58.18% | 104 | 66.35%
| Mirana | 528 | 30.48% | 15.47% | 441 | 51.47% | 87 | 47.13%
| Bloodseeker | 512 | 29.56% | 16.22% | 407 | 55.28% | 105 | 53.33%
| Ember Spirit | 440 | 25.40% | 12.13% | 368 | 49.73% | 72 | 37.50%
| Spectre | 389 | 22.46% | 13.40% | 311 | 59.49% | 78 | 60.26%
| Monkey King | 379 | 21.88% | 9.76% | 318 | 44.34% | 61 | 45.90%
| Templar Assassin | 367 | 21.19% | 11.20% | 298 | 52.68% | 69 | 53.62%

## Southeast Asia

| Hero | Matches | Contest Rate | OI | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Windranger | 2501 | 56.15% | 27.84% | 2045 | 49.98% | 456 | 47.81%
| Skywrath Mage | 1887 | 42.37% | 19.98% | 1525 | 47.21% | 362 | 46.96%
| Warlock | 1708 | 38.35% | 21.49% | 1378 | 55.30% | 330 | 59.09%
| Jakiro | 1456 | 32.69% | 16.05% | 1148 | 48.61% | 308 | 50.97%
| Mirana | 1365 | 30.65% | 16.19% | 1133 | 52.96% | 232 | 52.16%
| Zeus | 1283 | 28.81% | 14.89% | 1006 | 51.69% | 277 | 51.62%
| Ember Spirit | 1241 | 27.86% | 13.90% | 983 | 49.44% | 258 | 51.55%
| Faceless Void | 1138 | 25.55% | 12.93% | 906 | 51.32% | 232 | 47.84%
| Rubick | 1112 | 24.97% | 11.43% | 906 | 45.92% | 206 | 45.15%
| Queen of Pain | 1107 | 24.85% | 11.79% | 882 | 48.75% | 225 | 42.22%

## China

| Hero | Matches | Contest Rate | OI | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Skywrath Mage | 1298 | 33.67% | 15.93% | 1298 | 47.30% | 0 | 0.00%
| Night Stalker | 1259 | 32.66% | 17.22% | 1258 | 52.70% | 1 | 100.00%
| Windranger | 1255 | 32.56% | 16.00% | 1255 | 49.16% | 0 | 0.00%
| Doom | 1141 | 29.60% | 14.29% | 1141 | 48.29% | 0 | 0.00%
| Bloodseeker | 1065 | 27.63% | 15.46% | 1065 | 55.96% | 0 | 0.00%
| Ember Spirit | 927 | 24.05% | 12.66% | 927 | 52.64% | 0 | 0.00%
| Zeus | 899 | 23.32% | 12.30% | 899 | 52.73% | 0 | 0.00%
| Jakiro | 884 | 22.93% | 11.65% | 884 | 50.79% | 0 | 0.00%
| Faceless Void | 841 | 21.82% | 10.92% | 841 | 50.06% | 0 | 0.00%
| Axe | 839 | 21.76% | 11.34% | 839 | 52.09% | 0 | 0.00%

# Notable facts

* Junglers dropped in popularity once again
* While US and EU meta is pretty similar, SEA and China meta is drastically different from them
* Another thing: China hero popularity is spread across more heroes, probably because of Random Draft

---

[Divine 5 Meta Trends - 7.16 Edition](https://www.reddit.com/r/DotA2/comments/8qlgm1/divine_5_immortal_meta_trends_716_edition/)

[Pro Circuit Season 1 Stats](https://www.reddit.com/r/DotA2/comments/8qa662/pro_circuit_season_1_stats/)

Thanks to OpenDota and STRATZ for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.

And huge thanks to my Patreon pledger *Speedy Gonzales*. Your support helps to keep up.
