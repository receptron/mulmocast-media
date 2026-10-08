# Sound Effects

Short sound effects for MulmoCast videos (clock ticks, clicks, pops, hits, jingles…).
MulmoCast does not bundle any sound effects; scripts refer to these files by URL:

```
https://github.com/receptron/mulmocast-media/raw/refs/heads/main/soundeffects/<path>
```

e.g. `https://github.com/receptron/mulmocast-media/raw/refs/heads/main/soundeffects/opengameart/bart-ticking-clock/ticking_clock.wav`

All sounds are CC0 1.0. Sources, authors, original license files and the rules for adding new
sounds are in [LICENSES.md](LICENSES.md).

## Contents

Each pack also has a `Preview.ogg` (a montage of the whole pack) except `impact-sounds` and
`interface-sounds`. Numbering differs per pack: `name_000.ogg` (impact), `name_001.ogg`
(interface), `name1.ogg` (digital, ui, rpg), `name-1.ogg` (casino), `jingles_HIT00.ogg` (jingles).

### `kenney/impact-sounds` — hits and footsteps (5 variations each)

| Files | Sound |
|---|---|
| `impactPunch_medium_*`, `impactPunch_heavy_*` | Punch, slap (バシッ, ドスッ) |
| `impactSoft_medium_*`, `impactSoft_heavy_*` | Soft thud on cloth or cushion (ボフッ) |
| `impactWood_light/medium/heavy_*`, `impactPlank_medium_*` | Knock on wood (コン, ゴン) |
| `impactMetal_light/medium/heavy_*`, `impactTin_medium_*` | Metal clang (カーン) |
| `impactPlate_light/medium/heavy_*` | Ceramic plate clink (カチャン) |
| `impactGlass_light/medium/heavy_*` | Glass clink (チン, カチン) |
| `impactBell_heavy_*` | Bell strike (チーン) |
| `impactGeneric_light_*` | Generic light tap |
| `impactMining_*` | Pickaxe on rock (カキン) |
| `footstep_carpet/concrete/grass/snow/wood_*` | Single footsteps on each surface |

### `kenney/interface-sounds` — app / UI sounds

| Files | Sound |
|---|---|
| `click_*` (5), `select_*` (8), `switch_*` (7), `toggle_*` (4) | Clicks and switches (カチッ) |
| `tick_*` (3) | Short tick (チッ) |
| `pluck_*` (2), `drop_*` (4) | Pop / plop (ポン, ポトッ) |
| `confirmation_*` (4) | Positive "OK" chime (ピンポン) |
| `error_*` (8) | Negative buzz (ブッ) |
| `question_*` (4) | Rising "huh?" tone |
| `bong_001` | Gong-like bong (ボーン) |
| `glass_*` (6) | Glassy ding (キラン) |
| `open_*`, `close_*`, `maximize_*` (9), `minimize_*` (9), `back_*` | Window open/close, whoosh-like up/down |
| `scroll_*` (5), `scratch_*` (5) | Scroll ratchet, scratch |
| `glitch_*` (4) | Digital glitch |

### `kenney/ui-audio` — mechanical clicks

| Files | Sound |
|---|---|
| `click1`–`click5`, `mouseclick1`, `mouserelease1` | Mouse/button clicks |
| `switch1`–`switch38` | Many switch / toggle clicks |
| `rollover1`–`rollover6` | Soft hover blips |

### `kenney/digital-audio` — synth / game sounds

| Files | Sound |
|---|---|
| `powerUp1`–`powerUp12` | Power-up / level-up (ピロリロリン) |
| `phaserUp1`–`7`, `phaserDown1`–`3`, `highUp`, `highDown`, `lowDown` | Rising / falling sweeps (ヒューン) |
| `pepSound1`–`5` | Short bouncy blips (ポッ, ピョン) |
| `laser1`–`9`, `zap1`–`2`, `zapTwoTone*`, `zapThreeTone*` | Laser / zap (ピュン) |
| `tone1`, `twoTone1`–`2`, `threeTone1`–`2`, `lowThreeTone`, `lowRandom` | Beep tones |
| `phaseJump1`–`5`, `spaceTrash1`–`5` | Sci-fi jumps and noises |

### `kenney/rpg-audio` — everyday objects

| Files | Sound |
|---|---|
| `bookOpen`, `bookClose`, `bookFlip1`–`3`, `bookPlace1`–`3` | Book open/close, page turn (パラッ) |
| `doorOpen_1`–`2`, `doorClose_1`–`4`, `creak1`–`3` | Door, creak (ギィ) |
| `footstep00`–`09` | Footsteps |
| `handleCoins`, `handleCoins2` | Coins jingling (チャリン) |
| `metalClick`, `metalLatch`, `metalPot1`–`3` | Metal click, latch, pot |
| `chop`, `knifeSlice`, `knifeSlice2`, `drawKnife1`–`3` | Chop, slice, blade draw (シャキン) |
| `cloth1`–`4`, `clothBelt*`, `beltHandle1`–`2`, `dropLeather`, `handleSmallLeather*` | Cloth / leather rustle |

