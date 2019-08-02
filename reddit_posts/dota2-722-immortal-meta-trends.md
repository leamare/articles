# Immortal Rank Meta Trends - two weeks into 7.22
Published: https://www.reddit.com/r/DotA2/comments/byc53d/immortal_rank_meta_trends_two_weeks_into_722/

---

Spectral guy here. Sorry for the delay. I'm working on some awesome stuff aside from DPC and Immortal Rank reports, didn't have much time to make a post before.

This post is based on data collected during the first two weeks of patch 7.22 (the b patch is considered the same patch). This report includes not only ranked data, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that had abandons, ended in less than 10 minutes or had insignificantly low score (or it was impossible to get detailed draft data for them).

Positions data may be inaccurate in some way (mostly so that very bad core games are counted as support while supports who had high stats and didn't spent much on support items may be considered core), but it's most likely to be insignificant.

[Full report is available here](https://spectralalliance.ru/reports/?league=imm_ranked_722). You can look through data by yourself if you want, maybe you'll find something interesting as well. There are more detailed data about Hero VS Hero performance, Draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region specific data. The report will be updated (almost) daily.

### [Ranked meta trends hub](https://stats.spectral.gg/lrg2/?cat=ranked) | [Spectral Stats Hub](https://stats.spectral.gg/lrg2/)

---

# FAQ

* **Why so little matches played in REGION NAME?** On higher ranks it's common to queue for game on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using OpenDota API.
* **Why there are only random draft matches played in China?** They just like playing random draft ever since DotA All-Stars days.
* **What does banned winrate mean?** It's winrate of a player (and his team) who nominated a hero for ban.
* **Can I see individual players stats somewhere?** Techically - yes. But there are too much players, reports are getting too big and unreadable because of that. Also privacy stuff.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** Think of it as of smart winrate sort. It considers popularity and winrate of heroes.
* **Is it strictly Immortal Rank?** Almost. I'm not checking all the matches by myself (it would take too much time, requesting every single match and checking it's average rank). I'm using STRATZ API filters for that, minimum match rank is set to 80 (immortal). In some cases uncalibrated players or those who got to play with nine immortal players in game may get through.

# Summary

* **Matches total:** 23130
* **Individual players spotted in matches:** 17289
* **Radiant winrate:** **52.76%** -- *Almost 3% lower than in 7.21d*
* **Median match duration:** 34:06 -- *It's not 40+ mins we used to have, but it's two minutes higher than in 7.21d which is a lot*
* **Median hero picks:** 1419
* **Median hero bans:** 238
* **Median hero GPM/XPM:** 425/492 -- *See the note below*
* **Total buybacks:** 84736

The reason why I'm leaving those median hero stats every time is it's good for understanding what are the average values and it's easier to compare heroes using those.  It also leads to some interesting insights.

Median GPM didn't really change that much comparing all the 7.21 patches and 7.22. Median XPM is a different beast: it was 492 in 7.21d (and somewhat like that before), but it's 543 in 7.22. That kind of shift is quite huge and it's most likely due to experience formula changes.

### Game Modes

Nothing to see here this time. 95% of full-immortal matches were played in All Draft. It's sad there weren't all-stars low priority shitshows this time.

Even Random Draft didn't show up. Oh yeah, about that...

### Regions

* **Europe West:** 10221
* **Southeast Asia:** 6177
* **US East:** 3871
* **Europe East:** 919
* **South America:** 614
* **Russia and CIS:** 607
* **Australia:** 500
* **China:** 190
* **Japan:** 25
* **US West:** 6

What happened to China? It used to be the top-3 played region with unique meta. It's disappearance is also the reason why there aren't much Random Draft matches.

I think it may be because of all the recent tournaments happening in Europe, so there are much less Immortal Rank players in China left and there aren't much "pure" immortal matches being played as a result.

# Records

This section of the post only includes global records. You can check region specific records by yourself on the website.

Some of those are affected by turbo matches as well, but I found it out too late, so I just marked them. Sorry for that.

| Record                      | Match                                               | Value   | Player                                                       | Hero              |
| --------------------------- | --------------------------------------------------- | ------- | ------------------------------------------------------------ | ----------------- |
| GPM                         | [4790001122](https://stratz.com/matches/4790001122) | 1,377   | [KEEN.Eleven](https://stratz.com/players/134276083)          | Alchemist         |
| XPM                         | [4799786906](https://stratz.com/matches/4799786906) | 1,198   | [snxc](https://stratz.com/players/385716998)                 | Io                |
| Kills                       | [4788434771](https://stratz.com/matches/4788434771) | 43      | [@23savage](https://stratz.com/players/355168766)            | Morphling         |
| Deaths                      | [4793297925](https://stratz.com/matches/4793297925) | 36      | [dx1](https://stratz.com/players/102027765)                  | Nature's Prophet  |
| Assists                     | [4811127004](https://stratz.com/matches/4811127004) | 50      | [Whitemon](https://stratz.com/players/186347237)             | Nyx Assassin      |
| KDA with 0 deaths           | [4812938214](https://stratz.com/matches/4812938214) | 51      | [Suampi](https://stratz.com/players/381657196)               | Pugna             |
| KDA with 1+ deaths          | [4806928239](https://stratz.com/matches/4806928239) | 51      | [Qupe](https://stratz.com/players/118078153)                 | Earthshaker       |
| Gold Earned                 | [4804219554](https://stratz.com/matches/4804219554) | 95,572  | [Tyx](https://stratz.com/players/116293223)                  | Alchemist         |
| Last hits                   | [4806204511](https://stratz.com/matches/4806204511) | 1,418   | [dead inside(pos1)](https://stratz.com/players/13959693)     | Anti-Mage         |
| Damage to heroes            | [4809130258](https://stratz.com/matches/4809130258) | 183,646 | [TGF-TP](https://stratz.com/players/229341885)               | Tinker            |
| Damage to buildings         | [4795588472](https://stratz.com/matches/4795588472) | 28,641  | [POS 1 TY](https://stratz.com/players/852059748)             | Juggernaut        |
| Hero healing                | [4787491961](https://stratz.com/matches/4787491961) | 60,537  | [Shachlo](https://stratz.com/players/123787524)              | Necrophos         |
| Damage taken from heroes    | [4789990223](https://stratz.com/matches/4789990223) | 250,914 | [Edgy Teen Enjoying Billie Eilish](https://stratz.com/players/138480840) | Meepo             |
| Efficiency on lane          | [4787989741](https://stratz.com/matches/4787989741) | 184%    | [Hisoka](https://stratz.com/players/172783009)               | Outworld Devourer |
| Observer wards placed       | [4809651952](https://stratz.com/matches/4809651952) | 40      | [Antares](https://stratz.com/players/147853595)              | Winter Wyvern     |
| Sentries placed             | [4809651952](https://stratz.com/matches/4809651952) | 79      | [Antares](https://stratz.com/players/147853595)              | Winter Wyvern     |
| Obs Wards destroyed         | [4787458560](https://stratz.com/matches/4787458560) | 16      | [Svek](https://stratz.com/players/403853220)                 | Shadow Shaman     |
| Map pings                   | [4803830927](https://stratz.com/matches/4803830927) | 3,435   | Strangely, it's not our most beloved guy, its someone [POS 1 NOTHING ELSE](https://stratz.com/players/113106253) | Lich              |
| Stuns                       | [4792473185](https://stratz.com/matches/4792473185) | 514.67  | [Daleee](https://stratz.com/players/294312037)               | Lion              |
| Couriers killed by a player | [4784429982](https://stratz.com/matches/4784429982) | 5       | [♫-DTS-Surrender-♫](https://stratz.com/players/121821768)    | Bounty Hunter     |

# Heroes

## Sorted by Rank

| HERO           | MATCHES | CONTEST RATE | RANK   | PICKED | WINRATE | BANNED | WINRATE |
| -------------- | ------- | ------------ | ------ | ------ | ------- | ------ | ------- |
| Sand King      | 8187    | 35.40%       | 100.00 | 6980   | 53.94%  | 1207   | 52.11%  |
| Luna           | 882     | 3.81%        | 99.15  | 852    | 58.69%  | 30     | 60.00%  |
| Io             | 5215    | 22.55%       | 98.29  | 2679   | 56.44%  | 2536   | 48.97%  |
| Spirit Breaker | 2198    | 9.50%        | 97.44  | 2038   | 55.35%  | 160    | 50.00%  |
| Nyx Assassin   | 4683    | 20.25%       | 96.58  | 3032   | 53.50%  | 1651   | 51.85%  |
| Monkey King    | 6972    | 30.14%       | 95.73  | 5369   | 51.80%  | 1603   | 50.41%  |
| Ember Spirit   | 6782    | 29.32%       | 94.87  | 5441   | 51.88%  | 1341   | 49.44%  |
| Meepo          | 3050    | 13.19%       | 94.02  | 1278   | 57.12%  | 1772   | 48.48%  |
| Shadow Shaman  | 4813    | 20.81%       | 93.16  | 4637   | 52.06%  | 176    | 49.43%  |
| Naga Siren     | 4346    | 18.79%       | 92.31  | 2337   | 52.72%  | 2009   | 50.67%  |

## Hero Combos (sorted by deviation)

| HEROES                       | MATCHES | WINRATE | WINRATE DIFFERENCE | EXPECTED MATCHES | DEVIATION | PERCENTAGE | SAME LANE RATE |
| ---------------------------- | ------- | ------- | ------------------ | ---------------- | --------- | ---------- | -------------- |
| Sand King + Leshrac          | 709     | 51.76%  | 0.06%              | 497              | 212       | 29.90%     | 68.97%         |
| Sand King + Lina             | 786     | 55.34%  | 3.35%              | 699              | 87        | 11.07%     | 38.93%         |
| Sand King + Templar Assassin | 580     | 60.00%  | 7.08%              | 510              | 70        | 12.07%     | 0.17%          |
| Juggernaut + Shadow Shaman   | 641     | 49.14%  | -1.44%             | 572              | 69        | 10.76%     | 47.74%         |
| Earthshaker + Morphling      | 696     | 47.27%  | -0.61%             | 636              | 60        | 8.62%      | 4.45%          |
| Sand King + Grimstroke       | 587     | 47.70%  | 0.77%              | 528              | 59        | 10.05%     | 41.91%         |

# Hero positions

## Most popular

### Core Safelane

* **Juggernaut:** 5411 (49.09% wr)
* **Lifestealer:** 3477 (51.54% wr)
* **Troll Warlord:** 3246 (48.43% wr)
* **Morphling:** 3210 (47.04% wr)
* **Sven:** 2753 (49.07% wr)

It's a relief to see much more viable and actually picked cores in 7.22. Altho the Jugg - Lifestealer - Troll trio is still dominating in the meta.

### Core Midlane

* **Ember Spirit:** 3876 (52.81% wr)
* **Templar Assassin:** 3295 (51.96% wr) -- interesting to see this huge rise in both popularity and winrate for TA considering all the changes
* **Storm Spirit:** 3236 (47.31% wr) -- ...why?
* **Lina:** 2734 (48.61% wr) -- Even tho it's 48%, it seems to be pretty good time to play Core Lina. Usually Lina had around 45% winrate
* **Outworld Devourer:** 2500 (49.28% wr)

### Core Offlane

* **Sand King:** 5798 (53.90% wr)
* **Mars:** 4343 (49.07% wr)
* **Pangolier:** 3026 (49.93% wr)
* **Doom:** 1758 (48.07% wr)
* **Legion Commander:** 1742 (52.18% wr)

### Support

* **Earthshaker:** 4711 (49.37% wr)
* **Shadow Shaman:** 4412 (52.33% wr)
* **Rubick:** 4206 (49.38% wr)
* **Lion:** 3943 (50.90% wr)
* **Warlock:** 3893 (50.99% wr)
* **Oracle:** 3753 (48.01% wr)
* **Grimstroke:** 3733 (48.92% wr)
* **Abaddon:** 2995 (51.05% wr)
* **Nyx Assassin:** 2722 (**54.45%** wr)
* **Winter Wyvern:** 2462 (51.18% wr)

Overall there aren't much standouts on any position. The distribution of heroes by popularity is way closer than before. And there aren't that much 55%+ or 45%- heroes among the most popular ones.

---

[Full report is available here](https://stats.spectral.gg/lrg2/?league=imm_ranked_722)

Thanks to [OpenDota](https://opendota.com/) and [STRATZ](https://stratz.com/) for providing awesome APIs to grab all juicy match analysis data and generate stats for all the matches.