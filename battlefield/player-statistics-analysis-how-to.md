# Player Statistics Analysis - How-to

In this thread I aim to list a few tips on what to look for when analyzing player statistics
I would also like to point out, and emphasize that player statistics is a somewhat blunt tool to pin-point cheaters. Some cheaters kill with med packs, and that will obviously not show up in the player statistics. Others have their aimbot set to a very discrete level, which enables them to cheat for a very long time before getting caught (if they ever get caught). My point is, even though it doesn't show in the player statistics, they might still be cheating.



To get a better overview compared to what Battlelog offers, I recommend using either a Cheat-o-meter.
* [FRStats](http://frstats.net/COM/C-O-M.php),
* [Battlelog browser plugin](http://getbblog.com)
* [BF3 Stats](http://bf3stats.com/)
* [BF4 Stats](http://bf4stats.com/)
* [BFH Stats](http://bfhstats.com/)

I prefer using *BBLog* and *BFstats*.

## The use of Cheat-o-Meters
While they provide results that are easy to read, you should never solely trust the result of such a tool. Instead a combination of the previously mentioned tools is preferred.  
First look at the *Score per minute* (**SPM**):  
If it's well over a thousand, you should definitely dig deeper (Even if it's lower, you should still dig deeper,   since the **SPM** depends on your gaming-style)  
Usually the overall accuracy isn't very important, so I will just skip that and move on to the weapon statistics

## Weapon statistics

### Headshot per kill (HK%)

This is usually the dead give away. Anything over **40%** **HK** for **Machine guns**, **Assault rifles** and **Sub-machineguns** is suspicious.  
What is important here is to remember to check how many they have killed with the weapon in question! **1 kill** and **100%** **HK** with **M416** is of course not the least suspicious. **1000 kills** and **85%** **HK** is definitely a cheater.  
Snipers are harder to pin-point using the **HK%**, but usually anything over **80%** is suspicious.

### Kills per minutes (KPM)

Anything over about **3,5 KPM** for primary weapons is suspicious (**Knife**, **pistols**, **RPG/SMAW**, **M26*** and **M320*** are usually not used as primary weapons..).  
Again, look at the amount of kills they have with the weapon in question!

***


###Example One

*Patrik4778178*  
When entering his Blog I find an avg. weapon accuracy of **12%** and a **SPM** of **743**, **K/D ratio** of **2.22**. Nothing suspicious there.

**Moving on to the weapon statistics:**  
**AS VAL** **87.32%** **HK** after **489** kills (**cheat**)  
**RPK-74M** **75.47%** **HK** after **375** kills (**cheat**)  
The pattern repeats itself with multiple weapon with extremely high **HK%**  

I note that his **kills/min** for those weapons aren't very good, but with the extremely high **HK%** we can still conclude that he is cheating.  
Further more, his overall **HK%** is also **75.33%** (this isn't a dead giveaway in itself, since he may enjoy sniping a lot).

***

###Example Two
The player *StarBenito* has an avg **accuracy** of **13.5%**,  **K/D** of **1.34** and **SPM** of **627**, i.e. nothing out of the ordinary.  
Digging deeper we find extreme **HK%** and **KPM** on some of his weapons, suggesting that he is cheating.  
Me and Trubb watched him kill 16 guys, all over the map in 30 seconds, and we could therefore ban him for cheating.


## Conclusion:  
Analyzing stats is a powerful tool in the hunt for cheaters (and stat-padders). You always have to consider several points before making a conclusion based on statistics.  There are more things to look at that than I have talked about in this thread, for example Nemesis kills, **Quit %** and so on. Player statistics is sometimes a time consuming thing to analyse, but it is worth it in the end! If you are uncertain about whether or not someone is cheating, bring it up with your fellow admins and I am sure that you will get a lot of feedback.

***

# Damage modifier

You basically look at **kills/hits**

For base values on damage for different weapons you can go to
* [symthic](http://symthic.com/bf4-weapon-info)
* [battlefield.wikia.com](http://battlefield.wikia.com/wiki/Category:Weapons_of_Battlefield_4)

Example:  
* Joel-Pan918
* http://bf4stats.com/pc/Joel-Pan918  

The first thing that sticks out is that the guy is obviously cheating with insane headshot per kill percentages (HK%). This guy is stupid and makes him easy to detect, but not all cheaters use aimbot. Therefore we to check if a suspicious player is using damage modifier.  

Knowing with which weapon to start might be tricky if you are not used to reading stats, but I usually just do some math in my head to know which weapon to analyze further.
Let's take a look at the **ACE-53 SV** in this case.

### Baseline stats for the **ACE-53 SV**
* [ACE_53_SV](http://symthic.com/bf4-weapon-info?w=ACE_53_SV)
MAX **DMG** **45** MIN **DMG** **38**
* His **DMG/SHOT** with the **ACE-53 SV**
* **192 kills/265 hits** = **72% DAMAGE/SHOT**.
* **He is cheating.**

The limitation is that if a guy already has a lot of kills and starts cheating after a lot of played hours, it won't be as obvious and as easy to detect. Then you will have to look into battlereports in bf4db (BL reports are not specified) to try and figure something out.
http://bf4db.com/players/1282482/battlereports

If you make an account on bf4db you can update the stats for the player you are interested in, and maybe save you some time compared to doing the analysis manually.


Other interesting sites worth mentioning:

* [BF4 DB](http://bf4db.com/) - Battlereports, statistics (not always updated) & Player Fairfight status (just reads it off Battlelog, not that useful)
* [Anticheatinc bf4](http://history.anticheatinc.com/bf4/index.php) - Account history BF4
* [Anticheatinc bf3](http://history.anticheatinc.com/bf3/index.php) - Account history BF3
* [GGC](http://www.ggc-stream.net/search/server/guid) - GGC database over Punkbuster bans
* [PB Bans](http://www.pbbans.com/mbi-search.html) - PBBans database over Punkbuster bans
* [PB Screens](http://pbscreens.com/) - Punkbuster screenshots on a selection of servers. You can search for player GUID or nick


Sites to stay away from
[Metabans](http://metabans.com/) - It can be used to get old nicknames if you don't want to use bf4db or account history, but never ban someone just because they have a metaban!! A madmin can ban someone for "cheating" on all servers that run metabans, without a shred of evidence!  I've been there myself :(