### `kenney/casino-audio` — cards, dice, chips

| Files | Sound |
|---|---|
| `dice-shake-*`, `dice-throw-*`, `die-throw-*`, `dice-grab-*` | Dice (コロコロ) |
| `card-place-*`, `card-slide-*`, `card-shove-*`, `card-fan-*`, `card-shuffle`, `cards-pack-*` | Playing cards |
| `chip-lay-*`, `chips-collide-*`, `chips-handle-*`, `chips-stack-*` | Poker chips (カチャカチャ) |

### `kenney/music-jingles` — short musical stingers (17 each, `00`–`16`)

| Files | Instrument |
|---|---|
| `jingles_HIT00`–`16` | Orchestral hits |
| `jingles_NES00`–`16` | 8-bit / chiptune |
| `jingles_PIZZI00`–`16` | Pizzicato strings (playful, good for kids) |
| `jingles_SAX00`–`16` | Saxophone |
| `jingles_STEEL00`–`16` | Steel drum |

### `opengameart/` — clock ticks

| File | Sound | Length |
|---|---|---|
| `bart-ticking-clock/ticking_clock.wav` | Tick-tock loop, 8 ticks (チクタク) | 8.0 s |
| `bart-ticking-clock/tick1.wav`–`tick4.wav` | Single ticks | ~0.2 s |
| `antumdeluge-ticking-clock/clock-1.ogg` / `clock-1.wav` | Ticking clock | 4.0 s / 3.7 s |
| `cemkalyoncu-tick-and-tock/tick.wav`, `tick2.wav` | Single tick / tock | 0.3 s / 0.1 s |

### `opengameart/ezduzziteh-boings` and `ezduzziteh-silly` — cartoon boings and blips

| File | Sound | Length |
|---|---|---|
| `ezduzziteh-boings/bing_01.mp3`, `bing_02.mp3` | High spring boing (ビヨン) | 0.4 s |
| `ezduzziteh-boings/bung_01.mp3` | Low boing (ボヨン) | 0.6 s |
| `ezduzziteh-silly/bloop.mp3`, `plup.mp3`, `blung.mp3` | Bouncy pops (ポヨン, プルン) | ~0.3 s |
| `ezduzziteh-silly/blah.mp3`, `booleh.mp3`, `uah.mp3` | Silly voice-like blurts | 0.4–0.6 s |

### `opengameart/junkala-512-retro-sfx` — 8-bit game sounds (512 `.wav`)

Files with `loop` in the name loop seamlessly. Folder → contents:

| Folder | Files | Sound |
|---|---|---|
| `general-sounds/positive-sounds` | `sfx_sounds_powerup1`–`18` | Power-up, success (ピロリン) |
| `general-sounds/negative-sounds` | `sfx_sounds_error1`–`15`, `sfx_sounds_damage1`–`3`, `sfx_sounds_negative1`–`2` | Wrong / error (ブブー) |
| `general-sounds/fanfares` | `sfx_sounds_fanfare1`–`3` | Short victory fanfare |
| `general-sounds/coins` | `sfx_coin_single1`–`6`, `sfx_coin_double1`–`7`, `sfx_coin_cluster1`–`9` | Coin pickup (チャリン) |
| `general-sounds/buttons`, `menu-sounds`, `interactions` | `sfx_sounds_button1`–`14`, `sfx_menu_move1`–`5`, `sfx_menu_select1`–`5`, `sfx_sounds_interaction1`–`26` | Button / menu blips (ピッ) |
| `general-sounds/simple-bleeps`, `high-pitched-sounds`, `neutral-sounds` | `sfx_sounds_Blip1`–`11`, `sfx_sounds_high1`–`7`, `sfx_sound_neutral1`–`11` | Simple beeps |
| `general-sounds/pause-sounds` | `sfx_sounds_pause1_in` / `_out` … `pause7_*` | Pause in / out |
| `general-sounds/impacts`, `simple-damage-sounds` | `sfx_sounds_impact1`–`15`, `sfx_damage_hit1`–`10` | Hits (ドカッ) |
| `general-sounds/alarms/alarms`, `alarms/low-health-alarms` | `sfx_alarm_loop1`–`8`, `sfx_lowhealth_alarmloop1`–`7` | Alarm loops |
| `general-sounds/weird-sounds` | `sfx_sound_refereewhistle`, `sfx_sound_bling`, `sfx_sound_poweron`, `sfx_sound_shutdown1`–`2`, … | Whistle (ピーッ), bling, power on/off, noises |
| `movement/jumping-and-landing` | `sfx_movement_jump1`–`20`, `sfx_movement_jumpN_landing` | Jump (ピョン) and landing |
| `movement/falling-sounds` | `sfx_sounds_falling1`–`12` | Falling (ヒュ～) |
| `movement/portals-and-transitions` | `sfx_movement_portal1`–`6` | Warp / scene transition |
| `movement/footsteps`, `climbing-stairs`, `climbing-ladder` | `sfx_movement_footsteps*`, `sfx_movement_stairs*`, `sfx_movement_ladder*` | Steps (single and loops) |
| `movement/opening-doors` | `sfx_movement_dooropen1`–`4` | Door open |
| `movement/vehicles` | `sfx_vehicle_carloop1`–`2`, `sfx_vehicle_helicopterloop1`–`4`, `sfx_vehicle_plainloop`, `sfx_vehicle_engineloop`, `sfx_vehicle_breaks` | Car, helicopter, plane loops; brakes |
| `explosions/*` | `sfx_exp_*` (clusters, double, long, medium, odd, short, shortest, various) | Explosions (ドカーン) |
| `weapons/*` | `sfx_wpn_*`, `sfx_weapon_*` (laser, cannon, punch, sword, guns…) | Weapons — mostly not for kids' content |
| `death-screams/*` | `sfx_deathscream_{alien,android,human,robot}*` | Death screams — not for kids' content |

