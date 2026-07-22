# My Aseprite Theme

Improved version of the default Aseprite dark mode theme with some personal adjustments.

## Installation

1. Clone/download the repository contents.
2. Open the Aseprite data folder from Steam by clicking on the gear and navigating to "Browse local files":
   <img width="536" height="427" alt="Screenshot 2026-07-20 at 7 47 14 PM" src="https://github.com/user-attachments/assets/c36e810e-a2fa-4322-9370-5e9154907fde" />
3. Put the repository contents inside of `data/extensions`. Since the repository name is `aseprite-theme`, you may want to rename it to avoid conflicting with the default theme.
4. Restart Aseprite.
5. In Aseprite's preferences, navigate to the Theme category, click "Evorp's Aseprite Theme", click Select on the bottom, then click Apply on the bottom right. The theme should apply normally from there.

## Changes compared with the default Aseprite dark theme:

- Completely replaced the "Mini" font with the regular one in all cases (the mini font is horrendously illegible in a lot of cases when the regular font doesn't even cause any scaling issues to begin with).
- Made dividers solid instead of dashed (the dashed borders intersect weirdly with corners and cause a lot of visual noise).
- Made the home tab icon look a bit less disproportionate (doors are Not that tall).
- Removed background from icon buttons on title bars (I thought it looked cleaner and it's more consistent with native UI).
- Improved the Aseprite icon on the home page (the stock one is just an inverted version of the light mode logo which messes up the shading).
- Made the focused button border appear on the outline instead of inside the button (this is what macOS does which I use, and I think it looks cleaner than the Windows-styled inner border).
- Brightened the scrollbar up a bit and made the gutters Not solid black (this is a bit janky because of how Aseprite maps each UI element but whatever).
- Made the close tab hover effect consistent with other hover effects throughout the app (the default theme uses this weird antialiased transparency mask).
- Changed the folder group icon to a disclosure triangle (I kept confusing the closed and open folder icons at small scales).
- Made the main content border match the other area borders (I honestly have no idea why this is unique in the default theme lol).
- Fix inconsistent arrow sizing (the downward facing arrow was larger than the others and the standby state had an inconsistent shadow).
- Improve user data icon to be more visible (the attempt at a hamburger icon really wasn't doing it for me).
