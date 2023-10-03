# bun-bugs

`8.4.21` should satisfy `postcss@~8.4.21` so why is it using `version "8.4.31"`

```
postcss@8.4.21:
  version "8.4.21"
  resolved "https://registry.npmjs.org/postcss/-/postcss-8.4.21.tgz"
  integrity sha512-tP7u/Sn/dVxK2NnruI4H9BG+x+Wxz6oeZ1cJ8P6G/PZY0IKk4k/63TDsQf2kQq3+qoJeLm2kIBUNlZe3zgb4Zg==
  dependencies:
    nanoid "^3.3.4"
    picocolors "^1.0.0"
    source-map-js "^1.0.2"

postcss@~8.4.21:
  version "8.4.31"
  resolved "https://registry.npmjs.org/postcss/-/postcss-8.4.31.tgz"
  integrity sha512-PS08Iboia9mts/2ygV3eLpY5ghnUcfLV/EXTOW1E2qYxJKGGBUtNjN76FYHnMs36RmARn41bC0AZmn+rR0OVpQ==
  dependencies:
    nanoid "^3.3.6"
    picocolors "^1.0.0"
    source-map-js "^1.0.2"
```