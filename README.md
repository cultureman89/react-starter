# React Starter

## Start your React Project with a ready config!

this is a sample of the ReactJs project for starting easily and fast.
<br/>
In this project, we added some configs and installed some necessary packages. they help you to ready very fast and don't waste time them.
<br />

## Contents

- [Configs](https://github.com/raminr77/react_sample#Configs)
- [Packages](https://github.com/raminr77/react_sample#Packages)
- [Hooks](https://github.com/raminr77/react_sample#Hooks)
- [Tools (utils)](https://github.com/raminr77/react_sample#tools-utils)
- [How To Run](https://github.com/raminr77/react_sample#how-to-run)
- [API Pattern](https://github.com/raminr77/react_sample#api-pattern)
- [You Can Use In This Project](https://github.com/raminr77/react_sample#you-can-use-in-this-project)

<br />
<hr />
<br />

- ## Hooks

  - useApi (for requests)
  - usePageData (for page requests)
  - useCopyToClipboard (for copy text)
  - useOnScreen (for traking an element on screen)

- ## Tools (utils)

  - Snackbar
  - `htmlDecode` function
  - URLs for share in social
  - `generateSnackbar` function
  - `apiRequestObject` for API pattern
  - `removeUndefinedFromObject` function
  - Log system (Empty function for your config)
  - `redirect` and `attachObjectQueriesToUrl` functions
  - `truncate` and `shouldTruncate` functions for your texts
  - `isDemo`, `isProduction`, `isDevelopment`, `appVersion` and `appName` variables
  - `faToEn`, `enToFa`, `arToFa`, `faPriceToEnNumber` and `formatPrice` functions for your numbers (persian language)

<br />

## You Can Use In This Project

- You can use the AnimateCSS framework for your animations, add the class `animate__animated` to an element, along with any of the animation names white the `animate__` prefix.

  `<h1 class="animate__animated animate__bounce">An animated element</h1>`

  REF: https://animate.style/

- You can use `Vazir` font in this project. for change `EN` to `FA` number with font, use `fa-num-font` and `fa-num-font-bold` class. also you can use `vazir-bold` for bold type.
- You can import file from `src` address like this:

  `import { INDEX_PAGE_ROUTE } from 'routes/RedirectRoutes';`

<br />

## How To Run

- First Git Clone Or Download Project
- Copy and rename `.env.example` to `.env`
- `npm install` or `yarn add`
- Just Run: `npm start`
- Run white style watching:
  - Windows: `npm run dev:windows`
  - Linux or MaxOs: `npm run dev`
