# Awesome Bundle Size [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> An awesome list of tools and techniques to make your web bundle size smaller and your web apps load faster.

## Contents

- [Concepts](#concepts)
  - [Code Splitting](#code-splitting)
  - [Tree Shaking](#tree-shaking)
- [Tools to analyze bundle size](#tools-to-analyze-bundle-size)
  - [General](#general)
  - [Webpack](#webpack)
- [Tools to analyze the cost of imports](#tools-to-analyze-the-cost-of-imports)
- [Tools to help with Code Splitting](#tools-to-help-with-code-splitting)
- [Bundle size optimization guides](#bundle-size-optimization-guides)
  - [CSS](#css)
  - [Tree Shaking](#tree-shaking-1)
  - [Webpack](#webpack-1)
  - [You Don't Need X](#you-dont-need-x)
- [Code Splitting](#code-splitting-1)
  - [Code Splitting guides](#code-splitting-guides)
  - [Documentation for bundlers and libraries](#documentation-for-bundlers-and-libraries)
- [Videos and talks](#videos-and-talks)
  - [Bundle size](#bundle-size)
  - [Code Splitting](#code-splitting-2)
  - [Tree Shaking](#tree-shaking-2)
  - [Webpack](#webpack-2)

## Concepts

### Code Splitting

> Code-splitting your app can help you “lazy-load” just the things that are currently needed by the user, which can dramatically improve the performance of your app. While you haven’t reduced the overall amount of code in your app, you’ve avoided loading code that the user may never need, and reduced the amount of code needed during the initial load.

_Source: https://reactjs.org/docs/code-splitting.html_

### Tree Shaking

> Tree shaking is a term commonly used in the JavaScript context for dead-code elimination. It relies on the static structure of ES2015 module syntax, i.e. import and export. The name and concept have been popularized by the ES2015 module bundler rollup.

_Source: https://webpack.js.org/guides/tree-shaking_

## Tools to analyze bundle size

### General

- [source-map-explorer](https://github.com/danvk/source-map-explorer) - Analyze and debug space usage through source maps.

### Webpack

- [Webpack Bundle Analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) - Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap.
- [Webpack Bundle Size Analyzer](https://github.com/robertknight/webpack-bundle-size-analyzer) - A tool for finding out what contributes to the size of Webpack bundles.
- [size-plugin](https://github.com/GoogleChromeLabs/size-plugin) - Track compressed Webpack asset sizes over time.
- [Webpack Monitor](https://github.com/webpackmonitor/webpackmonitor) - A tool for monitoring webpack optimization metrics through the development process.

## Tools to analyze the cost of imports

- [bundlephobia](https://bundlephobia.com) - Find out the cost of adding a new frontend dependency to your project.
- [Import Cost](https://github.com/wix/import-cost) - Displays the import size of the package you are importing inside the code editor.

## Tools to help with Code Splitting

- [Bundle Buddy](https://github.com/samccone/bundle-buddy) - A tool to identify bundle duplication across splits.

## Bundle size optimization guides

### CSS

- [Reducing CSS bundle size 70% by cutting the class names and using scope isolation](https://medium.freecodecamp.org/reducing-css-bundle-size-70-by-cutting-the-class-names-and-using-scope-isolation-625440de600b)

### Lodash

- [Smaller Lodash bundles with Webpack and Babel](https://nolanlawson.com/2018/03/20/smaller-lodash-bundles-with-webpack-and-babel/)

### Tree Shaking

- [Reduce JavaScript Payloads with Tree Shaking](https://developers.google.com/web/fundamentals/performance/optimizing-javascript/tree-shaking/)
- [Webpack - Tree Shaking](https://webpack.js.org/guides/tree-shaking/)

### Webpack

- [Optimising your application bundle size with webpack](https://hackernoon.com/optimising-your-application-bundle-size-with-webpack-e85b00bab579)
- [How I Cut My React JavaScript Bundle Size In Half With Three Lines of Code](https://codeburst.io/how-i-cut-my-react-javascript-bundle-size-in-half-with-three-lines-of-code-fe7798ecbd3f)
- [Webpack: Optimizing Your Bundle Size](https://medium.com/@arturarsalanov/webpack-optimizing-your-bundle-size-ab0c90b1bf03)
- [Here’s how I reduced my bundle size by 90%](https://medium.com/@poshakajay/heres-how-i-reduced-my-bundle-size-by-90-2e14c8a11c11)
- [Optimizing Bundle size Webpack](https://medium.com/@tkssharma/optimizing-bundle-size-webpack-ab4efdfc1d15)
- [Put Your Webpack Bundle On A Diet - Part 1](https://www.contentful.com/blog/2017/10/10/put-your-webpack-on-a-diet-part-1/)
- [Put Your Webpack Bundle On A Diet - Part 2](https://www.contentful.com/blog/2017/10/19/put-your-webpack-bundle-on-a-diet-part-2/)
- [Put Your Webpack Bundle On A Diet - Part 3](https://www.contentful.com/blog/2017/10/27/put-your-webpack-bundle-on-a-diet-part-3/)

### You Don't Need X

- [You don't (may not) need Lodash/Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore)
- [You don't (may not) need Moment.js](https://github.com/you-dont-need/You-Dont-Need-Momentjs)
- [You Might Not Need jQuery](http://youmightnotneedjquery.com/)

## Code Splitting

### Code Splitting guides

- [Reduce JavaScript Payloads with Code Splitting](https://developers.google.com/web/fundamentals/performance/optimizing-javascript/code-splitting/)
- [Effective Code Splitting in React: A Practical Guide](https://hackernoon.com/effective-code-splitting-in-react-a-practical-guide-2195359d5d49)
- [Lessons Learned: Code Splitting with Webpack and React](https://hackernoon.com/effective-code-splitting-in-react-a-practical-guide-2195359d5d49)
- [Avoid this gotcha when code-splitting with TypeScript and Webpack](https://davidea.st/articles/webpack-typescript-code-split-wont-work)

### Documentation for bundlers and libraries

- [Webpack - Code Splitting](https://webpack.js.org/guides/code-splitting/)
- [Parcel - Code Splitting](https://parceljs.org/code_splitting.html)
- [React - Code-Splitting](https://reactjs.org/docs/code-splitting.html)

## Videos and talks

### Bundle size

- [Managing Your Bundle Size - Totally Tooling Tips](https://www.youtube.com/watch?v=Da6VxdGU2Ig)

### Code Splitting

- [Code-splitting your way to better perf with Webpack in Totally Tooling Tips](https://www.youtube.com/watch?v=QH94CXVv3UE)
- [Neehar Venugopal - A Beginner's Guide to Code Splitting Your React App - React Conf 2017](https://www.youtube.com/watch?v=bb6RCrDaxhw)

### Tree Shaking

- [Let's Tree-Shake It... (aka Demystifying Tree-Shaking and Dead Code Elimination)](https://www.youtube.com/watch?v=LVKSpYhkgKs)

### Webpack

- [Webpack Tips - Totally Tooling Tips](https://www.youtube.com/watch?v=zFoBYfMLUCM)
- [How to use Webpack Bundle Analyzer](https://www.youtube.com/watch?v=ltlxjq4YEKU)
- [Minimizing Bundle Sizes in React](https://www.youtube.com/watch?v=geHEm6Hn_2c)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
