# TactCs

A tactical 5v5 bomb-defusal shooter made in Unity, with an original map and online multiplayer.
(In game it's called **Breachpoint**.)

## How to play (Windows)

1. Click **CS.zip** above, then the **Download** button (the download arrow).
2. Unzip it (right-click → **Extract All**) and run `Breachpoint.exe` inside the folder. Keep all the files together.
3. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
4. Allow the game through the firewall if asked.
5. **Online:** one player picks **Host Online** and shares the join code. Everyone else types it and picks **Join Online**.
   Everyone must pick the same Relay type (DTLS is the default; try **WSS** if it won't connect).
6. **Same Wi-Fi (LAN):** one player picks **Host LAN**; the others type the IP shown on the host's screen and pick **Join LAN**.

Everyone needs the **same version** of the game – download it again when this page is updated.

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

## Rules

- Terrorists plant the bomb at site A or B; Counter-Terrorists stop them or defuse it.
- First team to 7 rounds wins; sides swap after round 6.
- Money for kills and rounds; buy weapons, armour, a defuse kit and grenades during buy time.
  Anything unused that you bought this round can be refunded.
- Weapons: Pistol, Hand Cannon, SMG, Assault Rifle (T), Carbine (CT), Sniper, Machine Gun, knife,
  HE / flash / smoke grenades.

## Host console commands

`pause` / `unpause`, `restart`, `warmup_end`, `endround t|ct`, `swapteams`, `scramble`,
`team <player> t|ct|spec`, `kick <player>`, `money <amount> [player|all]`, `roundtime`, `freezetime`, `say <text>`.
Everyone: `status`, `jointeam`, `sensitivity`, `fov`, `volume`.
