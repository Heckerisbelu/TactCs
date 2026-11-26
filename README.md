# TactCs

A tactical bomb-defusal shooter made in Unity, with an original map and online multiplayer.
Two modes: **Competitive** (up to 5v5) and **Wingman** (up to 2v2).
(In game it's called **Breachpoint**.)

## How to play (Windows)

1. Click **CS.zip** above, then the **Download** button (the download arrow).
2. Unzip it (right-click → **Extract All**) and run `Breachpoint.exe` inside the folder. Keep all the files together.
3. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
4. Allow the game through the firewall if asked.
5. **Online:** the host picks a **Game mode**, clicks **Host Online** and shares the join code. Everyone else types it and picks **Join Online**.
   Everyone must pick the same Relay type (DTLS is the default; try **WSS** if it won't connect).
6. **Same Wi-Fi (LAN):** one player picks **Host LAN**; the others type the IP shown on the host's screen and pick **Join LAN**.

7. Everyone lands in the **lobby** and picks **T** or **CT**. The host clicks **START MATCH** (or **Start with warmup**).

Everyone needs the **same version** of the game – download it again when this page is updated.

**Latest update:** fullscreen mode, new gun and footstep sounds, player models aim up and down, DMG / ADR on the scoreboard, 3.2 s plant time, no hit marker, owned armour greyed out in the buy menu, and guns can be picked up after the round ends.

> Some school and work networks block online play. If **Host Online** fails, use a phone hotspot or
> home internet. **Network Diagnostics** in the main menu tells you what's being blocked.

## Controls (change them all in Settings)

| Key | Action |
|---|---|
| WASD / mouse | move / look |
| Shift | walk quietly |
| Ctrl / Space | crouch / jump |
| Mouse 1 / Mouse 2 | fire / scope, knife stab, short grenade throw |
| R | reload – **hold R** for a silent reload (slower, enemies can't hear it) |
| F | inspect weapon |
| 1 2 3 4 5 | primary / pistol / knife / grenades / bomb |
| E (hold) | plant or defuse the bomb, pick up guns |
| G | drop weapon or bomb |
| B | buy menu (refunds included) |
| M | change team |
| Tab | scoreboard |
| Y / U | chat / team chat |
| ~ | console (type `help`) |
| Esc | pause menu and settings |
| F11 / Alt+Enter | fullscreen on/off (also in Settings) |

## Game modes

| | Competitive | Wingman |
|---|---|---|
| Players | up to 5v5 | up to 2v2 |
| Map | full map, sites A and B | smaller map, site B only |
| Win | first to 13 rounds (12–12 is a draw) | first to 9 rounds (8–8 is a draw) |
| Sides swap | after round 12 | after round 8 |

## Rules

- Terrorists plant the bomb at site A or B; Counter-Terrorists stop them or defuse it.
  The bomb takes 40 s to explode and beeps faster as it gets close; defusing takes 10 s (5 s with a kit),
  and the defuse bar turns red if there isn't enough time. Terrorists can see a dropped bomb through walls.
- First to 13 (Competitive) or 9 (Wingman); sides swap at halftime; 12–12 / 8–8 is a draw.
- Money for kills and rounds; buy weapons, armour, a defuse kit and grenades during buy time.
  Anything unused that you bought this round can be refunded.
- Weapons: Pistol, Hand Cannon, SMG, Assault Rifle (T), Carbine (CT), Sniper, Machine Gun, knife,
  HE / flash / smoke grenades.

## Host console commands

`start`, `lobby`, `mode competitive|wingman`, `pause` / `unpause`, `restart`, `warmup_end`, `endround t|ct`, `swapteams`, `scramble`,
`team <player> t|ct|spec`, `kick <player>`, `money <amount> [player|all]`, `roundtime`, `freezetime`, `say <text>`.
Everyone: `status`, `jointeam`, `sensitivity`, `fov`, `volume`.
