Published: https://www.reddit.com/r/DotA2/comments/9yx0md/immortal_rank_meta_trends_post719d_edition/?

---

Hey, Spectral stats guy is here again.

This post is based on data collected during patch 7.19d. This report includes not only ranked data, but stats of all matches with average rank equal to Immortal. This addition should make all this data a bit more interesting. Excluded matches are the ones that had abandons, ended in less than 10 minutes or had insignificantly low score.

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_719d). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region specific data.

At the time this post will be up, there will also be available [initial version of 7.20 report](https://spectralalliance.ru/reports/?league=imm_ranked_720) with matches for around 20 first hours of 7.20 patch.

I didn't include any regional specific data this time, but it all can be found in the report. Tell me if you found something that you found interesting!

[Ranked meta trends hub](https://spectralalliance.ru/reports/?cat=ranked)

---

# Short FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using mostly OpenDota API.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** It's ranked version of `(wins_picked+wins_banned)/matches_total`. It will be replaced later on, but right now it's here mostly to see most effective heroes in the meta.
* **What changed after changing ranked only matches to all matches?** Basically more matches. Additional matches don't really affect stats, but it shows that Immortal rank people don't only play ranked (and what game modes they like better) and shows that there are actual immortal rank players in other regions (and you can see what game modes are more popular in every region). It also helps me when I work with all this data locally.

# Summary

* **Matches total:** 64530
* **Missing replays:** 78
* **Individual players spotted in matches:** 25888
* **Radiant winrate:** 53.72%
* **Median match duration:** 49:31
* **Median hero picks:** 3874
* **Median hero bans:** 838
* **Median hero GPM/XPM:** 578/660
* **Total Couriers Killed:** 35166
* **Creeps murdered for IceFrog's glory:** 107406560

### Game Modes

* **All Draft:** 50954
* **Random Draft:** 11565
* **Captain's Mode:** 1806
* **Single Draft:** 172
* **Captain's Draft:** 15
* **All Pick:** 10 *-- probably botmatches*
* **Turbo:** 8

### Regions

* **Europe West:** 24803
* **Southeast Asia:** 14714
* **China:** 11864
* **US East:** 7870
* **Europe East:** 1261
* **Japan:** 1167
* **South America:** 1048
* **Russia and CIS:** 855
* **Australia:** 813
* **US West:** 61
* **Peru:** 41
* **India:** 25
* **Dubai:** 5
* **Chile:** 3

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

Some of those are affected by turbo matches as well, but I found it out too late, so I just marked them. Sorry for that.

|Record | Match | Value | Player | Hero |
|:--|:-:|:-:|:-:|:-:|
| GPM | 4195349522 - Turbo | 1,744 | Rainman | Meepo
| XPM | 4195349522 - Turbo | 2,360 | Rainman | Meepo
| Kills | 4224731711 | 50 | uber driver | Monkey King
| Deaths | 4186026212 | 49 | zero | Silencer
| Assists | 4223113355 | 68 | VLONE | Spirit Breaker
| KDA with 0 deaths | 4224515237 | 56 | #Sukinada | Queen of Pain
| KDA with 1+ deaths | 4202897305 | 56 | THIS FISH IS SO RAW | Faceless Void
| Gold Earned | 4223113355 | 124,206 | **syndreN** | Phantom Lancer
| Last hits | 4223113355 | 2,151 | **syndreN** | Phantom Lancer
| Damage to heroes | 4185465033 | 202,787 | Gunnar | Ember Spirit
| Damage to buildings | 4171651743 | 28,340 | 宇宙第一 | Lycan
| Hero healing | 4182777538 | 73,290.00 | Neo | Io
| Damage taken from heroes | 4223113355 | 224,813 | Sundress | Arc Warden
| Observer wards placed | 4223113355 | 51 | maki | Ogre Magi
| Sentries placed | 4200188242 | 139 | (L)edend | Oracle
| Obs Wards destroyed | 4224774216 | 19 | I'ma be a loner | Undying
| Map pings | 4219825750 | 1,991 | fuck love | Necrophos
| Stuns | 4223113355 | 1,097.13 | Lil | Techies
| Player with Widest Hero Pool |  | 89 | **EHOME.Innocence** |
| Player with Smallest Hero Pool |  | 1 | 沐风

# Heroes

**[Hero Graph](https://spectralalliance.ru/reports/?league=imm_ranked_720&mod=heroes-meta_graph)**

## Sorted by Rank

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Slark | 533 | 47.80% | 100.00 | 411 | 59.85% | 122 | 58.20%
| Dazzle | 501 | 44.93% | 99.14 | 415 | 54.46% | 86 | 53.49%
| Bounty Hunter | 460 | 41.26% | 98.28 | 375 | 49.33% | 85 | 45.88%
| Monkey King | 399 | 35.78% | 97.41 | 328 | 45.12% | 71 | 49.30%
| Lich | 346 | 31.03% | 96.55 | 281 | 48.40% | 65 | 50.77%
| Ogre Magi | 367 | 32.91% | 95.69 | 304 | 45.39% | 63 | 49.21%
| Brewmaster | 297 | 26.64% | 94.83 | 240 | 54.58% | 57 | 59.65%
| Luna | 277 | 24.84% | 93.97 | 224 | 54.91% | 53 | 52.83%
| Meepo | 191 | 17.13% | 93.10 | 143 | 72.73% | 48 | 79.17%
| Lion | 262 | 23.50% | 92.24 | 214 | 50.93% | 48 | 43.75%

## Pick Stages

### Stage 1 of Picks (first two picks) / Stage 3 of Picks (last pick)

| Hero | Picks | Winrate | - | Hero | Picks | Winrate |
|:--|:-:|:-:|:-:|:--|:-:|:-:|
| Grimstroke | 10000 | 50.12% | - | Monkey King | 13637 | 47.79%
| Earthshaker | 9340 | 51.34% | - | Necrophos | 11850 | 52.62%
| Phoenix | 7339 | 50.77% | - | Terrorblade | 11466 | 52.48%
| Ogre Magi | 6918 | 49.74% | - | Storm Spirit | 11130 | 48.91%
| Tiny | 5887 | 45.91% | - | Invoker | 11102 | 51.53%

## Hero Combos (sorted by deviation)

| Heroes | Matches | Winrate | Expectation | Deviation | Percentage | Same Lane Rate
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Gyrocopter + Io | 2912 | 59.44% | 160.650 | 2,751.350 | 94.48% | 94.75%
| Centaur Warrunner + Grimstroke | 2330 | 56.05% | 1,533.503 | 796.497 | 34.18% | 77.90%
| Drow Ranger + Mirana | 1140 | 56.49% | 683.037 | 456.963 | 40.08% | 0.96%
| Earthshaker + Phantom Lancer | 2377 | 53.64% | 1,949.559 | 427.441 | 17.98% | 7.24%
| Faceless Void + Phoenix | 1163 | 56.66% | 800.625 | 362.375 | 31.16% | 31.99%
| Earthshaker + Mirana | 2857 | 53.34% | 2,509.424 | 347.576 | 12.17% | 45.50%

## Lane Combos

| Heroes | Matches | Winrate | Most Common Lane
|:-:|:-:|:-:|:-:|
| Gyrocopter + Io | 2759 | 59.95% | Offlane
| Centaur Warrunner + Grimstroke | 1815 | 56.03% | Offlane
| Earthshaker + Necrophos | 1556 | 56.43% | Safelane
| Tiny + Grimstroke | 1502 | 46.94% | Offlane
| Axe + Grimstroke | 1411 | 51.31% | Offlane


# Hero positions

## Most popular

### Core Safelane

* **Terrorblade:** 14807 (52.87% wr)
* **Phantom Lancer:** 10366 (49.83% wr)
* **Monkey King:** 9165 (48.14% wr)
* **Morphling:** 7371 (45.75% wr)
* **Weaver:** 6531 (48.15% wr)

### Core Midlane

* **Invoker:** 12199 (51.94% wr)
* **Storm Spirit:** 11916 (49.19% wr)
* **Lina:** 10087 (**42.76%** wr)
* **Tinker:** 8000 (49.98% wr)
* **Zeus:** 6079 (54.37% wr)

### Core Offlane

* **Tiny:** 13218 (**46.34%** wr)
* **Axe:** 12893 (52.00% wr)
* **Necrophos:** 9667 (53.52% wr)
* **Centaur Warrunner:** 9329 (**55.59%** wr)
* **Ursa:** 7800 (51.33% wr)

### Support

* **Earthshaker:** 13646 (52.46% wr)
* **Grimstroke:** 12618 (51.05% wr)
* **Ogre Magi:** 12051 (50.37% wr)
* **Winter Wyvern:** 10389 (51.42% wr)
* **Silencer:** 10242 (51.06% wr)
* **Phoenix:** 9946 (53.15% wr)
* **Treant Protector:** 8698 (50.94% wr)
* **Undying:** 7723 (51.15% wr)
* **Shadow Shaman:** 6725 (53.32% wr)
* **Pudge:** 6311 (48.15% wr)

# Bonus - Day 1 7.20 hero stats

| Hero | Matches | Contest Rate | Rank | Picked | Winrate | Banned | Winrate |
|:--|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| Slark | 533 | 47.80% | 100.00 | 411 | 59.85% | 122 | 58.20%
| Dazzle | 501 | 44.93% | 99.14 | 415 | 54.46% | 86 | 53.49%
| Bounty Hunter | 460 | 41.26% | 98.28 | 375 | 49.33% | 85 | 45.88%
| Monkey King | 399 | 35.78% | 97.41 | 328 | 45.12% | 71 | 49.30%
| Lich | 346 | 31.03% | 96.55 | 281 | 48.40% | 65 | 50.77%
| Ogre Magi | 367 | 32.91% | 95.69 | 304 | 45.39% | 63 | 49.21%
| Brewmaster | 297 | 26.64% | 94.83 | 240 | 54.58% | 57 | 59.65%
| Luna | 277 | 24.84% | 93.97 | 224 | 54.91% | 53 | 52.83%
| Meepo | 191 | 17.13% | 93.10 | 143 | 72.73% | 48 | 79.17%
| Lion | 262 | 23.50% | 92.24 | 214 | 50.93% | 48 | 43.75%

# Notable Matches

* The longest match (2:07:00) and the match with most kills combined (202) is [4223113355](https://dotabuff.com/matches/4223113355). It's the same match with Lil Techies and syndreN PL
* Most couriers killed in a match [4228049799](https://dotabuff.com/matches/4228049799) (8)
* Most Roshans killed in a match [4199856318](https://dotabuff.com/matches/4199856318) (9)
* Biggest Networth stomp by a team in a match [4217970503](https://dotabuff.com/matches/4217970503) (62,153)
* Biggest Networth comeback by a team in a match [4178939515](https://dotabuff.com/matches/4178939515) (48,522)

---

And yet again, [full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_720)

[Immortal Rank Meta Trends - 7.19b Report](https://spectralalliance.ru/reports/?league=imm_ranked_719b)

[Competitive Meta Trends - The Kuala Lumpur Major](https://www.reddit.com/r/DotA2/comments/9y9xas/competitive_meta_trends_kuala_lumpur_major/)

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.
