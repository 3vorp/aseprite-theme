# My Aseprite Theme

Improved version of the default Aseprite dark theme with some personal adjustments.

## Installation

1. Clone/download the repository contents.
2. Open the Aseprite data folder from Steam by clicking on the gear and navigating to "Browse local files":
   <img width="536" height="427" alt="Screenshot 2026-07-20 at 7 47 14 PM" src="https://github.com/user-attachments/assets/c36e810e-a2fa-4322-9370-5e9154907fde" />
3. Put the repository contents inside of `data/extensions`. Since the repository name is `aseprite-theme`, you may want to rename it to avoid conflicting with the default theme.
4. Restart Aseprite.
5. In Aseprite's preferences, navigate to the Theme category, click "Evorp's Aseprite Theme", click Select on the bottom, then click Apply on the bottom right. The theme may prompt you to change your UI scale, which you can completely ignore.
6. ???
7. Profit

## Changes compared with the default Aseprite dark theme:

> [!NOTE]
> Many of the changes originally implemented in this theme have since been upstreamed to the Aseprite beta branch ([to the point that I'm now actually in the Aseprite theme credits](https://github.com/aseprite/aseprite/blob/beta/data/extensions/aseprite-theme/package.json#L11)).
>
> I'm not mentioning these changes here since I've already pretty extensively documented them in their respective pull requests.
> If you're interested, see [`#5970`](https://github.com/aseprite/aseprite/pull/5970), [`#6070`](https://github.com/aseprite/aseprite/pull/6070), [`#6086`](https://github.com/aseprite/aseprite/pull/6086), and [`#6140`](https://github.com/aseprite/aseprite/pull/6140) for more information.

### Font

- Overhaul font to have a more consistent x-height, more distinct characters, and cleaner punctuation. May be updated more in the future.
- Completely replaced the Aseprite Mini font with the regular one in all cases (the mini font is horrendously illegible and it's practically the same size as the much better regular font anyways).

### Cleaner UI

- Made dividers solid instead of dashed (the dashed borders intersect weirdly with corners and cause a lot of visual noise).
- Removed background from icon buttons on title bars (the windows xp-era button styles really weren't doing it for me).
- Brightened the scrollbar up a bit and made the gutters Not solid black (this is a bit janky because of how Aseprite maps each UI element but whatever).

### Consistency

- Slightly rounded modal dialog box outlines to match the overall border radii used throughout the app more closely.
- Made the close tab hover effect consistent with other hover effects throughout the app (the default theme uses this weird antialiased transparency mask).
- Fix inconsistent arrow sizing (the downward facing arrow was larger than the others and the standby state had an inconsistent shadow).
- Made all area borders consistent (I honestly have no idea why there's like three unique styles in the default theme).


### Personal Preference

- Made the focused button border appear on the outline instead of inside the button (it is no longer 2009, we are better than windows 95 button styles).
- Changed the folder group icon to a disclosure triangle (I kept confusing the closed and open folder icons at small scales).
- Made the home tab icon look a bit less disproportionate (doors are Not that tall).
- Improve user data icon to be more visible (the attempt at a hamburger icon really wasn't doing it for me).
