# a11y-syntax-highlighting

Accessible light and dark syntax highlighting themes.

## Support

### Libraries

- [Highlight.js](https://highlightjs.org/)
- [Prism.js](http://prismjs.com/)
    - [Line Highlight](https://prismjs.com/plugins/line-highlight/)
    - [Line Numbers](https://prismjs.com/plugins/line-numbers/)

### Applications

- [Adobe](https://helpx.adobe.com/illustrator/using/using-creating-swatches.html)
- [Figma](https://www.figma.com/) (drag SVGs onto your canvas)
- [macOS](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/DrawColor/Concepts/AboutColorLists.html)
- [Sketch](https://www.sketchapp.com/) (uses the [Sketch Palettes plugin](https://github.com/andrewfiorillo/sketch-palettes))

### Misc

- [Carbon](https://carbon.now.sh/?bg=rgba(171%2C%20184%2C%20195%2C%201)&t=a11y-dark&wt=none&l=auto&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false) (remember to include alt text with your image!)
- [JSON](https://www.json.org/)

### Roadmap

- Editors
    - [Microsoft Visual Studio Code](https://code.visualstudio.com/)
    - [Sublime Text](https://www.sublimetext.com/)
    - [Vi/Vim](http://www.vim.org/)


## Themes

### a11y-dark

![The a11y-dark theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-dark.png)

- Light text on a dark background.
- Background color of `#2b2b2b`.
- [WCAG AAA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| [Bright Turquoise](http://chir.ag/projects/name-that-color/#00E0E0) | `#00e0e0` | [8.59:1](https://webaim.org/resources/contrastchecker/?fcolor=00E0E0&bcolor=2B2B2B) | AAA | AAA |
| [Chino](http://chir.ag/projects/name-that-color/#D4D0AB) | `#d4d0ab` | [9.04:1](https://webaim.org/resources/contrastchecker/?fcolor=D4D0AB&bcolor=2B2B2B) | AAA | AAA |
| [Conifer](http://chir.ag/projects/name-that-color/#ABE338) | `#abe338` | [9.29:1](https://webaim.org/resources/contrastchecker/?fcolor=ABE338&bcolor=2B2B2B) | AAA | AAA |
| [Gold](http://chir.ag/projects/name-that-color/#FFD700) | `#ffd700` | [10.09:1](https://webaim.org/resources/contrastchecker/?fcolor=FFD700&bcolor=2B2B2B) | AAA | AAA |
| [Snuff](http://chir.ag/projects/name-that-color/#DCC6E0) | `#dcc6e0` | [8.90:1](https://webaim.org/resources/contrastchecker/?fcolor=DCC6E0&bcolor=2B2B2B) | AAA | AAA |
| [Spring Wood](http://chir.ag/projects/name-that-color/#F8F8F2) | `#f8f8f2` | [13.28:1](https://webaim.org/resources/contrastchecker/?fcolor=F8F8F2&bcolor=2B2B2B) | AAA | AAA |
| [Vivid Tangerine](http://chir.ag/projects/name-that-color/#FFA07A) | `#ffa07a` | [7.12:1](https://webaim.org/resources/contrastchecker/?fcolor=FFA07A&bcolor=2B2B2B) | AAA | AAA |


### a11y-light

![The a11y-light theme being applied to the HTML of the Prism.js website. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-light.png)

- Dark text on a light background.
- Background color of `#fefefe`.
- [WCAG AA compliant](https://www.w3.org/TR/WCAG/#visual-audio-contrast-contrast) for color contrast. WCAG AAA compliance forces the values on a light background to be too similar to each other to be used effectively for syntax highlighting.

| Color | Hex | Ratio | Normal Text | Large Text |
| :---- | :-- | ----: | :---------- | :--------- |
| [Chelsea Gem](http://chir.ag/projects/name-that-color/#AA5D00) | `#aa5d00` | [4.87:1](d) | AA | AAA |
| [Allports](http://chir.ag/projects/name-that-color/#007299) | `#007299` | [4.51:1](https://webaim.org/resources/contrastchecker/?fcolor=007299&bcolor=FEFEFE) | AA | AAA |
| [Dove Gray](http://chir.ag/projects/name-that-color/#696969) | `#696969` | [5.44:1](https://webaim.org/resources/contrastchecker/?fcolor=696969&bcolor=FEFEFE) | AA | AAA |
| [Emperor](http://chir.ag/projects/name-that-color/#545454) | `#545454` | [7.51:1](https://webaim.org/resources/contrastchecker/?fcolor=545454&bcolor=FEFEFE) | AAA | AAA |
| [Japanese Laurel](http://chir.ag/projects/name-that-color/#008000) | `#008000` | [5.09:1](https://webaim.org/resources/contrastchecker/?fcolor=008000&bcolor=FEFEFE) | AA | AAA |
| [Thunderbird](http://chir.ag/projects/name-that-color/#D91E18) | `#d91e18` | [5.02:1](https://webaim.org/resources/contrastchecker/?fcolor=D91E18&bcolor=FEFEFE) | AA | AAA |


### High Contrast Mode

Both themes have enhanced support for [Windows High Contrast Mode](https://support.microsoft.com/en-us/help/13862/windows-use-high-contrast-mode) when possible:

![The a11y-dark theme responding to Windows High Contrast Mode. Screenshot.](https://raw.githubusercontent.com/ericwbailey/a11y-prism-theme/master/images/a11y-high-contrast-mode.png)

## Used by

- [Eleventy](https://www.11ty.dev/docs/)
- [Melanie Richards](https://melanie-richards.com/)
- [Paul Kinchla](https://paulkinchla.com/blog/)
- [Sarah Higley](https://sarahmhigley.com/writing/)
- [Quarto](https://quarto.org/docs/output-formats/html-code.html#highlighting)
- [W3C Design System](https://design-system.w3.org/)
- [aaron-gustafson.com](https://www.aaron-gustafson.com/)
- [hidde.blog](https://hidde.blog/)
- [Oddbird CSS Sandbox](https://css.oddbird.net/)
- [cssnano](https://cssnano.co/)
- [Mark Llobrera](https://markllobrera.com/)
- [Kieran Barker](https://barker.codes/)

Run across it being used elsewhere? [Let me know](https://ericwbailey.website#contact)!

## Thanks

- [Michael Ball](https://github.com/cycomachead), for the idea.
- [Scott Vinkle](https://github.com/svinkle), [Carie Fischer](https://github.com/cehfisher), and [Scott O'Hara](https://github.com/scottaohara) for the encouragement.
- [Aaron Gustafson](https://github.com/aarongustafson), for suggesting line highlighting support.
- [Reuben L. Lillie](https://reubenlillie.com/), for Vi/Vim support.
