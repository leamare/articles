Published: 

---

# 7.22f Immortal Meta Trends

Just while everybody thought 7.22e is going to be the TI patch, Valve released another minor gameplay update labeled as 7.22f. The update didn't introduce a lot of significant changes and most of the trends are carryovers from the previous update. However there are still some interesting things waiting for them to be found.

This report is based on data collected during the first week of patch 7.22f (27th of July - 3rd of August). Data includes not only ranked matches, but stats of all matches with average rank equal to Immortal. Excluded matches are the ones that have abandons, ended in less than 10 minutes or had an insignificantly low score.

[The full and regularly-updated version of the report is available at Spectral.gg](https://stats.spectral.gg/lrg2/?league=imm_ranked_722f). You can find detailed data about Hero-vs-Hero performance, draft stages priorities, pairs and trios, positions stats and dire/radiant winrates, Meta Graph and region-specific data here.

## FAQ

* **Why REGION NAME has low number of matches?** It’s common for higher ranks to queue on closest popular region. I.e. EUW for RU players, USE for USW.
* **Where did you get data?** I've got match IDs manually extracted from leaderboards players' recent matches using STRATZ API. Then I fetch match data using OpenDota API.
* **Why there are only random draft matches played in China?** Chinese players just love playing Random Draft.
* **What is Hero Pairs Divergence?** It's the difference between expected pair's matches and real match number. Usually this difference is higher for better hero combos.
* **What is Hero Rank?** Think of it as of smart winrate sort. It considers popularity and winrate of heroes.
* **Is it strictly Immortal Rank?** Almost. I'm not checking all the matches by myself (it would take too much time, requesting every single match and checking it's average rank). I'm using STRATZ API filters for that, minimum match rank is set to 80 (immortal). In some cases uncalibrated players or those who got to play with nine immortal players in game may get through.

## Summary

* **Matches total:** 34,345
* **Individual players spotted in matches:** 34155 – The number includes Immortal players who lost their leaderboards rank
* **Radiant winrate:** 53.73%
* **Median match duration:** 34:57
* **Median hero picks:** 2,424
* **Median hero bans:** 323
* **Median hero GPM/XPM:** 429/552
* **Total observer wards placed:** 1,059,385

I'm leaving these median hero stats because it's good to understand the average values and comparing heroes is much easier using these numbers. It also leads to some interesting insights.

It's not surprising to see values to remain almost the same as in 7.22e report. However median picks and bans values are a bit larger than before which may be related to players (especially TI attendees) trying out new things before TI takes off.

### Game Modes

* **Ranked All Pick:** 25,854
* **Random Draft:** 7,706
* **Captains Mode:** 559
* **Single Draft:** 221
* **All Pick:** 5

### Regions

* **Europe West:** 10,536
* **China:** 7,871
* **Southeast Asia:** 7,609
* **US East:** 3,681
* **Europe East:** 1,530
* **Russia and CIS:** 1,452
* **South America:** 752
* **Australia:** 559
* **Japan:** 180
* **Peru:** 91
* **US West:** 81
* **India:** 3

## Heroes

The highest ranked heroes list didn’t change too much after the update. Enchantress, Faceless Void and Naga Siren continue to dominate in pubs and most picked list remained almost the same with only Ember Spirit going down from the second to the fifth place. 

But it’s not a Dota patch if there are no surprises and that’s where smart heroes ranking gets really useful. Spirit Breaker and, surprisingly, Slark got out of the top 10 ranked heroes list (while Slark still being the most picked hero and Spirit Breaker still being relatively popular). Crystal Maiden and Bane disappeared as well, but it’s interesting to see who got their places instead.

![1565116668060](F:\code\articles\dota_articles\7.22f trends\assets\1565116668060.png)

First of all, there’s Chen (1324 matches and 56.12% winrate). The hero isn’t really surprising to see being both popular and successful before The International since the hero was already pretty contested during all TIs and now he acts like a replacement for Io most of the time. Another interesting hero to note is Treant Protector (3500 matches, 53.34%) who is similar to Spirit Breaker in many ways, but gets a bit different niche being better at applying lane pressure. It’s also not surprising to see the rise of Sand King again: the hero is very versatile in what he can do, he’s hard to pressure and he is safe to pick at the tournament. But there’s another one hero who traditionally gets buffed before TI and is most likely to be picked here – Alchemist.

Every time the hero gets new buffs after being significantly nerfed, players find a new playstyle: Battle Fury Alchemist, Radiance “Naga” Alchemist, Aggressive Solar Crest Alchemist, Stunlock Alchemist with Unstable Concoction talents… This time is no exception and the new playstyle got “invented” right before TI patch. This time, after getting two early Bracers and Phase Boots, it’s pretty common to get Radiance into Assault Cuirass and Eye of Skadi. It’s not a problem for Alchemist to get these items relatively early and all of them make it very hard to fight against not only the hero, but his team as well. Alchemist of the 7.22f is a mix of both “safely farming for my team” and “aggressively stomping opponent with advantage” playstyles that were popular in previous patches.

### Hero positions

There were no significant positions changes after the update. This time Juggernaut was replaced as a go-to carry by Slark, Faceless Void finally got into the top-5 carry list. Middle lane cores didn’t change at all, aside from Ember Spirit’s declining popularity. Pudge is still rising and is still picked as core on any lane.

