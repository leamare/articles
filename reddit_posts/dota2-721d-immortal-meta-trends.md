Published: https://www.reddit.com/r/DotA2/comments/b8ezfi/immortal_rank_meta_trends_a_week_into_721d/

---

Spectral guy here. Yet another first-week-report. There is also NADCL Season 3 post in works. Not sure about major qualifiers, let me know if you're interested.

This post is based on data collected during the first week of patch 7.21d. This report includes not only ranked data, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that had abandons, ended in less than 10 minutes or had insignificantly low score (or it was impossible to get detailed draft data for them).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

There's something off about draft stages at the moment, just ignore it for now.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721d). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region specific data. The report will be updated semi-weekly (sort of).

[Ranked meta trends hub](https://spectralalliance.ru/reports/?cat=ranked)

---

# Short FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using mostly OpenDota API.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that. Also privacy stuff.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** Think of it as of smart winrate sort. It considers popularity and winrate of heroes.
* **Is it strictly Immortal Rank?** Not for now, there may be some random individual divine players here and there. Altho, an "Immortal Rank" match is usually the match with at least 9 immortal players in it.

# Summary

* **Matches total:** 18480
* **Missing replays:** ~500
* **Individual players spotted in matches:** 15717
* **Radiant winrate:** **55.27%**
* **Median match duration:** 32:04 -- *Side note: median and average match duration dropped from ~40 minutes to 31-33 minutes after patch 7.21.*
* **Median hero picks:** 1182
* **Median hero bans:** 31
* **Median hero GPM/XPM:** 422/492
* **Total buybacks:** 84736

### Game Modes

* **All Draft:** 15717
* **Random Draft:** 2195
* **Captain's Mode:** 502
* **Single Draft:** 64

### Regions

* **Europe West:** 7148
* **Southeast Asia:** 4271
* **US East:** 2507
* **China:** 2423
* **Europe East:** 698
* **Russia and CIS:** 623
* **South America:** 521
* **Australia:** 273
* **US West:** 12
* **Japan:** 3
* **South Africa:** 1

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

Some of those are affected by turbo matches as well, but I found it out too late, so I just marked them. Sorry for that.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
| GPM | [4573828338](https://stratz.com/matches/4573828338/) | 1,351 | 保 | Alchemist
| XPM | [4580849005](https://stratz.com/matches/4580849005/) | 1,213 | mid smurf muted | Monkey King
| Kills | [4571753126](https://stratz.com/matches/4571753126/) | 43 | NO REST FOR THE WICKED | Phantom Assassin
| Deaths | [4573135266](https://stratz.com/matches/4573135266/) | 33 | Biblibio | Lich
| Assists | [4584068072](https://stratz.com/matches/4584068072/) | 54 | CR | Disruptor
| KDA with 0 deaths | [4578368569](https://stratz.com/matches/4578368569/) | 47 | Bryle | Ember Spirit
| KDA with 1+ deaths | [4582251770](https://stratz.com/matches/4582251770/) | 49 | SERIPERI | Batrider
| Gold Earned | [4578129638](https://stratz.com/matches/4578129638/) | 75,838 | NOMLOG SANKE | Bounty Hunter
| Last hits | [4574704005](https://stratz.com/matches/4574704005/) | 1,184 | MODE: PLOV | Anti-Mage
| Damage to heroes | [4592167433](https://stratz.com/matches/4592167433/) | 145,025 | KEXIT | Necrophos
| Damage to buildings | [4585283067](https://stratz.com/matches/4585283067/) | 29,157 | lakhkandola | Anti-Mage
| Hero healing | [4592776136](https://stratz.com/matches/4592776136/) | 56,862 | JAYDP111 | Io
| Damage taken from heroes | [4592167433](https://stratz.com/matches/4592167433/) | 186,985 | ESKALATION | Meepo
| Efficiency on lane | [4577810385](https://stratz.com/matches/4577810385/) | 225% | Y.Y | Alchemist
| Observer wards placed | [4585730442](https://stratz.com/matches/4585730442/) | 34 | ASMNASMN | Oracle
| Sentries placed | [4575103734](https://stratz.com/matches/4575103734/) | 87 | positive player (techies spammer) | Dark Willow
| Obs Wards destroyed | [4584520256](https://stratz.com/matches/4584520256/) | 16 | Zero | Witch Doctor
| Map pings | [4585518468](https://stratz.com/matches/4585518468/) | 1,486 | Epileptic kid (aka depressed+tilted) | Morphling
| Stuns | [4577235046](https://stratz.com/matches/4577235046/) | 490.15 | Changes | Invoker
| Couriers killed by a player | [4595438787](https://stratz.com/matches/4595438787/) | 5 | 7seeds.SadbOy | Bounty Hunter

Just a side note. I looked through 7.21c final report and noticed that there's a competitor to Epileptic kid in terms of map pings. And the rival comes from SEA.

# Heroes

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Lycan | 1239 | 6.70% | 100.00 | 1185 | 60.42% | 54 | 46.30%
| Mars | 6517 | 35.27% | 99.15 | 6517 | 54.23% | 0 | 0.00%
| Io | 1098 | 5.94% | 98.29 | 1098 | 58.56% | 0 | 0.00%
| Nyx Assassin | 2582 | 13.97% | 97.44 | 2418 | 56.70% | 164 | 44.51%
| Bounty Hunter | 6604 | 35.74% | 96.58 | 6427 | 53.26% | 177 | 48.02%
| Necrophos | 2019 | 10.93% | 95.73 | 1980 | 56.01% | 39 | 53.85%
| Meepo | 885 | 4.79% | 94.87 | 841 | 58.03% | 44 | 59.09%
| Shadow Shaman | 6853 | 37.08% | 94.02 | 6746 | 51.70% | 107 | 59.81%
| Dark Seer | 1276 | 6.90% | 93.16 | 1123 | 56.63% | 153 | 45.75%
| Winter Wyvern | 1700 | 9.20% | 92.31 | 1672 | 54.25% | 28 | 64.29%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Phantom Assassin + Magnus | 353 | 48.44% | 73.973 | 279.027 | 79.04% | 35.98%
| Dark Willow + Mars | 593 | 50.59% | 326.026 | 266.974 | 45.02% | 53.46%
| Doom | grimstroke + 323 | 44.27% | 140.167 | 182.833 | 56.60% | 43.96%
| Shadow Shaman + Ursa | 965 | 53.06% | 792.144 | 172.856 | 17.91% | 54.82%
| Juggernaut + Lich | 363 | 47.38% | 214.534 | 148.466 | 40.90% | 79.89%
| Juggernaut + Magnus | 245 | 50.20% | 167.561 | 77.439 | 31.61% | 24.08%

# Hero positions

## Most popular

### Core Safelane

* **Juggernaut:** 5444 (50.66% wr)
* **Troll Warlord:** 2955 (49.04% wr)
* **Ursa:** 2787 (53.79% wr)
* **Lifestealer:** 2776 (49.89% wr)
* **Phantom Assassin:** 2378 (44.03% wr)

Everything is pretty much like said in 7.21b post, but there are more viable carries in terms of match numbers. But Lifestealer and Juggernaut are still dominating. Numbers are almost identical to 7.21c.

### Core Midlane

* **Ember Spirit:** 2637 (52.45% wr)
* **Shadow Fiend:** 2084 (47.98% wr)
* **Queen of Pain:** 1899 (48.24% wr)
* **Outworld Devourer:** 1847 (44.18% wr)
* **Lina:** 1780 (**48.48%** wr)

### Core Offlane

* **Mars:** 4859 (**55.24%** wr)
* **Pangolier:** **2873** (46.71% wr)
* **Bounty Hunter:** 2366 (**54.65%** wr)
* **Doom:** 2156 (48.01% wr)
* **Nature's Prophet:** 1310 (47.33% wr)

### Support

* **Shadow Shaman:** 6332 (52.01% wr)
* **Lion:** 4332 (48.52% wr)
* **Oracle:** 4253 (50.48% wr)
* **Bounty Hunter:** 3677 (52.13% wr)
* **Rubick:** 2953 (47.24% wr)
* **Tiny:** 2283 (48.58% wr)
* **Nyx Assassin:** 2145 (57.48% wr)
* **Abaddon:** 2094 (53.10% wr)
* **Bane:** 1986 (52.62% wr)
* **Earth Spirit:** 1932 (47.67% wr)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_721d)

[Immortal Rank Meta Trends - 7.21c Report](https://spectralalliance.ru/reports/?league=imm_ranked_721c)

[Nerds Hero Builds](https://leamare.github.io/nerds-builds/)

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.
