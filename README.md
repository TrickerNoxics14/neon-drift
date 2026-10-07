# Project-ND

A roguelite neon shooter — solo, local co-op for up to 4 on one keyboard, or online co-op for up to 16 friends.

**▶ Play: https://trickernoxics14.github.io/neon-drift/**

## Playing online with friends

1. Everyone opens the link above.
2. One player clicks **ONLINE CO-OP → HOST A PRIVATE GAME** and shares the 4-digit room code with their friends.
3. Friends click **JOIN WITH A CODE** and type it. Sharing a computer? Set **PLAYERS ON THIS PC** first (they split the keyboard like local co-op).
4. Pick your ship right in the lobby. With several players on one computer, each one changes their own ship with their own keys (**A/D**, **←/→** or **J/L**), or clicks their own slot. The host presses **START**.
5. Once everyone is in, the host can press **LOCK ROOM [K]**: nobody new can get in, not even with the code.

Want to play with anyone? **HOST A PUBLIC GAME** puts your room on **BROWSE PUBLIC GAMES**, where anyone can join, even after the game starts. Every public room now announces itself. The list used to be kept in one random player's browser, so a single player on a VPN or a strict network could make every public game disappear for everyone. Now a room only fails to show up if *your* computer can't reach it (and then you couldn't have joined it anyway).

The host is in charge of who's in the room: **✕** next to a player in the lobby (or **PLAYERS & ROOM** in the in-game menu) removes that player's computer (it asks twice, so a stray click can't do it), and the room can be locked or switched between public and private at any time without kicking anyone already playing.

### Privacy and safety

- **No game server, no accounts, no hidden menus.** Your computer connects straight to the other players' computers. That means the people you play with can see your IP address, as in any peer-to-peer game. A private room only ever connects you with people who have its code.
- **Nothing else about you is sent.** No names, files or save data: only your ships, cosmetics and what you do in the game. Your shards, unlocks and settings stay in your browser.
- **Opening the online screen doesn't connect you to anyone.** It only checks your connection with Google's STUN server. Browsing public games connects you to each public host (so they can see your IP address too). Private rooms never appear on the public list.
- **Everything other players send is checked.** Nobody can control someone else's ship, crash the game with bad data, or mess with your shards or your save.
- **The only outside code is the online library (PeerJS)**, and it only runs if it matches its known fingerprint. While you're online, the game also talks to the PeerJS matchmaking server (so computers can find each other) and Google's STUN server (to find your connection's address). Nothing else.

Playing with friends far away (other countries) works better now: busy fights no longer freeze guests' screens, the game smooths things out more on bumpier connections, enemy bullets are shown where the host will check them so dodging feels fair, and guests see their PING in the bottom-left corner (green under 120 ms, yellow under 250, red above). With many players the host's internet upload matters most, so the player with the best connection should host.

If joining doesn't work: make sure you all refreshed the page (Ctrl+F5) so you have the same version (the ONLINE CO-OP screen shows the online version, now 7), and know that a VPN or a strict network (like school Wi-Fi) can block the connection between two computers. The ONLINE CO-OP screen checks your connection and warns you if it looks blocked. Joining gives up with a message after a few tries instead of loading forever.

## Controls

- **Move:** mouse, WASD, arrow keys, or a gamepad — your ship fires automatically
- **Controllers:** left stick or D-pad to fly, A, X, RB or RT for your ability, START to pause, A to pick and B to go back in menus, and Y / B / X / A to answer DOKI DOLL. It rumbles when you get hit. Up to 4 controllers work for local co-op. On an Xbox, open the game in Microsoft Edge and the controller should work the same way.
- **Phones and tablets:** drag anywhere to fly (your ship sits just above your finger). The round button in the bottom right uses your ability, **II** in the top left pauses, and **⛶** on the menu goes fullscreen. Your phone buzzes when you get hit.
- **Ability:** Space, Q, E, Shift or right-click (gamepad: A, X or a right bumper/trigger; touch screens get a button)
- **P / Esc:** pause (see your build, settings, restart with **R**) · **M:** music · **F:** fullscreen · **1–4:** quick chat (online)
- **Online:** **Esc** opens your own menu while the game keeps going for everyone (settings, leave game). The host's menu also has **PAUSE FOR EVERYONE** (or press **P**).
- Local co-op: 2P = WASD (ability Q) + arrows/mouse (Right Shift / right-click) · 3P = mouse, WASD, arrows · 4P adds IJKL (ability U)

## Features

12 ship classes, all free (each with stronger MK II to MK V versions to unlock), each with its own ability · 33 upgrades · 34 enemy types · 19 boss fights (each solo boss has its own gimmick, plus team bosses and a nightmare final boss, THE ABYSS) ·
8 upgrade evolutions · ships that evolve as you power up · ship mastery · elite zones in Endless · co-op Link Beams · a mid-run shop · elite enemies · three secret bosses · 8 kinds of TURBULENCE ·
Standard, Endless, Boss Rush & MOH modes · 15 Hangar upgrades · 13 ship skins + 29 cosmetics (trails, bullet colors, kill effects, pets) · a boss gallery · a secret zone · Boss Rush medals · 8 hidden golden shards · 47 achievements · online quick chat (1–4) · an original soundtrack (below)

### MK II to MK V

Every ship is free. Each one also has a **MK II** (a stronger version with gold trim), and after that **MK III**, **MK IV** and **MK V**, bought in order with shards. Each one keeps everything the MK II has and pushes it further:

- **MK III:** +20% damage, 10% faster fire, +1 life, ability 20% faster. Prism-violet trim and 2 orbiting crystals.
- **MK IV:** +40% damage, 15% faster fire, +1 life, +5% speed, ability 30% faster. Mint trim and 3 crystals.
- **MK V:** +65% damage, 20% faster fire, +2 lives, +10% speed, ability 40% faster. Rainbow trim and 4 crystals.

Pick the version on the ship screen (press **V** to cycle through them). Own every MK III for the **Armada** trophy, and any MK V for **Fully Loaded**.

### Ship abilities

Every ship has one ability on a cooldown (the MK II's is stronger and comes back faster):

- **Striker — Nova Bomb:** wipes every enemy bullet off the screen and blasts everything on it.
- **Interceptor — Dash:** dash the way you're heading, untouchable, cutting through enemies.
- **Juggernaut — Fortress:** invincible for a few seconds, and bullets that hit you bounce back.
- **Scatter — Flak Ring:** rings of bullets in every direction.
- **Piercer — Railshot:** a beam straight up that pierces everything for huge damage.
- **Medic — Lifeline:** revives every downed teammate at once (or shields the whole team).
- **Wraith — Shadow Step:** phase out on demand and move 60% faster while phased.
- **Carrier — Swarm:** a swarm of homing missiles.
- **Berserker — Rampage:** double damage, faster fire, and you smash through enemies you ram.
- **Gunslinger — Fan the Hammer:** empties the whole cylinder at the closest enemy at double damage, then reloads instantly. (The Gunslinger fires 6 heavy rounds fast, then has to reload.)
- **Bomber — Megaton:** drops one huge, slow bomb that blasts everything around it and blows away enemy bullets. (The Bomber fires slow bombs that explode on whatever they touch, hitting everything nearby.)
- **Summoner — Sentry:** plants a turret that blasts nearby enemies for 12 seconds (two at a time). The Summoner is a real summoner, in the style of Terraria: it has no guns, but a **whip** that cracks at the nearest enemy and **tags** it, and **minions** (imps that spit fireballs, hornets that dive and ram) that go for tagged enemies first and hit them 60% harder. It starts with 3 minion slots (more from Wing Drone and extra-shot upgrades, up to 8), and it's fragile: one life fewer.

Some upgrade cards power up abilities. **Quick Charge**, **Aftershock**, **Adrenaline** and **Kill Charger** work for every ship. Each ship also has its own card that changes how its ability works: Mending Nova, Afterburner, Shockwave Fortress, Flak Storm, Overcharged Rail, Guardian Pulse, Phantom Blades, Hive Mind, Bloodthirst, Speed Loader, Payload and Overseer. A ship's card only shows up when someone is flying that ship.

### Ship mastery

Every ship levels up from 1 to 5 stars as you fly it, earning XP equal to the shards each run pays. Levels 2 to 4 pay bonus shards. Level 5 unlocks that ship's **Signature trail**, a twisting ribbon in its colors with ghost copies of the ship inside it. Equip it under Hangar → Skins & Cosmetics → Trails.

### Co-op: Link Beam

Fly close to a teammate for 3 seconds and a tether charges between you. When it's full, you fire a **Link Beam** together: a huge column of light that shreds everything above you.

### Ship evolution

The more upgrades a run piles up, the more every ship transforms: **Form II** at 6 upgrades (blades of light on the wings), **Form III** at 12 (a ring of energy circles the ship), and the **Final Form** at 18 (a burning halo and a white-hot core). Each form also hits a little harder.

### Turbulence

Before a run, press **X** on the menu (or in an online lobby, as the host) to switch on TURBULENCE: Glass Cannon, Behemoths, Hailstorm, Horde, Closed Shop, Slim Pickings, Powerless and Blackout. Each makes the run harder and pays extra shards, and they stack.

### Music

30 songs. Every zone has two songs, and each run picks one of them. The menus, the hangar, the shop, the route map, team bosses, the final boss, all three secret bosses, victory and game over each have their own song too.

The style is heavy rock in space: distorted guitars in both ears, a growling bass and big drums, with a bamboo flute, a koto, bells and taiko drums on top and lots of echo. When a boss shows up, the song turns into metal: galloping riffs, double bass drums and a lead guitar. When the boss gets **enraged**, it becomes an even heavier remake: much faster (160–196 BPM), darker, with drop-tuned guitars, twin lead guitars, blast beats and a breakdown.

THE ABYSS has its own song, **Flamewall**, made by the game's creator. It's a recording (`abyss.mp3`) that loops through the whole final fight. The secret bosses have recorded songs too: **Death** for the first one (`zero.mp3`), and **Doki Doki** for the pink one (`doki.mp3`). The Glitch Sector plays **Normal World** (`glitch.mp3`).

Listen to any song in the **Music Room** (Settings, or press **J** on the menu), and press **B** there to switch between its rock, metal and rage versions. Except for those three recordings, all the music is played live by the browser from notes written in the code.

### Bosses
**Regenerating bosses:** leave a boss alone for about 4 seconds (3 in MOH) and it starts to heal (2% of its health per second, 3% in MOH), with a green REGENERATING tag on its health bar. It never heals past its next phase mark (the 50% enrage, THE ABYSS's phases...), so a phase is never undone, and any hit stops it at once. Keep shooting!

Every boss has its own shape. The Warden is a fortress shield, Hexcore a hex nut, Stormcaller a storm cloud, The Hive a beehive, Phantom a ghost, Chronos a pocket watch, The Oracle one giant eye, and so on. The team bosses get their own shapes too: stars, a sun and a crescent moon, cut gems, a sword and more.

At half health a boss gets **ENRAGED**. It roars, blows away the bullets around it, and transforms in its own way. The Warden's shield plates burst off and its battlements turn into spikes. Hexcore melts down white-hot. Null Seraph grows blood-red wings and a crown. The Wyrm catches fire from head to tail. The Architect's tiers fly apart. The Singularity collapses to a pinpoint and bursts back out. Every solo boss also learns a new move that it only uses when enraged:

- **The Warden:** swings chains of bullets around itself.
- **Hexcore:** lobs magma bombs that leave burning pools.
- **Null Seraph:** crosses beams of light over each player. Its health running out isn't the end: it comes back as the golden **SERAPH OF SIX WINGS**.
- **Void Lancer:** charges three times in a row.
- **Stormcaller:** sends a wall of lightning across the screen with one safe lane.
- **The Hive:** fires homing stingers. Bring it down and the hive cracks open: **THE QUEEN** bursts out, a giant bee with a crown, and sends out bees of her own.
- **Phantom:** teleports right next to you.
- **Echo:** summons a mirror image that copies its attacks.
- **Chronos:** rewinds time so its bullets fly back. Bring it down and it shatters into **THE HOURGLASS**, its sand running out with its health, pouring sand down the screen with one gap to slip through.
- **The Wyrm:** breathes fire. Bring it down and it sheds its skin, rising again as the **BONE WYRM**, a skeleton burning with green ghost fire.
- **The Architect:** closes walls in from both sides.
- **The Oracle:** sweeps a giant beam across a marked arc. Bring it down and it opens **A HUNDRED EYES** all around it, and they shoot at you.
- **The Singularity:** sucks every bullet in, then blasts them back out.
- **The Leech:** sprays blood that rushes back into it.
- **DAWNNY:** inspired by a friend of the game's creator who loves manga, anime and books, and the Roblox games Murder Mystery and Flee the Facility. An open manga book in a pink heart frame, with a heart bookmark and a detective's magnifying glass. She throws PAGE STORMS, screams in manga speech bubbles (KYAA!, OMG!!), ships two hearts together (SHIP IT!: the pink line between them hurts), and throws knives. Every so often she starts a round from her favorite games: **WHO DUNNIT?** (she hides among identical suspects, and only the murderer throws knives: shoot the right one to make her dizzy, shoot an innocent and you get a burst of hearts) or **THE BEAST** (she can't be hurt and chases you: hack all three computers to escape and leave her dizzy). Enraged, she goes into MANGA WITHDRAWAL and uses **TO BE CONTINUED...**: manga panel borders slam down across the screen. Her song is **Next Chapter!!**.
- **Zero:** loads in with a LOADING ZERO.EXE bar, and fights in three forms, rebooting between each (it can't be hurt while it reboots): **ZERO**, a cube of flickering pixels; **NULL**, a bare core with its pixels orbiting it; and **FATAL ERROR**, corrupted memory flickering between the faces of other bosses it stole, skipping around the screen and deleting half of it in a checkerboard. It **steals every other boss's abilities**, announcing each one (STOLEN: STORMCALLER'S LIGHTNING) and wearing that boss's face while it uses it: their signature attacks (the Hive's eggs, Sonnet's spin dash, DOKI DOLL's hearts, Nemesis's missiles and more), their whole mechanics for 10 seconds at a time (the Warden's pylons, Hexcore's overheat, Null Seraph's mirror halo, Stormcaller's lightning, the Architect's walls, the Oracle's judgment, the Singularity's supernova, Echo's echoes, Chronos's time stop and Phantom's decoys), and their rage moves (all 16), in every form. Its new moves: **LAG SPIKE** (its bullets freeze, then jump ahead), **COPY-PASTE** (every bullet it has out gets a mirror copy), and **DEAD PIXELS** (falling pixels with one gap).
- **SONNET:** halfway through, seven emeralds turn him into the golden **SUPER SONNET**. He can't be hurt while he transforms, his health refills, he takes less damage, and he dashes around a star at light speed. (A nod to a certain blue hedgehog.) His fight plays **Golden Hour**, made by the game's creator: the instrumental, switching to the version with vocals at the very same moment in the song when he turns golden.

### THE ABYSS

The final boss gets a full entrance. The music dies and the screen glitches until the game seems to crash. A dead terminal types out a warning, then one giant eye opens in the dark, then dozens more. They all close as it laughs, tentacles slam in from the edges, and it rises out of the dark to its own song, **Flamewall**. After you've seen it once, press **Enter**, **Space** or **A** to skip ahead.

It fights in three phases, learning new moves in each:
- Tentacle lashes, ink rings and eruptions from below.
- Eyes that open in the dark around the screen and fire beams at you.
- Giant shadow hands that grab where you are.
- Black rain with one dry lane drifting across.
- Shades that hunt you in the dark.
- In its last phase, a frenzy where every tentacle strikes in turn.

When the lights go out, its eyes glow in the dark and it whispers to you. When it fully awakens, the screen breaks up, a crown of horns tears out of it, and its outline looms over the darkness.

Lose to it, and it leaves its mark: the main menu stays haunted until you finally beat it.

And once you've found the first secret boss, keep an eye out. Someone else might join your game.

Something pink is hiding out there too. Some enemies drop rare **pink coins**... and she can't be beaten the usual way. (A little nod to a certain pink doll from Deltarune.)

Regular enemies are animated too. They warp in, squash when hit, and break into pieces when destroyed. Ships fly with engine flames, gunners aim their barrels, and slimes blink.

### Zones

Every run travels through space, zone by zone. You always start in **Deep Space**. After a zone's last boss you choose your next zone from three on a **route map**. All routes end at the **Event Horizon**, where THE ABYSS waits. Every zone has its own sky, its own bosses and enemies, and a hazard:

- **Shattered Belt:** meteors tear across flashing lanes.
- **Crimson Nebula:** lightning strikes pink circles.
- **Frozen Rings:** drifting ice blocks enemy shots.
- **Solar Corona:** solar flares blast down glowing columns.
- **Derelict Fleet:** old turrets shoot at everything, enemies included.
- **Prism Reach:** prisms split every shot in three, yours and theirs.

**The Glitch Sector:** a secret zone. Beat THE ABYSS in a Standard run and press the (very glitchy) **CONTINUE INTO ENDLESS** button, and Endless starts right there. Once you've beaten ZERO, it can also show up on the route map. The screen tears (a warned strip shifts everything in it sideways), enemies flicker and teleport, and **INPUT ERROR** flips your left and right for a few seconds. Its last fight is always ZERO, at home. Its song is **Normal World**, made by the game's creator. It sends fewer enemies than other zones (its glitches are the danger), and gives you a few calm seconds when you arrive.

**GLITCH variants:** in the Glitch Sector and in every Endless run, every boss is a corrupted copy of itself (THE WARDEN becomes **TH3 W4RD3N**), running on broken memory:

- **How it looks:** chunks of its body are missing (black-and-violet "missing texture"), a band of it breaks up into big pixels and slowly slides, its pixels melt off it in streaks, dead pixels drip from it, and hex codes swarm around it. It **downloads** in (> DOWNLOADING TH3_W4RD3N.EXE) as blocks fly together.
- **NOT RESPONDING:** right before each glitch attack it freezes (its animation stops, it frosts over, and a busy spinner appears). That's your warning.
- **Its glitch attacks:** it knows two to start with (one each in a team fight):
  - **BINARY RAIN:** rows of 0s and 1s fall, each with a gap that wanders from row to row.
  - **FORK BOMB:** processes split in two, then split again, into a spray of dead pixels.
  - **ERROR:** error boxes pop up around the screen, fill their progress bars, then crash into rings of dead pixels.
  - **BIT FLIP:** spreads of 0s and 1s, but only one kind moves at a time. They swap twice a second (the frozen ones are dim).
  - **SEGMENTATION FAULT:** the lower screen splits into memory blocks, and about a third of them go bad after a warning.
  - **MEMORY LEAK:** leaked blocks spray out and creep down at you, until the **GARBAGE COLLECTOR** sweeps them away.
  - **PING FLOOD:** streams of packets shoot across the screen from the sides, along marked lines.
- **CORRUPTION:** its health bar shows how corrupted it is, with holes in the bar. Every 25% the whole screen breaks into pixels for a moment, **BUGS** (little pixel beetles) crawl out of it, and it learns another glitch attack.
- **SYSTEM CRASH:** at 75% corruption every bullet is wiped, and a **REBOOT SCAN** sweeps down the screen twice. Each pass has one open **PORT** to slip through, and both ports are shown from the start. It can't attack while it reboots.
- **When it dies** it stops working ("TH3 W4RD3N has stopped working") and is deleted top down into falling pixels: **CORRUPTED (core dumped)**.

Regular enemies get GLITCH variants there too. They download in behind a scan line, have holes and scanlines, fall apart into pixels, and each carries a bug of its own (shown above it): **fork()** splits in two when destroyed, **BUFFER** fills up as you hit it and then overflows into a ring of dead pixels, **OVERCLOCK** glows amber and then runs at double speed for a moment, **LEAK** drips leaked memory behind it, and **CRASH** leaves an error box behind that bursts. In that Endless, the sky glitches now and then too. You can see (and practice) every boss's GLITCH form in the gallery.

**Elite zones:** from cycle 2 of Endless, every zone gets a second hazard on top of its own:
- **Deep Space:** Starfall, with falling stars down marked columns.
- **Shattered Belt:** meteors that shed burning rocks.
- **Crimson Nebula:** lightning in long chains.
- **Frozen Rings:** an ice storm sweeping across the screen.
- **Solar Corona:** walls of flares with one gap.
- **Derelict Fleet:** turrets that launch suicide drones.
- **Prism Reach:** prisms that pulse out rings of light.
- **Event Horizon:** a gravity tide that drags everything toward the black hole.

The whole game is a single file: `index.html`.

### Second lives

Some bosses don't stay down. When THE WYRM, NULL SERAPH, THE HIVE, CHRONOS or THE ORACLE runs out of health, it stops, clears the screen, and comes back in a super form with 60% of its health. It can't be hurt while it transforms, and afterwards it takes less damage and attacks faster. The Hive, Chronos and the Oracle each get a new attack in their second life, too.

### Boss gallery

Press **G** on the menu (or open it from the Hangar) to see every boss fight you've met, drawn live, with how many times you've beaten it and your fastest kill. Bosses you haven't met are dark silhouettes, and the secret ones are just a **?** until you find them. Press **R** to see the rage and super forms of the bosses you've beaten.

Click a boss to open its page. Once you've beaten it in a run, you can **practice** it there: a single fight against just that boss, with a mid-run build (no shards, no score). **HARD** makes it enraged from the start, 25% faster and 25% tougher. Beat it on HARD and its tile turns red with a ☠.

THE ABYSS and ZERO also have their story on their pages, unlocked a piece at a time: by meeting them, beating them, beating them 3 times, and beating them on HARD.

### Pets

A little companion that follows your ship around (Hangar → Skins & Cosmetics → Pets). It grabs pickups that come near it and brings them to you, sometimes fetches a bonus coin from kills close to it, pops a heart when you're revived, and jumps for joy when a boss goes down. Spark, Buddy Drone and Starling can be bought with shards. Mini Doki, Mini Sonnet, Null Bit, P0 and Little Eye unlock by beating the secret bosses and THE ABYSS. Online, your friends see your pet too.

### MOH

A fourth run type (press **E** on the menu, or in the lobby): standard sectors and bosses, but built to be as hard as it can be while staying fair. You start with 2 lives, enemies are tougher, faster and about twice as many (often arriving in packs) from the first sector, and it gets worse every few sectors; there are far more elites, hearts are rarer, and bosses attack faster, have more health, enrage at 70% instead of 50%, and keep getting reinforcements all through the fight. And **hands** reach in from the dark all run long: a red ring shows where, and a hand of shadow closes on it about a second later. They follow you only for a moment, never come at someone who was just hit, and are rarer during boss fights, so a normal reaction is always enough. MOH pays 50% more shards, and destroying THE ABYSS in it earns the **Out of the Hands** trophy.

### Boss Rush medals

Clear Boss Rush fast enough for a medal: 🥇 **gold** under 16:00, 🥈 **silver** under 22:00, and 🥉 **bronze** for any clear (when ZERO joins the end of the rush, you get 1:15 extra). Your best medal and time show on the menu when Boss Rush is picked. Gold unlocks the **Champion** skin.

Run times are real time. The run clock used to count every second twice, so times (the run timer, Boss Rush medals and fastest boss kills in the gallery) showed double. Old records were halved to their real times, and any Boss Rush medal your real time had earned was handed out.

### Golden shards

One golden shard is hidden in each of the 8 regular zones. Each time you visit a zone whose shard you haven't found, there's a chance it drifts across the screen once, faint and twinkling. Fly into it to keep it. Online, a shard found by anyone counts for everyone. The Hangar shows how many you have, and finding all 8 unlocks the **Shardglass** skin.
