<p align="center">
  <a href="https://jolaleye.github.io/horizon-theme-vscode/">
    <img alt="horizon banner" src="https://i.imgur.com/pwBUCSe.png">
  </a>
</p>

---

<p align="center">
  <!-- marketplace version -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="marketplace version" src="https://img.shields.io/vscode-marketplace/v/jolaleye.horizon-theme-vscode.svg?maxAge=3600&style=for-the-badge&colorA=1C1E26&colorB=FAB38E">
  </a>
  <!-- installs -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="installs" src="https://vsmarketplacebadge.apphb.com/installs-short/jolaleye.horizon-theme-vscode.svg?maxAge=3600&style=for-the-badge&colorA=1C1E26&colorB=FAB38E">
  </a>
  <!-- rating -->
  <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">
    <img alt="rating" src="https://vsmarketplacebadge.apphb.com/rating-star/jolaleye.horizon-theme-vscode.svg?maxAge=86400&style=for-the-badge&colorA=1C1E26&colorB=FAB38E">
  </a>
  <!-- donation -->
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=8U6XT98BHG63E&item_name=To+support+the+development+of+Horizon+and+my+other+open-source+projects.+Thank+you%21&currency_code=USD&source=url">
    <img alt="donate" src="https://img.shields.io/badge/donate-$-FAB38E.svg?style=for-the-badge&colorA=1C1E26">
  </a>
</p>

<p align="center">
  <img alt="preview" src="https://i.imgur.com/y0gi1ez.png" width="90%">
</p>

> The preview above shows the _Horizon_ theme with the _Roboto Mono_ font. Horizon also includes a _Horizon Italic_ variant.

## Installation

1. Open the **Extensions** sidebar in VS Code
2. Search for `Horizon Theme`
3. Click **Install** and **Reload**
4. Open the **Command Palette** with `Ctrl+Shift+P`
5. Select **Preferences: Color Theme** and choose a Horizon variant.
6. Enjoy! 🎉 Also, check out some of the personalization options below...

## Personalization

Themes are highly subjective and tastes change all the time. Luckily, VS Code makes it easy to customize just about every aspect of your editor.
If you want to change something, open the Command Palette with `Ctrl+Shift+P` and select **Preferences: Open Settings (JSON)**. You can then override VS Code's defaults or Horizon's colors in the right side of the settings view.
Check out some of the personalization options below to customize Horizon to suit your taste.

For more info on theming, visit the [Extension Authoring Guide](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers) and [Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference).

### Sidebar Contrast

```
"workbench.colorCustomizations": {
  "activityBar.background": "#1E2028",
  "activityBar.border": "#1E2028",
  "sideBar.background": "#1E2028",
  "sideBar.border": "#1C1E26"
}
```

### Italics

The normal theme only uses italics in a few places: comments, parameters, and some special keywords (e.g. `this`). If you would prefer no italics at all, you can configure this in your settings...

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "No italics",
      "scope": ["comment", "variable.language", "variable.parameter"],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```

### Tag Brackets `<>`

```
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "name": "HTML tag brackets",
      "scope": ["punctuation.definition.tag"],
      "settings": {
        "foreground": "#BBBBBB"
      }
    }
  ]
}
```

## Contributing

### [Code of Conduct](CODE_OF_CONDUCT.md)

Always try your best to make a positive impact on this project and its community. By participating, you are expected to uphold the Code of Conduct.

### [Contributing Guide](CONTRIBUTING.md)

Read the contributing guide to learn about how you can report issues and contribute to changes.

## Color Reference

### Syntax Colors

> **Note:** All syntax colors have 90% opacity so your eyes don't burn :)

|                            Color                            | Usage                                                                    |
| :---------------------------------------------------------: | ------------------------------------------------------------------------ |
| ![](https://via.placeholder.com/10/B877DB?text=+) `#B877DB` | Keywords, template literals & embedded punctuation (e.g. `${}` or `{}` ) |
| ![](https://via.placeholder.com/10/E95678?text=+) `#E95678` | Variables, property names, tags, markup headings                         |
| ![](https://via.placeholder.com/10/25B0BC?text=+) `#25B0BC` | Functions, escape characters, CSS #ids                                   |
| ![](https://via.placeholder.com/10/F09483?text=+) `#F09483` | Constants, regex, attributes, units, CSS .classes                        |
| ![](https://via.placeholder.com/10/FAB795?text=+) `#FAB795` | Strings, pseudo CSS, inherited classes, markup links                     |
| ![](https://via.placeholder.com/10/FAC29A?text=+) `#FAC29A` | Special keywords, classes                                                |

### Terminal Colors

|  Color  |                           Normal                            |                           Bright                            |
| :-----: | :---------------------------------------------------------: | :---------------------------------------------------------: |
|  Blue   | ![](https://via.placeholder.com/10/30AAD7?text=+) `#30AAD7` | ![](https://via.placeholder.com/10/56C2EA?text=+) `#56C2EA` |
|  Cyan   | ![](https://via.placeholder.com/10/1FDAD9?text=+) `#1FDAD9` | ![](https://via.placeholder.com/10/3CE8E6?text=+) `#3CE8E6` |
|  Green  | ![](https://via.placeholder.com/10/14D386?text=+) `#14D386` | ![](https://via.placeholder.com/10/0AF29D?text=+) `#0AF29D` |
| Magenta | ![](https://via.placeholder.com/10/E54EAF?text=+) `#E54EAF` | ![](https://via.placeholder.com/10/F360C4?text=+) `#F360C4` |
|   Red   | ![](https://via.placeholder.com/10/E95478?text=+) `#E95478` | ![](https://via.placeholder.com/10/E06783?text=+) `#E06783` |
| Yellow  | ![](https://via.placeholder.com/10/FAB795?text=+) `#FAB795` | ![](https://via.placeholder.com/10/FAC39A?text=+) `#FAC39A` |

### UI Colors

|                            Color                            | Usage                                              |
| :---------------------------------------------------------: | -------------------------------------------------- |
| ![](https://via.placeholder.com/10/1C1E26?text=+) `#1C1E26` | Primary background                                 |
| ![](https://via.placeholder.com/10/232530?text=+) `#232530` | Light background (popups & widgets)                |
| ![](https://via.placeholder.com/10/2E303E?text=+) `#2E303E` | Selection, highlights, input field background      |
| ![](https://via.placeholder.com/10/6C6F93?text=+) `#6C6F93` | Accents (e.g. scrollbar, drag and drop highlights) |
| ![](https://via.placeholder.com/10/F43E5C?text=+) `#F43E5C` | Errors, deletion highlights                        |
| ![](https://via.placeholder.com/10/E95378?text=+) `#E95378` | Accents (e.g. active tab, badges)                  |
| ![](https://via.placeholder.com/10/FAB38E?text=+) `#FAB38E` | Debugging status bar                               |
| ![](https://via.placeholder.com/10/FAC39A?text=+) `#FAC39A` | Modified Git decoration (explorer)                 |
| ![](https://via.placeholder.com/10/21BFC2?text=+) `#21BFC2` | Modified highlights (gutter & scrollbar ruler)     |
| ![](https://via.placeholder.com/10/27D797?text=+) `#27D797` | Warning highlights, untracked resources            |
| ![](https://via.placeholder.com/10/09F7A0?text=+) `#09F7A0` | Addition highlights                                |

## License

[MIT](LICENSE) © [Jonathan Olaleye](https://github.com/jolaleye)
