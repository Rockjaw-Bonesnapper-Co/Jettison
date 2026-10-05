# Jettison

Jettison is a World of Warcraft addon for the WoW Forever client. It ranks the items in your bags
from least worth keeping to most, so you know what to drop when your bags are full and what to sell
at a vendor.

This repository holds the licence and the issue tracker. The addon itself is published on
CurseForge and Wago Addons.

## What it does

- Each item shows what it sells for and what it is to you (a reagent for your trade, food for
  your level, worse than what you wear, nothing). The order is Jettison's judgement of what to
  drop first.
- Items you still need are locked and never offered: quest items you still need, upgrades, and
  anything you lock yourself with the padlock.
- With full bags, the loot window shows the loot beside your least useful item and offers the swap.
- Jettison hands you the item to drop; you confirm it the usual way. Nothing is dropped for you.
- At a vendor the list becomes a sell list. Sell junk sells your greys. Sell suggested shows what
  else Jettison would sell, so you can take anything off or lock it before you confirm.
- A ledger shows what you dropped since your last vendor against what you sold.
- Your bag slots show the rank of the first few items to drop, on the default bags and on the
  common bag addons.
- Quest items name their quest, and say when it is complete.
- Turning in a quest with full bags shows what to drop to make room for the reward.
- ItemTree, Auctionator, Auctioneer and TradeSkillMaster are read when installed. None is needed.

## How to open it

- Click the minimap button, or type `/jettison show` (or `/jet show`). `/jettison help` lists the
  commands.
- The list also opens by itself beside the loot window and beside a vendor.
- Right click the minimap button for the settings.

## Beta limits

- English only for now.
- Made for the WoW Forever beta client. It is not listed for other clients.

## Feedback

Please open an issue in this repository for a bug, a wrong ranking or a suggestion. Saying the item,
your level and class, and what you expected helps a lot.

## Licence

All rights reserved. Copyright (c) 2026 Rockjaw Bonesnapper Co. See [LICENSE](LICENSE) for the full
terms, which are short. You may download, install, run and read Jettison, and modify your own copy
for your own use. Anything else, such as uploading it elsewhere or publishing a modified version,
needs written permission first. When the compiled item data ships, `Jettison_Data/Facts.lua` will
carry its own licence line: the rows derived from the Classic Era tables are GPL 3.0.

Jettison is not affiliated with Blizzard Entertainment. World of Warcraft is a trademark of
Blizzard Entertainment, Inc. No Blizzard artwork is included.
