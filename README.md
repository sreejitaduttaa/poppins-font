# Inter Font

[`fifthtry.github.io/inter`](https://fifthtry.github.io/inter) is a wrapper over [Inter font](https://github.com/rsms/inter).

# How To Use This Font

include fifthtry.github.io/inter package into FPM.ftd file:

```ftd
-- fpm.dependency: fifthtry.github.io/inter

-- fpm.auto-import: fifthtry.github.io/inter as inter
```

Inside your .ftd file to change for any specific token use:

```ftd
-- fpm.type.headline-small.font: $inter.fonts.Inter

-- ftd.text:
role: $fpm.type.headline-small
```

[Details](the link to our new how to).

# License

[Inter is distributed under SIL OPEN FONT LICENSE Version 1.1](https://github.com/rsms/inter/blob/master/LICENSE.txt). We use the same license to be compatible with them.
