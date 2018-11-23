Published: https://www.reddit.com/r/DotA2/comments/9o3331/immortal_rank_meta_trends_719c_edition/?

---

Hey, Spectral stats guy is here again. I was busy with other things after TI2018, so I missed 7.19b post, but as you could notice the report was still available. There were also some replay availability issues back then.

This post is based on data collected during patch 7.19c. It includes most of ranked matches that were played on Immortal rank in patch 7.19 (except ones that had abandons, ended in less than 10 minutes or had insignificantly low score).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_719c). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region spacific data.

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

* **Matches total:** 44738
* **Missing replays:** 26
* **Individual players spotted in matches:** 20555
* **Radiant winrate:** 54.43%
* **Average match duration:** 36:13
* **Total Buybacks:** 258233 (5.77 per match on average)
* **Total Couriers Killed:** 25448 

### Game Modes

* **All Draft:** 81.59% (36503)
* **Random Draft:** 18.41% (8235)

### Regions

* **Europe West:** 16825
* **Southeast Asia:** 11515
* **China:** 8242
* **US East:** 5790
* **Europe East:** 828
* **South America:** 656
* **Australia:** 475
* **Russia:** 367
* **US West:** 37
* **Japan:** 3

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
|GPM | 4138761328 | 1,332 | Sirc Cancer Try me | Alchemist
|XPM | 4140440154 | 1,402 | FUCKING APE | Meepo
|Kills | 4162511202 | 58 | Avaricous | Weaver
|Deaths | 4130216132 | 36 | Mr | Nature's Prophet
|Assists | 4135938255 | 71 | люди ночного мира | Zeus
|KDA with 0 deaths | 4126194770 | 50 | x3s | Ember Spirit
|KDA with 1+ deaths | 4142475557 | 67 | 待雨停 | Ember Spirit
|Gold Earned | 4162511202 | 139,736 | nnnn_nova | Zeus
|Last hits | 4162511202 | 1,849 | nnnn_nova | Zeus
|Damage to heroes | 4162511202 | 204,150 | nnnn_nova | Zeus
|Damage to buildings | 4142928149 | 24,946 | vk.com/s7ptember | Lycan
|Hero healing | 4156834383 | 62,654 | jojo | Treant Protector
|Damage taken from heroes | 4137442457 | 179,069 | стреляй,мэнi Пи}{уй | Meepo
|Efficiency on lane | 4137466674 | 208% | #1 TUSK in NA 💙 | Pugna
|Observer wards placed | 4162511202 | 55 | Slander | Grimstroke
|Sentries placed | 4162511202 | 339 | cheve | Bane
|Obs Wards destroyed | 4124800498 | 19 | Palawan Pawnshop Pera Padala | Vengeful Spirit
|Map pings | 4142894656 | 65,535 | broken | Ursa
|Crowd Control | 4161655223 | 650.99 | tsl | Invoker
|Couriers killed by a player | 4127631523 | 7.00 | Hey Ho (A1taoda) | Bounty Hunter

# Heroes

**[Hero Graph](https://spectralalliance.ru/reports/?league=imm_ranked_719c&mod=heroes-meta_graph)**

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Grimstroke | 19931 | 44.55% | 100.00 | 15990 | 50.35% | 3941 | 50.04%
| Earthshaker | 18851 | 42.14% | 99.14 | 15764 | 51.98% | 3087 | 51.28%
| Weaver | 19557 | 43.71% | 98.28 | 15857 | 49.52% | 3700 | 49.11%
| Treant Protector | 15043 | 33.62% | 97.41 | 12158 | 54.24% | 2885 | 54.28%
| Silencer | 15596 | 34.86% | 96.55 | 12881 | 52.08% | 2715 | 50.42%
| Tiny | 17656 | 39.47% | 95.69 | 14681 | 45.61% | 2975 | 44.20%
| Ursa | 15006 | 33.54% | 94.83 | 12272 | 52.47% | 2734 | 51.43%
| Necrophos | 14177 | 31.69% | 93.97 | 11759 | 53.06% | 2418 | 50.91%
| Terrorblade | 11876 | 26.55% | 93.10 | 9621 | 55.69% | 2255 | 56.81%
| Storm Spirit | 12556 | 28.07% | 92.24 | 10066 | 48.84% | 2490 | 46.99%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Picks | Winrate | - | Hero | Picks | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Grimstroke | 9664 | 50.65% | - | Weaver | 9960 | 49.62%
| Earthshaker | 7013 | 51.49% | - | Storm Spirit | 9040 | 48.71%
| Treant Protector | 6284 | 54.49% | - | Ursa | 8789 | 52.38%
| Silencer | 4021 | 52.40% | - | Tiny | 8025 | 46.44%
| Phoenix | 3158 | 51.08% | - | Phantom Lancer | 8010 | 50.00%

> PL is perfectly balanced Kappa

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Gyrocopter | wisp | Io | 966 | 57.66% | 54.987 | 911.013 | 94.31% | 90.27%
| Wraith King + Grimstroke | 1872 | 52.40% | 1,238.619 | 633.381 | 33.83% | 71.79%
| Drow Ranger + Weaver | 1319 | 53.98% | 924.383 | 394.617 | 29.92% | 1.29%
| Drow Ranger + Storm Spirit | 978 | 50.31% | 586.797 | 391.203 | 40.00% | 0.20%
| Drow Ranger + Vengeful Spirit | 609 | 53.04% | 243.790 | 365.210 | 59.97% | 56.98%
| Drow Ranger + Mirana | 739 | 51.83% | 431.616 | 307.384 | 41.59% | 1.35%

## Lane Combos

| Heroes | Matches | Winrate | Most Common Lane
|:-:|:-:|:-:|:-:|
| Wraith King + Grimstroke | 1344 | 52.08% | Offlane
| Weaver + Grimstroke | 1317 | 45.94% | Offlane
| Weaver + Treant Protector | 1217 | 52.42% | Offlane
| Tiny + Grimstroke | 1201 | 46.21% | Offlane
| Earthshaker + Weaver | 1123 | 52.89% | Offlane
| Silencer + Terrorblade | 1095 | 58.26% | Safelane


# Hero positions

## Most popular

### Core Safelane

* **Terrorblade:** 8412 (**56.19%** wr)
* **Phantom Lancer:** 7819 (49.53% wr)
* **Weaver:** 6680 (49.12% wr)
* **Ursa:** 6117 (53.65% wr)
* **Spectre:** 5475 (49.13% wr)

### Core Midlane

* **Storm Spirit:** 9601 (49.07% wr)
* **Invoker:** 7514 (49.73% wr)
* **Lina:** 5718 (**45.00%** wr)
* **Tinker:** 5359 (50.83% wr)
* **Zeus:** 5053 (**55.29%** wr)

### Core Offlane

* **Tiny:** 8991 (**45.92%** wr)
* **Weaver:** 8608 (50.13% wr)
* **Necrophos:** 6139 (**54.47%** wr)
* **Wraith King:** 4869 (51.98% wr)
* **Ursa:** 4640 (52.54% wr)

### Support

* **Grimstroke:** 12937 (51.71% wr)
* **Earthshaker:** 12774 (52.90% wr)
* **Silencer:** 12668 (52.22% wr)
* **Treant Protector:** 11745 (**54.33%** wr)
* **Winter Wyvern:** 7820 (52.66% wr)
* **Dark Willow:** 6994 (47.03% wr)
* **Crystal Maiden:** 6403 (53.38% wr)
* **Phoenix:** 6363 (52.55% wr)
* **Pudge:** 6214 (48.83% wr)
* **Undying:** 5413 (51.39% wr)


### Core Jungle

* **Terrorblade:** 90 (47.78% wr) -- 0.94% of matches
* **Bloodseeker:** 48 (**33.33%** wr) -- 0.84% of matches
* **Alchemist:** 46 (50.00% wr) -- 1.08% of matches
* **Enigma:** 32 (**37.50%** wr) -- 1.37% of matches
* **Nature's Prophet:** 30 (**30.00%** wr) -- 0.97% of matches

# Regions Meta

Not popular regions were sorted out. Pickban stats were gotten only for the most popular regions.

## Europe West

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Grimstroke | 9650 | 57.36% | 100.00 | 7307 | 51.32% | 2343 | 51.73%
| Weaver | 8183 | 48.64% | 99.14 | 6328 | 48.93% | 1855 | 49.54%
| Silencer | 6341 | 37.69% | 98.28 | 5083 | 52.43% | 1258 | 51.35%
| Earthshaker | 6216 | 36.95% | 97.41 | 4969 | 51.86% | 1247 | 52.85%
| Tiny | 6950 | 41.31% | 96.55 | 5476 | 45.62% | 1474 | 43.76%
| Treant Protector | 5484 | 32.59% | 95.69 | 4300 | 55.21% | 1184 | 55.32%
| Phoenix | 5611 | 33.35% | 94.83 | 4300 | 50.95% | 1311 | 52.17%

## US East

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Earthshaker | 2360 | 40.76% | 100.00 | 1933 | 51.37% | 427 | 49.18%
| Treant Protector | 2108 | 36.41% | 99.14 | 1657 | 56.37% | 451 | 57.21%
| Weaver | 2438 | 42.11% | 98.28 | 1968 | 48.83% | 470 | 47.87%
| Silencer | 2213 | 38.22% | 97.41 | 1772 | 53.61% | 441 | 52.61%
| Terrorblade | 2029 | 35.04% | 96.55 | 1588 | 58.06% | 441 | 58.05%
| Ursa | 2138 | 36.93% | 95.69 | 1713 | 52.83% | 425 | 50.35%
| Grimstroke | 2125 | 36.70% | 94.83 | 1652 | 48.12% | 473 | 48.41%

## Southeast Asia

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Earthshaker | 6809 | 59.13% | 100.00 | 5571 | 52.07% | 1238 | 50.97%
| Weaver | 5791 | 50.29% | 99.14 | 4631 | 49.43% | 1160 | 49.05%
| Treant Protector | 5350 | 46.46% | 98.28 | 4247 | 53.12% | 1103 | 52.22%
| Ursa | 4466 | 38.78% | 97.41 | 3574 | 53.55% | 892 | 54.93%
| Tiny | 5305 | 46.07% | 96.55 | 4358 | 45.48% | 947 | 43.93%
| Silencer | 4511 | 39.17% | 95.69 | 3682 | 50.79% | 829 | 47.29%
| Necrophos | 4016 | 34.88% | 94.83 | 3239 | 54.68% | 777 | 52.64%

## China

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Earthshaker | 2555 | 31.00% | 100.00 | 2555 | 52.41% | 0 | 0.00%
| Necrophos | 2533 | 30.73% | 99.14 | 2533 | 52.31% | 0 | 0.00%
| Grimstroke | 2616 | 31.74% | 98.28 | 2614 | 50.65% | 2 | 0.00%
| Terrorblade | 2075 | 25.18% | 97.41 | 2075 | 55.33% | 0 | 0.00%
| Tiny | 2480 | 30.09% | 96.55 | 2480 | 46.05% | 0 | 0.00%
| Weaver | 2160 | 26.21% | 95.69 | 2160 | 51.81% | 0 | 0.00%
| Ursa | 2089 | 25.35% | 94.83 | 2089 | 51.65% | 0 | 0.00%
| Zeus | 1909 | 23.16% | 93.97 | 1909 | 52.17% | 0 | 0.00%
| Monkey King | 2023 | 24.55% | 93.10 | 2023 | 47.95% | 0 | 0.00%
| Silencer | 1632 | 19.80% | 92.24 | 1632 | 52.39% | 0 | 0.00%

# Notable Matches

* Most Roshan kills in match [4162511202](https://dotabuff.com/matches/4162511202) (9). It's also the longest match of the patch (2:07:02). Featuring TPB.XaKoH as offlane Ogre Magi, Slander as support Grimstroke, some random techies spammer as Techies
* Most couriers killed in a match [4137465873](https://dotabuff.com/matches/4137465873) (9), featuring Waga as Bounty Hunter and Stormstormer as Lina
* Biggest Networth stomp by a team in a match [4157753494](https://dotabuff.com/matches/4157753494) (84,851), featuring 163 as Zeus, h) as Rubick, BLACKARXANGEL as Mirana, 4ndreJkee as Venomancer
* Biggest Networth comeback by a team in a match [4125714131](https://dotabuff.com/matches/4125714131) (48,190)
* The Shortest match was [4146881322](https://dotabuff.com/matches/4146881322) (10:01)
* Bloodbath with most kills combined was in match [4128000612](https://dotabuff.com/matches/4128000612) (188 kills total)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_719c)

You can also check out Nerds Hero Builds project. I'm trying to make fully detailed guides (not only for default positions, but also something unusual) for every hero with meta builds based on Immortal Rank matches and hero spammers commentaries and containing everything that may be useful. [Nerds Hero Builds site](https://leamare.github.io/nerds-builds/)

[Immortal Rank Meta Trends - 7.19 Edition Post](https://www.reddit.com/r/DotA2/comments/9cskst/immortal_rank_meta_trends_719_edition/)

[Immortal Rank Meta Trends - 7.19b Report](https://spectralalliance.ru/reports/?league=imm_ranked_719b)

[Spectral Alliance twitter](https://twitter.com/SpectralDota) - for english speakers

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.
