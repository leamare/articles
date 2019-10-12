Published: 

---

# 7.22g Immortal Meta Trends

Two weeks have passed since The International 2019 ended and one week since release of the newest gameplay patch. The patch introduced some minor changes before the upcoming Outlanders update, and we already have some data to look at.

This report is based on data collected during the first week of patch 7.22g (4th of September - 10th of September). Data includes not only ranked matches, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that have abandons, ended in less than 10 minutes or had an insignificantly low score.

[The full and regularly-updated version of the report is available at Spectral.gg](https://stats.spectral.gg/lrg2/?league=imm_ranked_722g). You can find detailed data about Hero-vs-Hero performance, draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region-specific data here.

## FAQ

* **Why REGION NAME has low number of matches?** It’s common for higher ranks to queue on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using OpenDota API.
* **Why there are only random draft matches played in China?** Chinese players just love playing Random Draft.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** Think of it as of smart winrate sort. It considers popularity and winrate of heroes.
* **Is it strictly Immortal Rank?** Almost. I'm not checking all the matches by myself (it would take too much time, requesting every single match and checking it's average rank). I'm using STRATZ API filters for that, minimum match rank is set to 80 (immortal). In some cases uncalibrated players or those who got to play with nine immortal players in game may get through.

## Summary

* **Matches total:** 23,683
* **Individual players spotted in matches:** 35,653 – The number includes Immortal players who lost their leaderboards rank
* **Radiant winrate:** 53.26%
* **Median match duration:** 35:21
* **Median hero picks:** 1,462
* **Median hero bans:** 164
* **Median hero GPM/XPM:** 424/548
* **Total observer wards destroyed:** 221,011

### Game Modes

* **Ranked All Pick:** 17,760
* **Random Draft:** 5,159
* **Captains Mode:** 511
* **Single Draft:** 230
* **Captain’s Draft:** 23

### Regions

* **Europe West:** 7,028
* **China:** 5,308
* **Southeast Asia:** 4,844
* **US East:** 2,762
* **Russia and CIS:** 1,996
* **Europe East:** 836
* **South America:** 435
* **Australia:** 239
* **Japan:** 106
* **Peru:** 67
* **US West:** 53
* **India:** 5
* **Chile:** 4

## Heroes

Alchemist, the terror of the pubs, was nerfed in the patch and lost a lot in terms of winrate. But, surprisingly, this still wasn’t enough to completely shut the hero down, moving him more into “solid pick” category. Same goes for another strong hero of 7.22f – Enchantress. Changes to Nature’s Attendants made it possible to actually shut down Enchantress in some cases, which made the hero more situational than before, but didn’t kill her completely. Even Tiny, who’s nerfs can be classified as insignificant, dropped a lot and, while remaining a most picked hero, doesn’t seem as scary anymore.

However, there are two other heroes on the rise that weren’t properly addressed in the patch, while being strong and contested in 7.22f meta and during TI9 – Mirana and Faceless Void. Both of those heroes are in the top 10 ranked list now. While Faceless Void has 53% winrate and is the most popular safelane core hero, Mirana looks insanely good. The hero is not only the most contested right now, but also has 56.7% winrate which was previously seen only for the situational “cheese” heroes with low pick rates.

Invoker, while not being as popular, looks just as scary. I already noted a rise of the Support Invoker in 7.22d, 7.22f and TI9 articles, and this trend is still rising. The hero is far from being one of the most contested, but still placed the second in hero ranking. The reason for that is relatively high pick rate and, what’s more important, winrate of Support Invoker: the hero has 2555 matches as Midlane Core with 52.88% winrate and 1249 matches as Support with overwhelming 57.17% winrate. It seems like this trend may be rising even more in foreseeable future.

The last hero worth noting is probably Night Stalker. The hero was buffed in the latest patch and instantly became a pub star, getting to 58% winrate during the first two days. And even now the hero has what can be called tier 3 pick rate and winrate of 55%. On of the most interesting new trends seems to be picking Night Stalker as a core hero for any lane and rushing Aghanim’s Scepter. The Void upgrade with Scepter not only makes farming much easier for Night Stalker, but also provides a 0.6 stun and effectively increases range of the spell almost two times (from 525 range to 900 AoE).

![1565116668060](assets\heroes.png)

### Hero positions

In terms of hero positions there’s nothing new to talk about. It’s still surprising to see Alchemist being picked as Safelane Core and being relatively successful. Faceless Void, on the other hand, have risen even more and bacame the top-1 carry hero.

It’s interesting to see almost full change of the popular support heroes change with only Rubick, Crystal Maiden and Jakiro remaining in the top-10 list. One interesting trend to note is position 4 Lina who is not only much more successful than Midlane Core Lina (50.15% winrate as Support and 46.06% as Midlane Core).

