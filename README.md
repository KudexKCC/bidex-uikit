# 💻 Bidex UIkit

[![Version](https://img.shields.io/npm/v/@kudexkcc/bidex-uikit)](https://www.npmjs.com/package/@kudexkcc/bidex-uikit) [![Size](https://img.shields.io/bundlephobia/min/@kudexkcc/bidex-uikit)](https://www.npmjs.com/package/@kudexkcc/bidex-uikit)

Bidex UIkit is a set of React components and hooks used to build pages on Bidex's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @kudexkcc/bidex-uikit`

## Setup

### Theme

Before using Bidex UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@kudexkcc/bidex-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@kudexkcc/bidex-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://pancakeswap.github.io/pancake-uikit/)
