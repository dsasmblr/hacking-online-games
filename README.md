<div align="center">
  <a href="https://guidedhacking.com/?utm_source=dsasmblr">
    <img src="https://raw.githubusercontent.com/dsasmblr/hacking-online-games/master/resources/guidedhacking-hero.png" />
  </a>
  <br>
  <span align="center"><a href="https://guidedhacking.com/?utm_source=dsasmblr">This repo is sponsored by GuidedHacking.com!</a></span>
</div>

# [The Ultimate Online Game Hacking Resource](https://github.com/dsasmblr/hacking-online-games/)
**A curated list of tutorials/resources for hacking online games!**

From dissecting game clients to cracking network packet encryption, this is a go-to reference for those interested in the topic of hacking online games. I'll be updating this list whenever I run across excellent resources, so be sure to Watch/Star it! If you know of an excellent resource that isn't yet on the list, feel free to submit it for consideration via creating an issue or pull request for this repository, or [email it to me](mailto:dsasmblr@gmail.com).

### General Information

Title/Link | Description
---- | ----
[EFF FAQ on Reverse Engineering Legalities](https://www.eff.org/issues/coders/reverse-engineering-faq) | This FAQ details information that may help reverse engineers reduce their legal risk. *Use this information as a guide, not actual legal advice.*
[Cheating in Online Games: Overview of Approaches and Consequences](https://en.wikipedia.org/wiki/Cheating_in_online_games) | This Wikipedia page offers a good 10,000-foot view of the landscape of hacking online games.

### Blog Posts, Articles, and Presentations

Title/Link | Description
---- | ----
[Hack.lu 2017: (Workshop) Reverse Engineering a MMORPG](https://www.slideshare.net/AntoninBeaujeant/reverse-engineering-a-mmorpg) | This workshop covers the basics of reverse engineering a (M)MORPG. The target is [Pwn Adventure 3](http://www.pwnadventure.com/), an intentionally-vulnerable MMORPG developed by [Vector35](https://vector35.com/).
[Hack the Vote 2016 CTF "The Wall" Solution](https://zerosum0x0.blogspot.com/2016/11/hack-vote-wall-solution.html) | A write-up for a 2016 CTF challenge involving the multiplayer, open source Minecraft clone, Minetest.
[Reverse Engineering Online Games - Dragomon Hunter](http://0xbaadf00dsec.blogspot.com/2016/01/reverse-engineering-online-games.html) | An in-depth tutorial showing how to reverse engineer online games via the game *Dragomon Hunter*.
[Hacking/Exploiting/Cheating in Online Games (PDF)](https://zdresearch.com/wp-content/uploads/2013/04/Exploiting-Online-Games.pdf) | A presentation from 2013 that delves deeply into hacking online games, from defining terminology to providing code examples of specific hacks.
[Hacking Online Games](https://www2.cs.arizona.edu/~collberg/Teaching/466-566/2012/Resources/presentations/2012/topic4-final/slides.pdf) | A presentation from 2012 discussing various aspects of hacking online games.
[For 20 Years, This Man Has Survived Entirely by Hacking Online Games](https://motherboard.vice.com/en_us/article/59p7qd/this-man-has-survived-by-hacking-mmo-online-games) | A hacker says he turned finding and exploiting flaws in popular MMO video games into a lucrative, full-time, job.
[Hackers in Multiplayer Games](https://www.reddit.com/r/gamedev/comments/3ykg77/hackers_in_multiplayer_games/?st=j6p8fdyy&sh=61b63df4) | A Reddit post discussing hacking in multiplayer games.
[Reverse Engineering Network Protocols](https://www.reddit.com/r/ReverseEngineering/comments/yru6p/reverse_engineering_network_protocols/c5yijpt/?st=j6p93sze&sh=c88f98eb) | A very helpful comment from a Reddit post inquiring about reversing network protocols.
[Deciphering MMORPG Protocol Encoding](https://stackoverflow.com/questions/539812/deciphering-mmorpg-protocol-encoding) | An informative discussion from a question on Stack Overflow.
[Reverse Engineering of a Packet Encryption Function of a Game](https://reverseengineering.stackexchange.com/questions/8816/reverse-engineering-of-a-packet-encryption-function-of-a-game) | An informative discussion from a question on StackExchange.
[Fuzzing Online Games](https://www.elie.net/static/files/fuzzing-online-games/fuzzing-online-games-slides.pdf) | This is the slide deck used for the DEFCON 20 talk linked in the videos section below. [Click here](https://www.elie.net/talk/fuzzing-online-games) for the main presentation page.
[Kartograph (Game Hacking Tool)](https://www.elie.net/static/files/kartograph/kartograph-slides.pdf) | This is the slide deck used for the DEFCON 18 talk linked in the videos section below. [Click here](https://www.elie.net/talk/kartograph) for the main presentation page, and [click here](https://www.elie.net/static/files/openconflict-preventing-real-time-map-hacks-in-online-games/openconflict-preventing-real-time-map-hacks-in-online-games-slides.pdf) for an extended version of this slide deck [[Back-up Link](http://crypto.stanford.edu/~dabo/pubs/papers/onlinegames.pdf)].
[Adding Multiplayer Functionality to Torchlight (A Single-Player, Closed-Source Game)](https://github.com/dsasmblr/hacking-online-games/blob/master/resources/Extending_a_Closed_-_Source_Game_with_Multiplayer.pdf) | Torchlight is chosen as a real-world target application for adding multiplayer functionality to the otherwise single-player, closed-source game.
[Exploiting Game Engines for Fun and Profit](http://revuln.com/files/Ferrante_Auriemma_Exploiting_Game_Engines.pdf) | This slide deck shows you methods to exploit game engines, effictively discovering attack vectors that will work across multiple games using the same engine.
[How to Hack an MMO](https://www.raphkoster.com/2008/04/17/how-to-hack-an-mmo/) | This is an old article, but a good cursory overview of some of what's involved in attacking an MMO game client.
[Introduction to Server Side Emulation](https://github.com/dsasmblr/hacking-online-games/blob/master/resources/Introduction%20to%20Server%20Side%20Emulation.pdf) | An old but still relevant document for those interested in building their own emulated server (useful for things like reintroducing multiplayer functionality into a dead game).
[Reversing Path of Exile's Protocol](https://www.reddit.com/r/REGames/comments/8j8fc2/reversing_path_of_exiles_protocol/) | A three-part series of blog posts detailing one individual's approach to reverse engineering Path of Exile's network protocol).

### Videos

Title/Link | Description
---- | ----
[How to Hack Local Values in Browser-Based Games with Cheat Engine](https://www.youtube.com/watch?v=f_axmYpG1Lk) | This video teaches you how to find and change local values (which might appear as server-based values) in browser-based games.
[Reverse-Engineering a Proprietary Game Server with Erlang](https://www.youtube.com/watch?v=DumXgoFrMdU) | This talk details advantages Erlang has over other languages for reverse engineering protocols and analyzing client files. A live demo showcasing some of these tools and techniques is also given.
[DEF CON 16: Gaming - The Next Overlooked Security Hole](https://www.youtube.com/watch?v=pqWmFkMFzaU) | This talk discusses the growing number of attack vectors presenting themselves in the form of games, from engines to mods to middleware and more.
[DEF CON 17: Fragging Game Servers](https://www.youtube.com/watch?v=bRM4J-LphUw) | From hardware interaction to network protocols, this talk presents the inner workings of the Source Dedicated Server (used for games like *Left 4 Dead* and *Team Fortress 2*). Also discussed are some of the weaknesses in these game engines, as well as ways they're exploited in the wild.
[DEF CON 17: Subverting the World Of Warcraft API](https://www.youtube.com/watch?v=EnmoI2dRwX4) | This talk discusses MMO hacks related to the World of Warcraft API.
[DEF CON 18: Securing MMOs - A Security Professional's View from the Inside](https://www.youtube.com/watch?v=9IGvIexJSFU) | Gold farmers. Cheaters. Beleaguered programmers. All ingredients in a recipe for an unstable, fun-sapping game. This talk takes a look at the security problems plaguing the MMO industry and how modern engineers are taking the fight to cheaters and hackers in MMOs.
[DEF CON 18: Kartograph - Applying Reverse Engineering Techniques to Map Hacking](https://www.youtube.com/watch?v=WDNY4DMx8Jc) | Using games like Civilization IV, Age of Empires III, and Anno as targets, this talk teaches memory forensic techniques you can use to hack online games. Be sure to watch the accompanying [Kartograph demo video](https://www.youtube.com/watch?v=mFprkIAeKgM).
[DEF CON 19: Hacking MMORPGs for Fun and Mostly Profit](https://www.youtube.com/watch?v=hABj_mrP-no) | This talk presents a pragmatic view of both threats and defenses in relation to hacking online games.
[DEF CON 20: Fuzzing Online Games](https://www.youtube.com/watch?v=r0UQ6bpKOX0) | This talk discusses interesting techniques you can consider using to fuzz online games.
[DEF CON 23: Shall We Play A Game](https://www.youtube.com/watch?v=XxyRDkmNMHg) | This talk shows how playing on custom game servers and community-created maps could easily lead to exploitive code execution on our machines that bypass mitigation techniques. Targets include CryEngine 3, Dota 2, Garry's Mod, ARMA3 and Digital Combat Simulator.
[DEF CON 25 - Twenty Years of MMORPG Hacking: Better Graphics, Same Exploits](https://media.defcon.org/DEF%20CON%2025/DEF%20CON%2025%20video%20and%20slides/DEF%20CON%2025%20-%20Manfred%20-%20Twenty%20Years%20of%20MMORPG%20Hacking-%20Better%20Graphics%20and%20Same%20Exploits.mp4) | This presentation, presented by Manfred, technically analyzes some of the virtual economy-devastating, low-hanging-fruit exploits that are common in nearly every MMORPG released to date.
[Motherboard Livestream Archive: Researcher Cracks Elder Scrolls Online, Dark Age of Camelot, and Wildstar](https://www.youtube.com/watch?v=iYTCBPUn98c) | Adrian Bednarek, better known as "Manfred", demonstrates the MMORPG hacks he wanted to show but couldn't during his DEF CON 25 presentation. This is a rare glimpse into the tools, thoughts, and approaches of a professional online game hacker!
[Black Hat Europe 2014 - Next Level Cheating and Leveling Up Mitigations](https://www.youtube.com/watch?v=bsYxcpz3w8A) | This presentation outlines two practical attacks against one of the most popular anti-cheat engines and demonstrates the implications of a successful attack against anti-cheat software.
[Cyber Necromancy - Reverse Engineering Dead Protocols](https://media.ccc.de/v/31c3_-_5956_-_en_-_saal_2_-_201412281400_-_cyber_necromancy_-_joseph_tartaro_-_matthew_halchyshak) | This presentation talks about bringing a multiplayer game whose servers have shut down, back to life. The game is Metal Gear Online on the PS2 and PS3.
[32C3 - How Hackers Grind an MMORPG: By Taking it Apart!](https://www.youtube.com/watch?v=9pCb0vIp_kg) | In this presentation, Runes of Magic, a long-dead MMORPG, is used to demonstrate how to reverse engineer network protocols.
[ARMA 3 - Reverse Engineering on IDA Pro & Reclass 2015](https://www.youtube.com/watch?v=dIBdJUaOuWE) | A 45-minute tutorial demonstrating how to hack ARMA 3 using IDA Pro and ReClass.
[Let's Play/Hack - Pwn Adventure 3: Pwnie Island](https://www.youtube.com/watch?v=RDZnlcnmPUA&list=PLhixgUqwRTjzzBeFSHXrw9DnQtssdAwgG) | A video series of 21 parts on hacking the intentionally vulnerable MMORPG [Pwn Adventure 3](http://www.pwnadventure.com/).

### Podcasts/Audio

Title/Link | Description
---- | ----
[Darknet Diaries Ep. 7: Manfred Part 1: Hacking Online Video Games for Fun](https://darknetdiaries.com/episode/7/) | "Manfred" has privately been hacking online games for the past 20 years. In this episode, he tells stories of some of the unbelievable ways he's hacked games--all in the name of fun.
[Darknet Diaries Ep. 8: Manfred Part 2: Hacking Online Video Games for Profit](https://darknetdiaries.com/episode/8/) | "Manfred" found a way to turn his passion for video games and reverse engineering into a full time business. He exploited video games and sold virtual goods and currency for real money. This was his full time job. In this episode, he explains exactly how he did this.

### Books

Title/Link | Description
---- | ----
[Game Hacking](https://www.nostarch.com/gamehacking) | *Game Hacking* shows programmers how to dissect computer games and create bots.
[Attacking Network Protocols](https://www.nostarch.com/networkprotocols) | *Attacking Network Protocols* is a deep-dive into network vulnerability discovery.
[Practical Packet Analysis, 3rd Edition](https://www.nostarch.com/packetanalysis3) | *Practical Packet Analysis, 3rd Ed.* teaches you how to use Wireshark for packet capture and analysis.
[Exploiting Online Games: Cheating Massively Distributed Systems](https://www.amazon.com/Exploiting-Online-Games-Massively-Distributed/dp/0132271915/) | This book takes a close look at security problems associated with advanced, massively distributed software in relation to video games.

### Online Game Hacking Forums

Title/Link | Description
---- | ----
[Guided Hacking](https://guidedhacking.com/) | Discussion of multiplayer and single-player game hacks and cheats.
[UnKnoWnCheaTs Forum](https://unknowncheats.me/) | Discussion of multiplayer game hacks and cheats.
[MPGH (Multi-Player Game Hacking) Forum](http://www.mpgh.net) | Discussion of multiplayer game hacks and cheats.
[ElitePVPers](https://www.elitepvpers.com/) | Discussion of MMO hacks, bots, cheats, guides and more.
[OwnedCore](http://www.ownedcore.com/) | An MMO gaming community for guides, exploits, trading, hacks, model editing, emulation servers, programs, bots and more.

### Open Source and Safe-to-Hack Multiplayer Games

Title/Link | Description
---- | ----
[Pwn Adventure 2](http://ghostintheshellcode.com/#pwnadventure2) | A custom 3D MMOFPS based on the Unity game engine. The game includes several quests that are only solvable by modifying the game client.
[Pwn Adventure 3: Pwnie Island](http://pwnadventure.com/) | A first-person, open-world MMORPG developed specifically to be hacked! You might also be interested in [Pwn Adventure 2](http://ghostintheshellcode.com/#pwnadventure2), which is Unity-based.
[Minetest](http://www.minetest.net/) | An open source, multiplayer voxel-based game and game engine. (A Minecraft clone, basically.)
[Xonotic](http://www.xonotic.org/) | An open source, arena-style multiplayer FPS.
[Nexuiz](http://www.alientrap.com/games/nexuiz/) | The open source, multiplayer FPS game Xonotic is based on.
[AssaultCube](https://assault.cubers.net/) | An open source, multiplayer, FPS.
[List of Open Source Games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) | A large list on Wikipedia of open source games, both single-player and multiplayer.
