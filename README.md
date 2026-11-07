# Lanternfall

A first-person, turn-based dungeon crawler for your phone, inspired by classic grid-based
crawlers. It's one HTML file with no install, no account and no ads.

## Play
- **Move:** put your thumb on the left side of the controls and slide. It's a floating joystick (forward, back, sidestep).
- **Look:** drag anywhere else, on the view or the right side.
- **⚔ Strike** attacks what's in front of you. Auto-strike (on by default, toggle in Menu) swings for you when a monster is close and in front.
- Near a shrine or the peddler the Strike button changes to Drink or Trade. Chests open when you walk into them.
- Real-time combat: monsters glow red just before they hit, so back off to dodge.
- **🔥 Firebolt** (4 MP) is a projectile. **✚ Mend** (5 MP) heals. Tonics heal, Ethers restore mana.
- Find the glowing stairs to go deeper. Every 5th floor a **Gloam Warden** guards them.
- 3 classes: **Sellsword** (tank), **Ashbinder** (mage), **Cutpurse** (crits, dodges, extra gold).
- 4 zones that repeat deeper and harder: The Ossuary, Drowned Vaults, Ember Halls, Pale Below.

## Saving
- 3 save slots, stored in your browser (`localStorage`).
- Saves automatically every few seconds, after key events, and when you leave the app.
- A checkpoint is saved at the start of every floor. If you die, you can **Rise again** there (you lose 25% of your gold).

## Put it on your phone
1. Host it with GitHub Pages: repo **Settings → Pages → Deploy from branch**, then pick the branch and `/ (root)`.
2. Open the Pages URL in Safari (iPhone) or Chrome (Android).
3. **Share → Add to Home Screen.** It opens full screen like an app and works offline after the first load.

When the game is hosted as a Claude artifact, saves are also backed up to your account and restored if the phone's copy is lost.

Otherwise, saves belong to the browser and address you play on. If you clear Safari website data, your saves are deleted too.
