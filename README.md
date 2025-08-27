# TBK Mini Corne Layout

![build workflow](https://github.com/Kirschluft/zmk-tbk-mini/actions/workflows/build.yaml/badge.svg) ![image workflow](https://github.com/Kirschluft/zmk-tbk-mini/actions/workflows/image.yaml/badge.svg)

![zmk](https://github.com/zmkfirmware/zmk) config customized for German writing on the ![TBK Mini](https://github.com/Bastardkb/TBK-Mini?tab=readme-ov-file) with 42 keys.

## Notes

Works best with the "US (intl) with AltGr dead keys" layout, e.g. setting the following in a sway config:

```
input * {
    xkb_layout us
    xkb_variant intl
}
```

The layout was initially adapted from ![Miryoku](https://github.com/manna-harbour/miryoku) and automatic keymap visualizations were created by ![sevenautumns](https://github.com/sevenautumns/zmk-6x3-3).

## Keymap

![Keymap Layout](keymap.svg)

