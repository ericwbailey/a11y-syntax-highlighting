# a11y-syntax-highlighting

Accessible light and dark syntax highlighting themes. Supports [WCAG level AA contrast requirements (good for most websites and apps)](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html).


## Use

You can [download the files directly](https://github.com/ericwbailey/a11y-syntax-highlighting/releases), or [use NPM](https://www.npmjs.com/package/a11y-syntax-highlighting). After that you can either link to the CSS you need directly, or incorporate it into your build sustem.

Other [services are also supported](#supported).


## Supported

### Libraries

- [Highlight.js](https://highlightjs.org/)
- [Prism.js](http://prismjs.com/)
  - [Line Highlight](https://prismjs.com/plugins/line-highlight/)
  - [Line Numbers](https://prismjs.com/plugins/line-numbers/)

### Applications

- [Adobe](https://helpx.adobe.com/illustrator/using/using-creating-swatches.html)
- [Figma](https://www.figma.com/) (drag SVGs onto your canvas)
- [macOS](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/DrawColor/Concepts/AboutColorLists.html)
- [Vim](https://www.vim.org/)
- [Xcode](https://developer.apple.com/xcode/)
- [macOS Terminal](https://support.apple.com/guide/terminal/welcome/mac)
- [iTerm](https://iterm2.com/)

### Misc

- [Carbon](https://carbon.now.sh/?bg=rgba(171%2C%20184%2C%20195%2C%201)&t=a11y-dark&wt=none&l=auto&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false) (remember to include alt text with your image!)
- [JSON](https://www.json.org/)


## Themes

### a11y-dark

![The a11y-dark theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-dark.png)

- Light text on a dark background.
- Background color of `#2B2B2B`.
- [WCAG AAA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| Background | `#2B2B2B` | N/A | N/A | N/A |
| No token | `#F8F8F2` | [13.28:1](https://webaim.org/resources/contrastchecker/?fcolor=F8F8F2&bcolor=2B2B2B) | AAA | AAA |
| Comment | `#D4D0AB` | [9.04:1](https://webaim.org/resources/contrastchecker/?fcolor=D4D0AB&bcolor=2B2B2B) | AAA | AAA |
| Blue | `#6BBEFF` | [7.03:1](https://webaim.org/resources/contrastchecker/?fcolor=6BBEFF&bcolor=2B2B2B) | AAA | AAA |
| Cyan | `#66DDEC` | [8.84:1](https://webaim.org/resources/contrastchecker/?fcolor=66DDEC&bcolor=2B2B2B) | AAA | AAA |
| Green | `#ABE338` | [9.28:1](https://webaim.org/resources/contrastchecker/?fcolor=ABE338&bcolor=2B2B2B) | AAA | AAA |
| Gray | `#F8F8F2` | [13.28:1](https://webaim.org/resources/contrastchecker/?fcolor=ABE338&bcolor=2B2B2B) | AAA | AAA |
| Orange | `#F5AB32` | [7.25:1](https://webaim.org/resources/contrastchecker/?fcolor=F5AB32&bcolor=2B2B2B) | AAA | AAA |
| Purple | `#DCC6E0` | [8.89:1](https://webaim.org/resources/contrastchecker/?fcolor=DCC6E0&bcolor=2B2B2B) | AAA | AAA |
| Red | `#FFA07A` | [7.12:1](https://webaim.org/resources/contrastchecker/?fcolor=FFA07A&bcolor=2B2B2B) | AAA | AAA |
| Yellow | `#FFD700` | [10.09:1](https://webaim.org/resources/contrastchecker/?fcolor=FFD700&bcolor=2B2B2B) | AAA | AAA |

### a11y-light

![The a11y-light theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-light.png)

- Dark text on a light background.
- Background color of `#FEFEFE`.
- [WCAG AA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast. WCAG AAA compliance forces the values on a light background to be too similar to each other to be used effectively for syntax highlighting.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| Background | `#FEFEFE` | N/A | N/A | N/A |
| No token | `#545454` | [7.5:1](https://webaim.org/resources/contrastchecker/?fcolor=545454&bcolor=FEFEFE) | AAA | AAA |
| Comment | `#802200` | [9.69:1](https://webaim.org/resources/contrastchecker/?fcolor=802200&bcolor=FEFEFE) | AAA | AAA |
| Blue | `#326BAD` | [5.41:1](https://webaim.org/resources/contrastchecker/?fcolor=326BAD&bcolor=FEFEFE) | AA | AAA |
| Cyan | `#1F7C93` | [4.77:1](https://webaim.org/resources/contrastchecker/?fcolor=007299&bcolor=FEFEFE) | AA | AAA |
| Green | `#008000` | [5.09:1](https://webaim.org/resources/contrastchecker/?fcolor=008000&bcolor=FEFEFE) | AA | AAA |
| Gray | `#696969` | [5.44:1](https://webaim.org/resources/contrastchecker/?fcolor=696969&bcolor=FEFEFE) | AA | AAA |
| Orange | `#A85D00` | [4.92:1](https://webaim.org/resources/contrastchecker/?fcolor=A85D00&bcolor=FEFEFE) | AA | AAA |
| Purple | `#9400D3` | [6.5:1](https://webaim.org/resources/contrastchecker/?fcolor=9400D3&bcolor=FEFEFE) | AA | AAA |
| Red | `#D91E18` | [5.01:1](https://webaim.org/resources/contrastchecker/?fcolor=D91E18&bcolor=FEFEFE) | AA | AA |
| Yellow | `#856514` | [5.38:1](https://webaim.org/resources/contrastchecker/?fcolor=856514&bcolor=FEFEFE) | AA | AAA |


### Forced Colors mode

Both themes have enhanced support for [Windows High Contrast Mode](https://support.microsoft.com/en-us/windows/change-color-contrast-in-windows-fedc744c-90ac-69df-aed5-c8a90125e696) when possible:

![The a11y-dark theme responding to Windows High Contrast Mode. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-forced-colors.png)


## FAQ

### Can you explain what the filenames mean?

- `a11y-light-on-light-dark-on-dark`: This theme contains both light text on a dark background and dark text on a light background visual treatments for code. It is set to show a light background color for code when your operating system's light mode is active, and a dark background color when your operating system's dark mode is active.
- `a11y-dark-on-light-light-on-dark`: This theme contains both light text on a dark background and dark text on a light background visual treatments for code. It is set to show a dark background color for code when your operating system's light mode is active, and a light background color when your operating system's dark mode is active.
- `a11y-light`: This theme uses a light background color for code for an operating system's light and dark modes.
- `a11y-dark`: This theme uses a dark background color for code for an operating system's light and dark modes.
- Files that end with `.min.css`: These themes have had their contents compressed to be used in production environments.
- `a11y-dark-legacy.css`, `a11y-dark-legacy.min.css` `a11y-light-legacy.css`, `a11y-light-legacy.min.css`: These files are for Internet Explorer support.

### What's the difference between non-legacy and legacy files?

The current version of each syntax file uses features not supported by Internet Explorer. These features include:

- [Cascade layers](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_layers),
- [`root:`](https://developer.mozilla.org/en-US/docs/Web/CSS/:root),
- [`:where()`](https://developer.mozilla.org/en-US/docs/Web/CSS/:where),
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*), 
- [`hsla()` color syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hsl),
- [Dark and light mode media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme), and the 
- [Forced Colors media query](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/forced-colors).

<strong>Only use the legacy files if you need to support Internet Explorer</strong>. Otherwise, syntax highlighting will not work for this browser.

### How do I only use light text on a dark background visual treatment, or vice-versa?

Don't use `a11y.css` or `a11y.min.css`, as they use the `prefers-color-scheme` media query. Pick either `a11y-light-on-dark.min.css` or `a11y-dark-on-light.min.csss` depending on what you want.

### What happened to the old color names?

Naming things is hard. I had to redo them to have better control between light and dark modes, as well as normalization across different services.

### What's the difference between `-ms-high-contrast` and `forced-colors`?

`forced-colors` is a cross-browser standard derived from the propritary `-ms-high-contrast` declaraction. It has a slightly different syntax, but will also honor legacy `-ms-high-contrast` code.

`-ms-high-contrast` <strong>will not</strong> honor `forced-colors` code. The situation is a bit of a mess, honestly. You can read more about [the difference between Windows High Contrast Mode and cross-browser Forced Colors mode in this Smashing Magazine article](https://www.smashingmagazine.com/2022/03/windows-high-contrast-colors-mode-css-custom-properties/#high-contrast-mode-forced-colors-mode-and-browser-support).

### I noticed that the colors in the Forced Color Mode screenshot don't all look like they have high enough contrast?

This is by design. These colors are dynamic, and can be adjusted by the person using the theme to make the experience work for their vision needs.

### Something strange is going on with inheriteance, can you help?

Check your Cascade Layer order. These themes use the `vendor-prism` and `vendor-highlight` namespaces, respectively.

### Will you consider supporting this service I use?

Possibly! [Raise an issue](https://github.com/ericwbailey/a11y-syntax-highlighting/issues/new) and let's talk about it.

### I don't like these colors, can you change them?

I'm not interested in that, but modifying the CSS Custom Property values is a good starting point. Just make sure to [check the foreground's color value against the background color value](https://webaim.org/resources/contrastchecker/) to make sure it passes level AA.


## Roadmap

- [CSS Highlights API](https://pavi2410.com/blog/high-performance-syntax-highlighting-with-css-highlights-api/)
- [Microsoft Visual Studio Code](https://code.visualstudio.com/)


## Used by

- [aaron-gustafson.com](https://www.aaron-gustafson.com/)
- [cssnano](https://cssnano.co/)
- [Eleventy](https://www.11ty.dev/docs/)
- [hidde.blog](https://hidde.blog/)
- [Kieran Barker](https://barker.codes/)
- [Mark Llobrera](https://markllobrera.com/)
- [Melanie Richards](https://melanie-richards.com/)
- [Oddbird CSS Sandbox](https://css.oddbird.net/)
- [Paul Kinchla](https://paulkinchla.com/blog/)
- [Quarto](https://quarto.org/docs/output-formats/html-code.html#highlighting)
- [Sarah Higley](https://sarahmhigley.com/writing/)
- [24 jours de web](https://www.24joursdeweb.fr/)
- [Zeroheight](https://zeroheight.com/)
- [W3C Design System](https://design-system.w3.org/)

Run across it being used elsewhere? [Let me know](https://ericwbailey.website#contact)!

## Thanks

- [Michael Ball](https://github.com/cycomachead), for the idea.
- [Scott Vinkle](https://github.com/svinkle), [Carie Fischer](https://github.com/cehfisher), and [Scott O'Hara](https://github.com/scottaohara) for the encouragement.
- [Aaron Gustafson](https://github.com/aarongustafson), for suggesting line highlighting support.
- [Reuben L. Lillie](https://reubenlillie.com/), for Vi/Vim support.
- [Elly Loel](https://www.ellyloel.com/), for the nudge to modernize the CSS.
- [Brandon Mathis](https://hslpicker.com/), for help with hex code color conversion.
