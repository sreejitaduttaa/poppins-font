# Poppins : FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Inter](https://fonts.google.com/specimen/Inter/about).

Inter is a variable font family carefully crafted & designed for computer screens.
Inter features a tall x-height to aid in readability of mixed-case and lower-case
text. Several OpenType features are provided as well, like contextual alternates 
that adjusts punctuation depending on the shape of surrounding glyphs, slashed 
zero for when you need to disambiguate "0" from "o", tabular numbers, et

Designers: Rasmus Andersson, Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://sreejitaduttaa.github.io/poppins-font/).

TLRD:

Include sreejitaduttaa.github.io/poppins-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: sreejitaduttaa.github.io/poppins-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: sreejitaduttaa.github.io/poppins-font/assets as poppins

;-- fpm.type.headline-small: $poppins.fonts.Poppins
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `Poppins` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Inter Font is under [Open Font Licence](https://fonts.google.com/specimen/Inter/about), this FPM wrapper is also
under [Open Font Licence](LICENSE).





