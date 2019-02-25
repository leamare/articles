Published: https://www.reddit.com/r/DotA2/comments/auqssv/immortal_rank_meta_trends_a_week_into_721b/

---

Yo, Spectral guy here.

I didn't have much time recently to publish a 7.20 and 7.21 posts. Altho I'd like to make something more useful - a mid-patch report using current data for 6 full days.

This post is based on data collected during patch 7.21b. This report includes not only ranked data, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that had abandons, ended in less than 10 minutes or had insignificantly low score (or it was impossible to get detailed draft data for them).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721b). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region specific data.

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

* **Matches total:** 16635
* **Missing replays:** ~100
* **Individual players spotted in matches:** 16632
* **Radiant winrate:** 53.60%
* **Median match duration:** 32:15 -- *Side note: median and average match duration dropped from ~40 minutes to 31-33 minutes after patch 7.21*
* **Median hero picks:** 1094
* **Median hero bans:** 255
* **Median hero GPM/XPM:** 427/497
* **Total Observer Wards destroyed:** 120060

### Game Modes

* **All Draft:** 14009
* **Random Draft:** 2291
* **Captain's Mode:** 211
* **All Random:** 66
* **Single Draft:** 52
* **All Pick:** 6 *-- probably botmatches*

### Regions

* **Europe West:** 6442
* **Southeast Asia:** 4024
* **China:** 2372
* **US East:** 2065
* **Europe East:** 701
* **Russia and CIS:** 443
* **South America:** 347
* **Australia:** 141
* **Dubai:** 40
* **India:** 24
* **US West:** 21
* **Japan:** 11
* **Peru:** 3
* **South Africa:** 1

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

Some of those are affected by turbo matches as well, but I found it out too late, so I just marked them. Sorry for that.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
| GPM | 4448719456 | 1,351 | Skynet.Angel | Alchemist
| XPM | 4446967229 | 1,121 | QULE? | Anti-Mage
| Kills | 4436841181 | 39 | Nada | Ursa
| Deaths | 4433657136 | 33 | YBSEMAJ | Invoker
| Assists | 4447906489 | 49 | Teriyakidota | Io
| KDA with 0 deaths | 4447124125 | 47 | привіт | Pangolier
| KDA with 1+ deaths | 4430834242 | 47 | ALL.BLIZZARD | Monkey King
| Gold Earned | 4445522554 | 69,377 | DIMACRAZY | Lifestealer
| Last hits | 4433777598 | 1,050 | LOLITA | Anti-Mage
| Damage to heroes | 4439819209 | 149,088 | Wingblade | Queen of Pain
| Damage to buildings | 4450268900 | 28,772 | LOH | Juggernaut
| Hero healing | 4431393084 | 44,042 | Luffy | Dazzle
| Damage taken from heroes | 4430420342 | 132,070 | ベアトリーチェ | Wraith King
| Efficiency on lane | 4450259680 | 212% | YTLJBUHF | Pugna
| Observer wards placed | 4448363775 | 33 | ЗА МНОЮ ЕДЕТ КАТАФАЛК | Lich
| Sentries placed | 4432929140 | 82 | NICE啊村村 | Winter Wyvern
| Obs Wards destroyed | 4444922485 | 15 | @Maren | Lich
| Map pings | 4434072321 | 1,729 | DEPRESSED+TILTED | Ursa
| Stuns | 4444824526 | 516.90 | TECHIES | Techies
| Couriers killed by a player | 4431139713 | 5 | FLAXENGAMING | Bounty Hunter

