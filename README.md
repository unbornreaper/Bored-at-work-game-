# Lanternfall

A first-person, turn-based dungeon crawler for your phone, inspired by classic grid-based
crawlers. It's one HTML file with no install, no account and no ads.

## Play
- **Move:** left pad (walk, back, turn, sidestep). Hold a button to keep moving, or swipe on the view.
- **Strike:** hits whatever is in front of you. Walking into an enemy attacks it too.
- **Firebolt** (4 MP) hits the first enemy in a line. **Mend** (5 MP) heals. Tonics heal, Ethers restore mana.
- Monsters only move when you act. Turning is free.
- Find the glowing stairs to go deeper. Every 5th floor a **Gloam Warden** guards them.
- Shrines fully restore you. A Lantern Peddler shows up every 3rd floor.
- 3 classes: **Sellsword** (tank), **Ashbinder** (mage), **Cutpurse** (crits, dodges, extra gold).
- 4 zones that repeat deeper and harder: The Ossuary, Drowned Vaults, Ember Halls, Pale Below.

## Saving
- 3 save slots, stored in your browser (`localStorage`).
- Saves automatically after every action and when you leave the app.
- A checkpoint is saved at the start of every floor. If you die, you can **Rise again** there (you lose 25% of your gold).

## Put it on your phone
1. Host it with GitHub Pages: repo **Settings → Pages → Deploy from branch**, then pick the branch and `/ (root)`.
2. Open the Pages URL in Safari (iPhone) or Chrome (Android).
3. **Share → Add to Home Screen.** It opens full screen like an app and works offline after the first load.

Saves belong to the browser and address you play on. If you clear Safari website data, your saves are deleted too.
