# Bicento UIkit fork from Pancake UIKit

**This repository is not used anymore. See the [https://github.com/bicento/bicento-toolkit](Bicento toolkit) instead**

Bicento UIkit is a set of React components and hooks used to build pages on Bicento apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @bicento-libs/uikit`

## Setup

### Theme

Before using Bicento UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@bicento-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@bicento-libs/uikit'
...
<ResetCSS />
```