# Heroes

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Bounty Hunter | 7476 | 44.94% | 100.00 | 5912 | 55.56% | 1564 | 55.88%
| Ursa | 5511 | 33.13% | 99.14 | 4420 | 55.09% | 1091 | 54.63%
| Lycan | 1233 | 7.41% | 98.28 | 978 | 58.38% | 255 | 60.78%
| Lifestealer | 6891 | 41.42% | 97.41 | 5452 | 53.08% | 1439 | 52.47%
| Winter Wyvern | 1764 | 10.60% | 96.55 | 1431 | 56.81% | 333 | 58.26%
| Sven | 2801 | 16.84% | 95.69 | 2269 | 55.44% | 532 | 53.20%
| Broodmother | 383 | 2.30% | 94.83 | 298 | 59.06% | 85 | 67.06%
| Necrophos | 1051 | 6.32% | 93.97 | 856 | 55.96% | 195 | 59.49%
| Shadow Shaman | 4929 | 29.63% | 93.10 | 4034 | 52.03% | 895 | 52.40%
| Magnus | 2342 | 14.08% | 92.24 | 1902 | 53.73% | 440 | 57.50%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Picks | Winrate | - | Hero | Picks | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Bounty Hunter | 3253 | 54.81% | - | Juggernaut | 3701 | 49.15%
| Shadow Shaman | 1420 | 50.21% | - | Lifestealer | 3675 | 53.77%
| Crystal Maiden | 1396 | 50.86% | - | Monkey King | 3600 | 51.08%
| Lich | 1257 | 45.19% | - | Ursa | 3103 | 55.33%
| Tiny | 1149 | 45.87% | - | Kunkka | 2425 | 51.84%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Phantom Assassin + Magnus | 615 | 55.93% | 155.727 | 459.273 | 74.68% | 48.78%
| Luna + Io | 376 | 53.99% | 44.095 | 331.905 | 88.27% | 88.56%
| Juggernaut + Lich | 839 | 46.48% | 559.008 | 279.992 | 33.37% | 78.90%
| Gyrocopter + Io | 263 | 51.33% | 18.411 | 244.589 | 93.00% | 92.78%
| Juggernaut + Magnus | 512 | 53.52% | 296.248 | 215.752 | 42.14% | 39.65%
| Doom + Grimstroke | 398 | 49.25% | 216.912 | 181.088 | 45.50% | 47.49%

# Hero positions

## Most popular

### Core Safelane

* **Lifestealer:** 4858 (53.54% wr)
* **Juggernaut:** 4742 (49.49% wr)
* **Phantom Assassin:** 2446 (49.59% wr)
* **Ursa:** 2035 (56.07% wr)
* **Troll Warlord:** 1694 (50.77% wr)

Remember how I was bitching about only five cores being viable and signifcantly more popular than others?

Well, this time we have only two: Lifestealer and Juggernaut. PA takes the third place and has almost two times less matches.

### Core Midlane

* **Kunkka:** 2436 (52.30% wr)
* **Monkey King:** 2393 (52.82% wr)
* **Outworld Devourer:** 2209 (**45.41%** wr)
* **Viper:** 1538 (**54.94%** wr)
* **Invoker:** 1472 (52.72% wr)

### Core Offlane

That's some juicy stuff. The reason of low safelane cores versatility is, I believe, strong offlane pool. I'd like to list a bit more of them this time.

* **Pangolier:** 2313 (50.06% wr) -- *Perfectly balanced Kappa*
* **Nature's Prophet:** 1940 (49.28% wr)
* **Bounty Hunter:** 1915 (**56.29%** wr) -- *He's also pretty popular as pos 1, I believe*
* **Ursa:** 1835 (**56.57%** wr)
* **Doom:** 1590 (49.18% wr)
* **Slardar:** 1475 (51.32% wr)
* **Tiny:** 1385 (43.47% wr)
* **Sven:** 1345 (**55.39%** wr)

### Support

* **Shadow Shaman:** 3769 (52.53% wr)
* **Lich:** 3576 (47.85% wr)
* **Bounty Hunter:** 3564 (55.05% wr)
* **Grimstroke:** 3336 (50.03% wr)
* **Rubick:** 2833 (48.11% wr)
* **Crystal Maiden:** 2803 (52.12% wr)
* **Lion:** 2799 (51.02% wr)
* **Tusk:** 2447 (46.71% wr)
* **Earth Spirit:** 2244 (45.81% wr)
* **Oracle:** 2207 (49.71% wr)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721b)

[Immortal Rank Meta Trends - 7.21 Report](https://spectralalliance.ru/reports/?league=imm_ranked_721)

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.