## Handy picks

| Sound | File |
|---|---|
| Tick-tock (loop) | `opengameart/bart-ticking-clock/ticking_clock.wav`, `opengameart/antumdeluge-ticking-clock/clock-1.ogg` |
| Single tick | `opengameart/bart-ticking-clock/tick1.wav`, `opengameart/cemkalyoncu-tick-and-tock/tick.wav`, `kenney/interface-sounds/tick_00*.ogg` |
| Slap / punch (パチーン, バシッ) | `kenney/impact-sounds/impactPunch_medium_00*.ogg`, `impactPunch_heavy_00*.ogg`, `impactSoft_*.ogg` |
| Pop / pluck (ポン) | `kenney/interface-sounds/pluck_00*.ogg`, `drop_00*.ogg`, `kenney/digital-audio/pepSound*.ogg`, `opengameart/ezduzziteh-silly/bloop.mp3`, `plup.mp3` |
| Boing (ビヨーン) | `opengameart/ezduzziteh-boings/bing_01.mp3`, `bung_01.mp3` |
| Jump / fall (ピョン, ヒュ～) | `opengameart/junkala-512-retro-sfx/movement/jumping-and-landing/sfx_movement_jump*.wav`, `movement/falling-sounds/sfx_sounds_falling*.wav` |
| Whistle (ピーッ) | `opengameart/junkala-512-retro-sfx/general-sounds/weird-sounds/sfx_sound_refereewhistle.wav` |
| Click / switch | `kenney/interface-sounds/click_00*.ogg`, `kenney/ui-audio/click*.ogg`, `switch*.ogg` |
| Correct / wrong | `kenney/interface-sounds/confirmation_00*.ogg`, `error_00*.ogg`, `opengameart/junkala-512-retro-sfx/general-sounds/positive-sounds/*`, `negative-sounds/sfx_sounds_error*.wav` |
| Bell / ding (チーン) | `kenney/impact-sounds/impactBell_heavy_00*.ogg`, `kenney/interface-sounds/bong_001.ogg`, `glass_00*.ogg` |
| Power-up / level-up | `kenney/digital-audio/powerUp*.ogg`, `phaserUp*.ogg` |
| Short jingles (success, fanfare) | `kenney/music-jingles/jingles_{HIT,NES,PIZZI,SAX,STEEL}*.ogg`, `opengameart/junkala-512-retro-sfx/general-sounds/fanfares/*.wav` |
| Coin (チャリン) | `opengameart/junkala-512-retro-sfx/general-sounds/coins/sfx_coin_single*.wav`, `kenney/rpg-audio/handleCoins*.ogg` |
| Scene transition | `opengameart/junkala-512-retro-sfx/movement/portals-and-transitions/*.wav` |
| Page turn / door / coins | `kenney/rpg-audio/bookFlip*.ogg`, `doorOpen_*.ogg`, `handleCoins*.ogg` |
| Dice / cards | `kenney/casino-audio/dice-throw-*.ogg`, `card-place-*.ogg` |
| Footsteps | `kenney/impact-sounds/footstep_*.ogg`, `kenney/rpg-audio/footstep*.ogg` |