One interesting and new trend is support Invoker (or “Shota Invoker”). This playstyle started with a test by the player 2B who is famous for playing core heroes as supports. However, this time it turned out to be not a niche thing, but an interesting trend that quickly started spreading on Immortal rank. Right now it’s not rare to see position 5 or 4 support Invoker and even players like SoNNeikO and YapzOr are playing the hero. What’s interesting is the hero also has a higher winrate as support – 51.92% in 780 matches against 50.24% in 4015 of Midlane Core Invoker.

#### Core Safelane

* **Slark:** 8,867 (49.25% wr)
* **Juggernaut:** 7,493 (46.68% wr)
* **Lifestealer:** 4,767 (50.07% wr)
* **Wraith King:** 4,186 (52.44% wr)
* **Faceless Void:** 3,249 (54.91% wr)

#### Core Midlane

* **Ember Spirit:** 5,589 (49.74% wr)
* **Outworld Devourer:** 5,464 (48.06% wr)
* **Storm Spirit:** 4,191 (47.82% wr)
* **Invoker:** 4,015 (50.24% wr)
* **Queen of Pain:** 2,999 (50.78% wr)

#### Core Offlane

* **Sand King:** 4,616 (52.90% wr)
* **Mars:** 4,244 (48.04% wr)
* **Pangolier:** 4,854 (48.56% wr)
* **Legion Commander:** 3,532 (49.41% wr)
* **Pudge:** 3,435 (52.52% wr)

#### Support

* **Rubick:** 7,172 (48.23% wr)
* **Spirit Breaker:** 5,987 (51.46% wr)
* **Lion:** 5,874 (49.68% wr)
* **Grimstroke:** 5,537 (46.36% wr)
* **Shadow Shaman:** 5,263 (51.76% wr)
* **Crystal Maiden:** 4,897 (52.11% wr)
* **Warlock:** 4,366 (52.06% wr)
* **Earthshaker:** 4,310 (50.44% wr)
* **Pudge:** 3,840 (46.35% wr)
* **Jakiro:** 3,495 (51.59% wr)

## Legends of 7.22e

Concluding the 7.22f patch first week review, I’d like to close the book on 7.22e with some interesting global records noticed.

* **Highest GPM:** 1,565 by muted pos 2 as Alchemist in a match [4924915864](https://dotabuff.com/matches/4924915864)
* **Highest XPM:** 1,320 by Marley as Broodmother in a match [4904829684](https://dotabuff.com/matches/4904829684)
* **Most kills:** 47 by A Cruel Angel's Thesis as Ursa in a match [4919335475](https://dotabuff.com/matches/4919335475)
* **Most deaths:** 51 by Crippling depression as Enchantress in a match [4922719395](https://dotabuff.com/matches/4922719395)
* **Most assists:** 58 by cheerego as Spirit Breaker in a match [4927955694](https://dotabuff.com/matches/4927955694)
* **Highest KDA with 0 deaths:** 54 by Pegasus as Ember Spirit in a match [4918528926](https://dotabuff.com/matches/4918528926)
* **Highest KDA with 1+ deaths:** 63 by Edge of Revolution as Zeus in a match [4907507878](https://dotabuff.com/matches/4907507878)
* **Total Gold Earned:** 103,295 by ROCK as Kunkka in a match [4928097477](https://dotabuff.com/matches/4928097477)
* **Last Hits:** 1,794 by berlin as Medusa in a match [4928934408](https://dotabuff.com/matches/4928934408)
* **Damage to Heroes:** 271,001 by Kirikage as Zeus in a match [4926915400](https://dotabuff.com/matches/4926915400)
* **Damage to Buildings:** 30,739 by @zamez as Lone Druid in a match [4921267276](https://dotabuff.com/matches/4921267276)
* **Hero healing:** 68,935 by Tetsu as Dazzle in a match [4927558211](https://dotabuff.com/matches/4927558211)
* **Damage taken from heroes:** 236,711 by new life. as Meepo in a match [4910769206](https://dotabuff.com/matches/4910769206)
* **Observer wards placed:** 50 by TalRasha as Witch Doctor in a match [4926915400](https://dotabuff.com/matches/4926915400)
* **Sentries placed:** 98 by TalRasha as Witch Doctor in a match [4926915400](https://dotabuff.com/matches/4926915400)
* **Observer wards destroyed:** 21 by wagatecha as Warlock in a match [4905326076](https://dotabuff.com/matches/4905326076)
* **Map pings:** 4,149 by 低调 隐忍 杀戮 as Phoenix in a match [4917282390](https://dotabuff.com/matches/4917282390)
* **Stuns:** 657.17 by cypr1an as Underlord in a match [4905906550](https://dotabuff.com/matches/4905906550)
* **Most courier kills by a player:** 6 by 陌生的队友我爱你们 as Bounty Hunter in a match [4910640705](https://dotabuff.com/matches/4910640705)
* **Biggest networth stomp by a team** (63,527) in a match [4910924118](https://dotabuff.com/matches/4910924118) 
* **Biggest networth comeback by a team** (55,907) in a match [4928099125](https://dotabuff.com/matches/4928099125)
* **Most Roshan kills in a match** (9) in a match [4926915400](https://dotabuff.com/matches/4926915400)
* **Longest match** (1:56:31) was [4926915400](https://dotabuff.com/matches/4926915400)
* **Bloodbath with most kills combined** (171) was [4928097477](https://dotabuff.com/matches/4928097477)

Complete report for the patch 7.22d is [available at Spectral.gg](https://stats.spectral.gg/lrg2/?league=imm_ranked_722e&mod=records) as well.
