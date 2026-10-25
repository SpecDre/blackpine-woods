# Blackpine Woods

A 32-bit pixel-art mushroom foraging adventure that runs in the browser. It's a single `index.html` with no build step and no dependencies beyond Google Fonts.

Start as a backpacker with 5 coins. Examine wild mushrooms (cap, underside, stem, smell) to identify them, trade with Old Wren, chop trees, fish, build a lean-to and then a cabin, and grow oysters and shiitake. Then explore beyond the woods: Foxfire Cave and the Glowroot Depths below it, Willow Marsh, Silverrun Lake, Highpine Ridge, the mountain village of Cloudpeak and Frostfall Tarn. Along the way you track down the scattered members of the Foragers' Club.

Three skills level up separately: Foraging, Woodcutting and Fishing.

## Play

Open `index.html` in a browser, or visit the deployed site.

- **Move:** arrow keys or WASD (on-screen joystick on phones)
- **Interact / continue:** E, Space or Enter
- **Basket** I · **Journal** J · **Quests** Q · **Map** M

## 3D view (beta)

`3d.html` opens the same game with a 3D "HD-2D" view of Blackpine Woods: the pixel-art ground becomes a lit 3D floor with sunken water, and trees, people, animals and props stand up as sprite cards with real shadows, a day/night cycle and campfire light. It uses Three.js r128 from cdnjs, loaded only when the 3D view is on. In the main game it's a switch under **⚙ Game → View**. Other areas still show in 2D for now. Saves are shared between the two pages because they're on the same site.

## Saving

Progress saves automatically in the browser's local storage, separately for each website. To move a game between sites or devices, open **⚙ Game**, choose **Copy save code**, then paste the code into **Load a save code** on the other site. Codes for this version start with `BPW2.`. Codes from the older, smaller version (`BPW1.`) don't carry over.

## Deploy

It's a static site, so any static host works. On Vercel, the project root is served as-is.

## Note

This is a game, not a field guide. Never eat a wild mushroom based on a description, a picture or a game. Mushroom facts are drawn from *The Mushroom Bible* by Richard Korman, rewritten for the game.
