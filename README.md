# SillyTavern-CatppuccinNightsTheme
A SillyTavern theme using the catppuccin mocha palette.

![Main page](/src/screenshot-main.png)

Second theme for SillyTavern and honestly? my daily drive. I really like Catppuccin Mocha, it's really easy on the eyes, at least for me, I even have my whole CachyOS themed with that palette. 

It's just a recolor of my first theme, because I always end up using dark themes, I like colourful themes but my eyes get tired faster than with dark colours, so I just recolor and tinker a bit. The main banner is using a different css to be full width. I hope you like it ♡

I added the background used in the screenshot, two different versions, a darker one and lighter one. But any catppuccin mocha wallpaper works here.

## How to use
First of all you need the extension [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs) so all the colors, fonts and CSS load properly, but it gives you more control to edit the theme, if you want to adapt it more to your liking. All the colors can be changed, except for some hardcoded colors on the info board.

Once you have the extension downloaded, in the **"User Settings"** tab import the theme from the folder `theme` called `Catppuccin Nights.json`. The theme is fully installed now!

![Settings page](/src/screenshot-settings.png)

In the screenshot you can see the extra three colors, and you can change the placement of the QR buttons, and having the default fonts if you're not keen into the cutesy ones I added. The CSS has some annotations too, in case you want to change something like the banner or remove the rainbow avatar frame, which by the way, adapts to all avatar styles!

### Moonlit Echoes version
To install the theme in Moonlit Echoes you have to add two files instead of one. In the **User Settings** tab import the theme from the folder `theme` called `Catppuccin Nights - Moonlit Echoes - Theme.json` and in the **Extensions** tab import the Moonlit Echoes preset `Catppuccin Nights - Moonlit Echoes - Preset.json` into the extension's settings. Now the theme is fully installed.

![moonlit echoes](/src/screenshot-moonlit-echoes.png)

## Info Board

![chat page](/src/screenshot-chat.png)

To use the info board, you need to be using the **"Chat Completion"** API, import the [extra prompt](https://discord.com/channels/1100685673633153084/1344396649245577307/1344496317438890044) on the **"AI Response Configuration"** and the regex file from the folder `info board` goes into the **"Extensions"** tab.

In the `info board` folder you will find three different info boards:
- **Default** is the regex for Selenis' original prompt. Add the prompt `prompt-[info_board]__default.json` and the regex `regex-[info_board]__default.json` 
- **Cozy** for an edited version more focused on slice of life. Add the prompt `prompt-[info_board]__cozy.json` and the regex  `regex-[info_board]__cozy.json`
- **Emoji** A more simple info board, the categories are emojis and have less information. The one I'm using now, just enough to keep the LLM more consistent in location, time and what the character is wearing. Add the prompt `prompt-[info_board]__emoji.json` and the regex  `regex-[info_board]__emoji.json`

### Cozy Info Board
![Cozy Info Board](/src/IB-Cozy.png)

### Emoji Info Board
![Emoji Info Board](/src/IB-Emoji.png)

> [!NOTE]
> The credit for the default info board goes to @Selenis, the others are based on her original one. Find Selenis' themes and prompt in SillyTavern discord

### Sources and credits

- [IceFog](https://github.com/IceFog72/) for the handy [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs).
- [Catppuccin](https://catppuccin.com/) for the palette that colours my digital life
- [qwerasd205](https://github.com/qwerasd205) for the most adorable monospaced font ever [Annotation Mono](https://qwerasd205.github.io/AnnotationMono/).
- [Looney patterns](https://looneypatterns.com/) for the stars SVG background on the info board.
- [King-Lulu-Deer](https://www.deviantart.com/king-lulu-deer/art/Witching-Hour-743636064) for the header gif.
- [Ana Tudor](https://codepen.io/thebabydino/pen/bGPMOpJ) for the css rainbow border.
- [Comehope](https://codepen.io/comehope/pen/YLqbXy) for the css stripes border.
- 480 Design for their [Solar icon set](https://icon-sets.iconify.design/solar/?suffixes=Bold%20Duotone)
- Sadly I don't know who the original authors of the edited backgrounds are... So I'll credit the original photographer [Lisa Fotios](https://www.pexels.com/photo/pink-flowers-photograph-1083822/)

If you want a place to find more catppuccin mocha wallpapers/backgrounds a good place is [orangc's walls](https://files.orangc.net/media/walls-catppuccin-mocha/)

