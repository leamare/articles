Published: https://www.reddit.com/r/DotA2/comments/azseuo/immortal_rank_meta_trends_a_week_into_721c/

---

Spectral guy here. Yet another first-week-report. A post about Starladder Minor is coming later.

This post is based on data collected during patch 7.21c. This report includes not only ranked data, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that had abandons, ended in less than 10 minutes or had insignificantly low score (or it was impossible to get detailed draft data for them).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721c). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region specific data. The report will be updated semi-weekly (sort of).

[Ranked meta trends hub](https://spectralalliance.ru/reports/?cat=ranked)

---

# Short FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using mostly OpenDota API.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** Think of it as of smart winrate sort. It considers popularity and winrate of heroes.

# Summary

* **Matches total:** 18242
* **Missing replays:** ~100
* **Individual players spotted in matches:** 17350
* **Radiant winrate:** **55.52%** -- *Casual Radiant winrate*
* **Median match duration:** 32:28 -- *Side note: median and average match duration dropped from ~40 minutes to 31-33 minutes after patch 7.21.*
* **Median hero picks:** 1057
* **Median hero bans:** 119
* **Median hero GPM/XPM:** 427/502
* **Creeps Murdered:** 28195883

### Game Modes

* **All Draft:** 15976
* **Random Draft:** 1826
* **Captain's Mode:** 389
* **Single Draft:** 51

### Regions

* **Europe West:** 7439
* **Southeast Asia:** 4393
* **US East:** 2248 -- *WutFace*
* **China:** 2042
* **Europe East:** 907
* **Russia and CIS:** 574
* **South America:** 411
* **Australia:** 201
* **Peru:** 13
* **US West:** 5
* **Japan:** 5
* **India:** 2
* **South Africa:** 2

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

Some of those are affected by turbo matches as well, but I found it out too late, so I just marked them. Sorry for that.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
| GPM | 4504741156 | 1,460 | 小屁屁一二三 | Alchemist
| XPM | 4511728655 | 1,190 | Malevolent | Broodmother
| Kills | 4496394083 | 40 | StabsenKUK | Monkey King
| Deaths | 4501558641 | 38 | SLK mein ma fun boy | Monkey King
| Assists | 4508275343 | 56 | VOLVI RECARGADO COMO CACHA | Spirit Breaker
| KDA with 0 deaths | 4506117432 | 58 | ssk | Ember Spirit
| KDA with 1+ deaths | 4504351990 | 52 | pesanta | Mars
| Gold Earned | 4491682727 | 86,803 | Mr_Porn | Alchemist
| Last hits | 4508275343 | 1,140 | Azuki chan | Storm Spirit
| Damage to heroes | 4508275343 | 154,503 | Azuki chan | Storm Spirit
| Damage to buildings | 4500985826 | 26,465 | ZephYr | Lycan
| Hero healing | 4490206429 | 44,253 | Dead Inside | Necrophos
| Damage taken from heroes | 4511572434 | 132,797 | happy prince #82 | Meepo
| Efficiency on lane | 4492854671 | 219% | coL.Limmp | Death Prophet
| Observer wards placed | 4489196794 | 33 | famous don | Grimstroke
| Sentries placed | 4509275911 | 121 | EHOME.Innocence | Omniknight
| Obs Wards destroyed | 4486720558 | 15 | 殺 | Zeus
| Map pings | 4512872298 | 1,074 | depressed+tilted | Ursa
| Stuns | 4498730833 | 434.19 | MTRT | Elder Titan
| Couriers killed by a player | 4492058200 | 6 | Sakura~ | Bounty Hunter

# Heroes

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Lycan | 1199 | 6.57% | 100.00 | 1029 | 61.22% | 170 | 61.18%
| Bounty Hunter | 6959 | 38.15% | 99.15 | 6163 | 53.55% | 796 | 51.26%
| Io | 1005 | 5.51% | 98.29 | 897 | 57.97% | 108 | 57.41%
| Dark Seer | 940 | 5.15% | 97.44 | 784 | 57.40% | 156 | 64.10%
| Ursa | 5113 | 28.03% | 96.58 | 4526 | 53.14% | 587 | 52.81%
| Viper | 3478 | 19.07% | 95.73 | 3024 | 54.10% | 454 | 53.96%
| Pangolier | 6292 | 34.49% | 94.87 | 5589 | 52.28% | 703 | 50.64%
| Mars | 5580 | 30.59% | 94.02 | 5461 | 52.50% | 119 | 51.26%
| Meepo | 667 | 3.66% | 93.16 | 597 | 58.12% | 70 | 58.57%
| Oracle | 3237 | 17.74% | 92.31 | 2841 | 53.47% | 396 | 54.80%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Picks | Winrate | - | Hero | Picks | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Mars | 5443 | 52.51% | - | Juggernaut | 1227 | 50.77%
| Bounty Hunter | 5295 | 53.37% | - | Ursa | 1107 | 53.03%
| Pangolier | 4375 | 52.21% | - | Lifestealer | 1094 | 51.55%
| Shadow Shaman | 3417 | 51.57% | - | Phantom Assassin | 1041 | 49.38%
| Juggernaut | 3324 | 49.97% | - | Monkey King | 948 | 47.05%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Juggernaut + Bounty Hunter | 1047 | 54.44% | 95.039 | 951.961 | 90.92% | 2.96%
| Lifestealer + Bounty Hunter | 886 | 53.16% | 80.941 | 805.059 | 90.86% | 4.06%
| Shadow Shaman + Pangolier | 882 | 54.42% | 79.955 | 802.045 | 90.93% | 15.19%
| Bounty Hunter + Pangolier | 912 | 59.76% | 122.080 | 789.920 | 86.61% | 48.79%
| Juggernaut + Pangolier | 851 | 53.47% | 86.122 | 764.878 | 89.88% | 0.47%
| Shadow Shaman + Ursa | 821 | 60.05% | 63.916 | 757.084 | 92.21% | 56.03%

# Hero positions

## Most popular

### Core Safelane

* **Juggernaut:** 5123 (50.67% wr)
* **Lifestealer:** 4043 (51.79% wr)
* **Phantom Assassin:** 3571 (48.11% wr)
* **Ursa:** 3236 (54.42% wr)
* **Troll Warlord:** 2615 (48.76% wr)

Everything is pretty much like said in 7.21b post, but there are more viable carries in terms of match numbers. But Lifestealer and Juggernaut are still dominating. 

### Core Midlane

* **Viper:** 2889 (**54.90%** wr) - *Viper Effect*
* **Ember Spirit:** 2379 (50.82% wr)
* **Monkey King:** 2019 (47.70% wr)
* **Invoker:** 1858 (46.45% wr)
* **Queen of Pain:** 1748 (50.74% wr)

Kunkka suddenly disappeared from top 5 list. He's 8th now but still has pretty good winrate.

### Core Offlane

* **Pangolier:** **4263** (52.45% wr)
* **Mars:** 3568 (**52.61%** wr)
* **Bounty Hunter:** 2994 (**55.51%** wr)
* **Doom:** 1757 (51.05% wr)
* **Nature's Prophet:** 1741 (47.90% wr)

### Support

* **Shadow Shaman:** 4489 (52.15% wr)
* **Lion:** 3925 (50.37% wr)
* **Bounty Hunter:** 3666 (51.72% wr)
* **Rubick:** 3356 (48.63% wr)
* **Oracle:** 3006 (53.36% wr)
* **Grimstroke:** 2666 (46.17% wr)
* **Lich:** 2653 (47.83% wr)
* **Bane:** 2270 (54.14% wr)
* **Earth Spirit:** 2038 (48.18% wr)
* **Crystal Maiden:** 1988 (51.66% wr)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721c)

[Immortal Rank Meta Trends - 7.21b Report](https://spectralalliance.ru/reports/?league=imm_ranked_721b)

[Nerds Hero Builds](https://leamare.github.io/nerds-builds/)

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.
