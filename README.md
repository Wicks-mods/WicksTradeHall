<p align="center"><img src="images/wick-thumb-trade.png" alt="Wick's Trade Hall"></p>

# Wick's Trade Hall

<!-- wick:badges:start -->
[![Downloads](https://img.shields.io/curseforge/dt/1502890?style=flat-square&labelColor=171124&label=downloads&color=4FC778)](https://www.curseforge.com/wow/addons/trade-hall)
![Forever](https://img.shields.io/badge/client-Forever-383058?style=flat-square&labelColor=171124)
[![License](https://img.shields.io/badge/license-MIT%20%2B%20trademark-383058?style=flat-square&labelColor=171124)](LICENSE)
[![Discord](https://img.shields.io/badge/discord-join-4FC778?style=flat-square&labelColor=171124)](https://discord.gg/GWGTMhYBZY)
<!-- wick:badges:end -->

The economy addon for **World of Warcraft: Forever**, built on
[WickCore](https://github.com/Wicks-mods/WickCore). Wick's Ledger folds in
here.

## What it does

**This session.** Gold, loot, experience and time, with what that comes
to an hour. It starts itself when you enter an instance and, with hard
lock on, pauses when you step out instead of ending, so one dungeon is
one session however many times you take a summon or run back from a
graveyard. Greys collapse into a single Junk row. The last five sessions
that earned anything are kept per character.

A session is persisted on every change, so a reload or a crash does not
lose it. One left running for eight hours is forgotten rather than
reported, because the numbers would mean nothing.

**The trade board.** The trade channel as a board rather than a wall of
scroll. Seven categories, one line per person per subject, and anything
nobody repeats for twenty minutes drops off. Channels with trade,
commerce or services in the name are picked up on their own, and say and
yell are read too because that is where a capital's bank steps trade.

The classifier is keyword based and deliberately cautious. A message has
to carry a trade signal at all, must not read like a group or guild
advert, and then falls through an ordered set of rules. It is wrong
sometimes; wrong into Misc is cheap, wrong into a category you are
reading is not, which is why the blacklist runs first.

## About prices

Loot is valued at its vendor price, and that is the honest ceiling here.
TSM, Auctionator and Auctioneer are what this read on TBC and none of
them exist on Forever, so there is no chain left to walk. This client
also will not price an item the character has never encountered, which is
exactly the case a fresh grey drop presents.

So anything that cannot be priced counts as nothing and is marked as
such. A total that quietly included guesses would be worse than one that
admits what it does not know. Shipped vendor prices, the way Wick's Gear
ships item data, will close most of that gap.

## Commands

| | |
|---|---|
| `/wth` | the window |
| `/wth board` | the trade board |
| `/wth clear` | empty the board |
| `/wth channels` | which channels are being watched |
| `/wth start` / `stop` / `reset` | the session by hand |
| `/wth bar` | show or hide the session bar |
| `/wth lock` / `unlock` | the bar's position |
| `/wth status` | what it can see |

`/wtradehall` is an alias.

## Compatibility

World of Warcraft: Forever, 1.60.x, Interface 16001. Requires WickCore.

## More from Wick

<!-- wick:suite-table:start -->
| Addon | GitHub | CurseForge |
|---|---|---|
| **WickCore** | [repo](https://github.com/Wicks-mods/WickCore) | [CurseForge](https://www.curseforge.com/wow/addons/wickcore) |
| **Wick's Comforts** | [repo](https://github.com/Wicks-mods/WicksComforts) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-comforts) |
| **Wick's Beasts and Things** | [repo](https://github.com/Wicks-mods/WicksBeastsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-beasts-and-things) |
| **Wick's Stances and Things** | [repo](https://github.com/Wicks-mods/WicksStancesAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-stances-and-things) |
| **Wick's Seals and Things** | [repo](https://github.com/Wicks-mods/WicksSealsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-seals-and-things) |
| **Wick's Conjures and Things** | [repo](https://github.com/Wicks-mods/WicksConjuresAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-conjures-and-things) |
| **Wick's Poisons and Things** | [repo](https://github.com/Wicks-mods/WicksPoisonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-poisons-and-things) |
| **Wick's Demons and Things** | [repo](https://github.com/Wicks-mods/WicksDemonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-demons-and-things) |
| **Wick's Bags** | [repo](https://github.com/Wicks-mods/WicksBags) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-bags) |
| **Wick's Trade Hall** | [repo](https://github.com/Wicks-mods/WicksTradeHall) | [CurseForge](https://www.curseforge.com/wow/addons/trade-hall) |
| **Wick's Gear** | [repo](https://github.com/Wicks-mods/WicksGear) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-gear) |
| **Wick's UI** | [repo](https://github.com/Wicks-mods/WicksUIForever) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-ui) |
| **Wick's Reminders** | [repo](https://github.com/Wicks-mods/WicksReminders) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-reminders) |
| **Wick's Map** | [repo](https://github.com/Wicks-mods/WicksMap) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-map) |

**Community:** [Discord](https://discord.gg/GWGTMhYBZY)
<!-- wick:suite-table:end -->

## License

MIT for code (see [LICENSE](LICENSE)). Brand chrome and the "Wick's" wordmark are trademarked, see [TRADEMARK.md](https://github.com/Wicks-mods/WickSuite/blob/main/TRADEMARK.md).
