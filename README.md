# 2014

Zen-based Drupal theme (2014 design) for RSC websites: Base theme
Subtheme of `Zen-7.x-5.6`.

## Compiling

`compass _0.12.6_ watch`

or

`compass _0.12.6_ compile`

## Theme flavours
Different parts of the website use different color schemes and layouts. For this, there are three scss files:

- base.scss
- lib.scss (used at www.christianstudylibrary.org )
- pl.scss (used at www.christianstudylibrary.org/pl )

template.php contains some logic to decide which flavour should be used.