List of the most popular Offlane Cores also received a huge update and replacing dominating Pudge, Mars and Pangolier with the recent TI9 trends: Sand King, Tiny, Axe, Enchantress.

#### Core Safelane

* **Faceless Void:** 4,796 (53.27% wr)
* **Slark:** 4,713 (48.40% wr)
* **Lifestealer:** 4,418 (48.94% wr)
* **Juggernaut:** 3,236 (49.10% wr)
* **Alchemist:** 3,004 (53.06% wr)

#### Core Midlane

* **Outworld Devourer:** 3,740 (47.65% wr)
* **Ember Spirit:** 3,177 (49.92% wr)
* **Kunkka:** 2,856 (51.72% wr)
* **Invoker:** 2,555 (52.88% wr)
* **Storm Spirit:** 2,200 (48.55% wr)

#### Core Offlane

* **Sand King:** 2,894 (**55.11%** wr)
* **Night Stalker:** 2,793 (**55.50%** wr)
* **Tiny:** 2,609 (**42.55%** wr)
* **Enchantress:** 2,556 (49.92% wr)
* **Axe:** 2,335 (51.43% wr)

#### Support

* **Mirana:** 5,805 (**58.40%** wr)
* **Rubick:** 4,639 (47.45% wr)
* **Shadow Demon:** 4,437 (48.97% wr)
* **Ogre Magi:** 4,107 (51.64% wr)
* **Crystal Maiden:** 3,595 (51.10% wr)
* **Tiny:** 3,445 (47.20% wr)
* **Lion:** 3,330 (49.19% wr)
* **Ancient Apparition:** 2,877 (48.77% wr)
* **Jakiro:** 2,749 (49.98% wr)
* **Lina:** 2,590 (50.15% wr)

## Legends of 7.22f

Following the tradition, let's close the trends discussion with the overview of the 7.22f records.

* **Highest GPM:** 1,603 by Carry the future as Alchemist in a match [5007558826](https://dotabuff.com/matches/5007558826)
* **Highest XPM:** 1,387 by < blank > as Broodmother in a match [5007050548](https://dotabuff.com/matches/5007050548)
* **Most kills:** 47 by AtX- as Phantom Assassin in a match [4942309750](https://dotabuff.com/matches/4942309750)
* **Most deaths:** 42 by dabdabs- as Lion in a match [4941817923](https://dotabuff.com/matches/4941817923)
* **Most assists:** 64 by imprømax as Zeus in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Highest KDA with 0 deaths:** 57 by rist0 as Grimstroke in a match [4956716923](https://dotabuff.com/matches/4956716923)
* **Highest KDA with 1+ deaths:** 59 by Persimmon as Ember Spirit in a match [4961278414](https://dotabuff.com/matches/4961278414)
* **Total Gold Earned:** 139,689 by imprømax as Zeus in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Last Hits:** 1,794 by berlin as Medusa in a match [4928934408](https://dotabuff.com/matches/4928934408)
* **Damage to Heroes:** 322,391 by imprømax as Zeus in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Damage to Buildings:** 30,802 by xNaowa as Bounty Hunter in a match [4930980413](https://dotabuff.com/matches/4930980413)
* **Hero healing:** 80,044 by tups as Io in a match [5002268701](https://dotabuff.com/matches/5002268701)
* **Damage taken from heroes:** 259,745 by Mad world as Meepo in a match [4969117428](https://dotabuff.com/matches/4969117428)
* **Observer wards placed:** 62 by bamboo as Lion in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Sentries placed:** 103 by Slowby as Jakiro in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Observer wards destroyed:** 21 by Get higher! as Shadow Demon in a match [5006926094](https://dotabuff.com/matches/5006926094)
* **Map pings:** 3,872 by Fat Paper Stacks as Tusk in a match [4984882601](https://dotabuff.com/matches/4984882601)
* **Stuns:** 658.01 by ;(from dag) as Nyx Assassin in a match [4953647291](https://dotabuff.com/matches/4953647291)
* **Most courier kills by a player:** 6 by RolyPoly as Bounty Hunter in a match [4947761212](https://dotabuff.com/matches/4947761212)
* **Biggest networth stomp by a team** (74,720) in a match [5001694544](https://dotabuff.com/matches/5001694544) 
* **Biggest networth comeback by a team** (65,491) in a match [4950026787](https://dotabuff.com/matches/4950026787)
* **Most Roshan kills in a match** (11) in a match [4963590618](https://dotabuff.com/matches/4963590618)
* **Longest match** (2:32:31) was [4963590618](https://dotabuff.com/matches/4963590618)
* **Bloodbath with most kills combined** (182) was [4970149538](https://dotabuff.com/matches/4970149538)

Complete report for the patch 7.22f is [available at Spectral.gg](https://stats.spectral.gg/lrg2/?league=imm_ranked_722f) as well.
