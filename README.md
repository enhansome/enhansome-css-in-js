# Awesome CSS in JS with stars

A collection of awesome things regarding to CSS in JS approach

[中文 README](README-ZH_CN.md)

## Table of Contents

* [Libraries](#libraries)
* [Articles](#articles)
* [Videos](#videos)
* [Benchmarks](#benchmarks)

## Libraries

* [styled-components](https://github.com/styled-components/styled-components) ⭐ 41,124 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-17 - Universal, Dynamic & High-Performance Styling in JavaScript
* [linaria](https://github.com/callstack/linaria) ⭐ 12,345 | 🐛 72 | 🌐 TypeScript | 📅 2026-08-10 - Zero-runtime CSS in JS library
* [styled-jsx](https://github.com/zeit/styled-jsx) ⭐ 7,777 | 🐛 83 | 🌐 JavaScript | 📅 2026-06-09 - Full CSS support for JSX without compromises
* [radium](https://github.com/FormidableLabs/radium) ⚠️ Archived - Set of tools to manage inline styles on React elements.
* [jss](https://github.com/cssinjs/jss) ⭐ 7,056 | 🐛 225 | 🌐 JavaScript | 📅 2024-08-13 - JSS is a CSS authoring tool which uses JavaScript as a host language
* [aphrodite](https://github.com/Khan/aphrodite) ⭐ 5,339 | 🐛 91 | 🌐 JavaScript | 📅 2025-07-24 - It's inline styles, but they work! Also supports styling via CSS
* [glamor](https://github.com/threepointone/glamor) ⭐ 3,668 | 🐛 73 | 🌐 JavaScript | 📅 2023-12-21 - css in your javascript
* [glamorous](https://github.com/paypal/glamorous) ⚠️ Archived - React component styling solved with an elegant API, small footprint, and great performance (via glamor)
* [styletron](https://github.com/rtsao/styletron) ⭐ 3,309 | 🐛 36 | 🌐 TypeScript | 📅 2023-12-22 - ⚡️ Universal, high-performance JavaScript styles
* [fela](https://github.com/rofrischmann/fela/) ⭐ 2,284 | 🐛 8 | 🌐 JavaScript | 📅 2024-11-06 - Universal, Dynamic & High-Performance Styling in JavaScript
* [csx](https://github.com/jxnblk/cxs) ⭐ 1,182 | 🐛 45 | 🌐 JavaScript | 📅 2022-12-08 - ϟ A CSS-in-JS solution for functional CSS in functional UI components
* [glam](https://github.com/threepointone/glam) ⭐ 509 | 🐛 13 | 🌐 JavaScript | 📅 2018-04-25 - crazy good css in your js
* [freestyler](https://github.com/streamich/freestyler) ⭐ 271 | 🐛 13 | 🌐 TypeScript | 📅 2026-02-07 - 5<sup>th</sup> generation React styling library
* [styled-jss](https://github.com/cssinjs/styled-jss) ⭐ 214 | 🐛 20 | 🌐 JavaScript | 📅 2018-12-31 - Styled Components on top of JSS
* [aesthetic](https://github.com/milesj/aesthetic) ⭐ 208 | 🐛 0 | 🌐 TypeScript | 📅 2021-07-21 - Aesthetic is a powerful React library for styling components, whether it be CSS-in-JS using objects, importing stylesheets, or simply referencing external class names.
* [j2c](https://github.com/j2css/j2c) ⭐ 165 | 🐛 9 | 🌐 JavaScript | 📅 2019-10-22 - CSS in JS library, tiny yet featureful
* [rockey](https://github.com/tuchk4/rockey) ⭐ 99 | 🐛 3 | 🌐 JavaScript | 📅 2019-02-15 - Stressless CSS for components using JS. Write Component Based CSS with functional mixins.
* [emotion](https://emotion.sh/) - 👩‍🎤 The Next Generation of CSS-in-JS
* [react-jss](https://github.com/cssinjs/react-jss) - JSS integration for React

> NOTE table is still not completed. If there is bug or need to add another library - please suggest PR.

How to read the table:

**As Object** - When declare CSS using Objects.

```js
{
  color: 'red',
}
```

**As TL** - When declare CSS using Template Literals.

```js
`
  color: red;
`
```

**SSR** - Server Side Rendering.

**RN Support** - React Native support.

**Agnostic** - Framework agnostic. Means that library could used with any framework.

**Dynamic** - When it is possible to write CSS that depends on runtime values like component props.

```js
{
  color: props =>  props.color
}
```

```js
props => ({
  color: props.color
})
```

```js
`
  color: ${props => props.color}
`
```

**Babel plugins** - If there are any babel plugins for performance optimization.

**Bindings** - If there are packages that provide bindings for another framework or library.

|                                                             Package                                                             | As Object | As TL | SSR | RN Support | Agnostic | Dynamic | Babel plugins | Bindings                                                                                                                                                                                                                                                                         |   |
| :-----------------------------------------------------------------------------------------------------------------------------: | :-------: | :---: | :-: | ---------- | -------- | ------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
|              [emotion](https://github.com/emotion-js/emotion) ⭐ 18,017 \| 🐛 392 \| 🌐 JavaScript \| 📅 2026-08-26              |     ✅     |   ✅   |  ✅  | ✅          | ✅        | ✅       | ✅             | react-emotion, preact-emotion                                                                                                                                                                                                                                                    |   |
|                 [fela](https://github.com/rofrischmann/fela/) ⭐ 2,284 \| 🐛 8 \| 🌐 JavaScript \| 📅 2024-11-06                 |     ✅     |       |  ✅  | ✅          | ✅        | ✅       |               | [react-fela](http://fela.js.org/docs/guides/UsageWithReact.html) [native-fela](http://fela.js.org/docs/guides/UsageWithReactNative.html) [preact-fela](http://fela.js.org/docs/guides/UsageWithPreact.html) [inferno-fela](http://fela.js.org/docs/guides/UsageWithInferno.html) |   |
|                    [jss](https://github.com/cssinjs/jss) ⭐ 7,056 \| 🐛 225 \| 🌐 JavaScript \| 📅 2024-08-13                    |     ✅     |   ✅   |  ✅  |            | ✅        | ✅       | ✅             | [react-jss](https://github.com/cssinjs/react-jss) [styled-jss](https://github.com/cssinjs/styled-jss) ⭐ 214 \| 🐛 20 \| 🌐 JavaScript \| 📅 2018-12-31                                                                                                                           |   |
|                    [rockey](https://github.com/tuchk4/rockey) ⭐ 99 \| 🐛 3 \| 🌐 JavaScript \| 📅 2019-02-15                    |           |   ✅   |     |            | ✅        | ✅       |               | [rockey-react](https://github.com/tuchk4/rockey/tree/master/packages/rockey-react) ⭐ 99 \| 🐛 3 \| 🌐 JavaScript \| 📅 2019-02-15                                                                                                                                                |   |
| [styled-components](https://github.com/styled-components/styled-components) ⭐ 41,124 \| 🐛 19 \| 🌐 TypeScript \| 📅 2026-08-17 |           |   ✅   |  ✅  | ✅          |          | ✅       | ✅             |                                                                                                                                                                                                                                                                                  |   |
|                [aphrodite](https://github.com/Khan/aphrodite) ⭐ 5,339 \| 🐛 91 \| 🌐 JavaScript \| 📅 2025-07-24                |     ✅     |       |  ✅  |            | ✅        |         |               |                                                                                                                                                                                                                                                                                  |   |
|                     [csx](https://github.com/jxnblk/cxs) ⭐ 1,182 \| 🐛 45 \| 🌐 JavaScript \| 📅 2022-12-08                     |     ✅     |       |  ✅  |            | ✅        |         |               |                                                                                                                                                                                                                                                                                  |   |
|                  [glam](https://github.com/threepointone/glam) ⭐ 509 \| 🐛 13 \| 🌐 JavaScript \| 📅 2018-04-25                 |     ✅     |       |  ✅  |            | ✅        |         | ✅             |                                                                                                                                                                                                                                                                                  |   |
|               [glamor](https://github.com/threepointone/glamor) ⭐ 3,668 \| 🐛 73 \| 🌐 JavaScript \| 📅 2023-12-21              |     ✅     |       |  ✅  |            | ✅        |         | ✅             |                                                                                                                                                                                                                                                                                  |   |
|                                   [glamorous](https://github.com/paypal/glamorous) ⚠️ Archived                                  |     ✅     |       |  ✅  | ✅          |          | ✅       |               |                                                                                                                                                                                                                                                                                  |   |
|                [styletron](https://github.com/rtsao/styletron) ⭐ 3,309 \| 🐛 36 \| 🌐 TypeScript \| 📅 2023-12-22               |     ✅     |       |  ✅  |            | ✅        | ✅       |               | [styletron-react](https://github.com/rtsao/styletron#using-styletron-with-react) ⭐ 3,309 \| 🐛 36 \| 🌐 TypeScript \| 📅 2023-12-22                                                                                                                                              |   |
|                 [aesthetic](https://github.com/milesj/aesthetic) ⭐ 208 \| 🐛 0 \| 🌐 TypeScript \| 📅 2021-07-21                |     ✅     |       |     |            | ✅        |         |               |                                                                                                                                                                                                                                                                                  |   |
|                       [j2c](https://github.com/j2css/j2c) ⭐ 165 \| 🐛 9 \| 🌐 JavaScript \| 📅 2019-10-22                       |     ✅     |       |  ✅  |            | ✅        |         |               |                                                                                                                                                                                                                                                                                  |   |

## Articles

* [A Unified Styling Language](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660) - why writing your styles in JavaScript isn’t such a terrible idea after all, and why I think you should be keeping an eye on this rapidly evolving space.
* [Is CSS-in-JS really bad for UX?](https://medium.com/@okonetchnikov/is-css-in-js-really-bad-for-ux-e9cce7b2da83) - CSS in JS performance implications - JS developers are too focused on DX and keep forgetting about how important performance for UX is.
* [I swore never to use CSS in JS, here are 6 reasons why I was wrong](https://hackernoon.com/i-swore-never-to-use-css-in-js-here-are-6-reasons-why-i-was-wrong-541fe3dfdeb7)- *"When I first heard of this idea, I was shocked..."* But here are 6 reasons why it is useful.
* [Journey to Enjoyable, Maintainable Styling with React, ITCSS, and CSS-in-JS](https://medium.com/maintainable-react-apps/journey-to-enjoyable-maintainable-styling-with-react-itcss-and-css-in-js-632cfa9c70d6) - Making Styling Better With better CSS / with Components / with JavaScript and final approach with ITCSS and Aphrodite
* [Rockey. Motivation and Requirements](https://medium.com/@tuchk4/rockey-motivation-and-requirements-f787d1ed61e0) - Article about requirements for CSS in JS approach and motivation to develop another one CSS in JS library - rockey.
* [CSS in JS: The Argument Refined](https://medium.com/@steida/css-in-js-the-argument-refined-471c7eb83955)
* [Inline Styles are so 2016](https://medium.com/yplan-eng/inline-styles-are-so-2016-f100b79dafe1)
* [“Scale” FUD and Style Components](https://medium.learnreact.com/scale-fud-and-style-components-c0ce87ec9772)
* [JSS is a better abstraction over CSS](https://top.fse.guru/jss-is-css-d7d41400b635)
* [A 5-minute Intro to Styled Components](https://medium.freecodecamp.com/a-5-minute-intro-to-styled-components-41f40eb7cd55)
* [Styled Components: Enforcing Best Practices In Component-Based Systems](https://www.smashingmagazine.com/2017/01/styled-components-enforcing-best-practices-component-based-systems/)
* [💅 styled components 💅 — Production Patterns](https://medium.com/@jamiedixon/styled-components-production-patterns-c22e24b1d896)
* [Introducing glamorous 💄](https://hackernoon.com/introducing-glamorous-fb3c9f4ed20e)

## Videos

* [Styling React/ReactNative Applications - Max Stoiber at React Amsterdam](https://www.youtube.com/watch?v=bIK2NwoK9xk)
* [CSS in JS tech chat with Kent C. Dodds and Sarah Drasner](https://www.youtube.com/watch?v=BXOF_8jDdf8)
* [CSS in JS without Compromise by François de Campredon at react-europe 2016](https://www.youtube.com/watch?v=DGEFNBYJRps)
* [Glamorous Walkthrough by Kent C. Dodds](https://www.youtube.com/watch?v=lmrQTpJ_3PM)
* [ColdFront16 • Glenn Maddern: The Future of Reusable CSS](https://www.youtube.com/watch?v=XR6eM_5pAb0)
* [Ryan's Random Thoughts on Inline Styles by Ryan Florence](https://www.youtube.com/watch?v=EkPcGS4TzdQ)
* [CSS in JavaScript](https://www.manning.com/livevideo/css-in-javascript-with-styled-components-and-react)

## Benchmarks and comparison

* [MicheleBertoli/css-in-js](https://github.com/MicheleBertoli/css-in-js) ⭐ 5,476 | 🐛 6 | 🌐 JavaScript | 📅 2024-04-02 React: CSS in JS techniques comparison.
* [A-gambit/CSS-IN-JS-Benchmarks](https://github.com/A-gambit/CSS-IN-JS-Benchmarks) ⭐ 381 | 🐛 47 | 🌐 JavaScript | 📅 2023-01-12 [RESULTS.md](https://github.com/A-gambit/CSS-IN-JS-Benchmarks/blob/master/RESULT.md) ⭐ 381 | 🐛 47 | 🌐 JavaScript | 📅 2023-01-12
* [tuchk4/css-in-js-app](https://github.com/tuchk4/css-in-js-app) ⭐ 43 | 🐛 2 | 🌐 JavaScript | 📅 2018-07-03 - React application with different css-in-js approaches and libraries.
* [hellofresh/css-in-js-perf-tests](https://github.com/hellofresh/css-in-js-perf-tests) - CSS-in-JS performance tests
* [jsperf: jss-vs-css](https://jsperf.com/jss-vs-css/3)
* [jsperf: classes vs inline styles](https://jsperf.com/classes-vs-inline-styles/4)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
