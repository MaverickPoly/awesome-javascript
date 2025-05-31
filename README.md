# Awesome JavaScript

A curated list of awesome JavaScript frameworks, libraries, tools, and resources, focusing on modern and actively maintained projects across various domains.

## Contents

- [Frontend Frameworks & Libraries](#frontend-frameworks--libraries)
- [State Management](#state-management)
- [Build Tools & Bundlers](#build-tools--bundlers)
- [Testing](#testing)
- [Backend (Node.js)](#backend-nodejs)
- [Mobile Development](#mobile-development)
- [Desktop Development](#desktop-development)
- [Game Development](#game-development)
- [Data Visualization](#data-visualization)
- [UI Components & Toolkits](#ui-components--toolkits)
- [DOM Manipulation](#dom-manipulation)
- [Utility Libraries](#utility-libraries)
  - [General Utilities](#general-utilities)
  - [File & Content Handling](#file--content-handling)
  - [Image Manipulation](#image-manipulation)
  - [Audio Processing](#audio-processing)
  - [Video Processing & Players](#video-processing--players)
- [Templating Engines](#templating-engines)
- [Static Site Generators](#static-site-generators)
- [Package Managers](#package-managers)
- [Type Checking](#type-checking)
- [Code Quality & Formatting](#code-quality--formatting)
- [Code Editors (Embeddable/JS-based)](#code-editors-embeddablejs-based)
- [Learning Resources](#learning-resources)
- [Awesome Resources & Communities](#awesome-resources--communities)
- [Contributing](#contributing)
- [License](#license)

---

## Frontend Frameworks & Libraries

- **[React](https://react.dev/)**: A JavaScript library for building user interfaces, maintained by Meta and a community of individual developers and companies. Known for its component-based architecture and virtual DOM.
- **[Vue.js](https://vuejs.org/)**: An approachable, performant, and versatile framework for building web user interfaces. It's progressive, meaning you can adopt it incrementally.
- **[Angular](https://angular.io/)**: A platform and framework for building single-page client applications using HTML and TypeScript. Developed by Google, it offers a comprehensive ecosystem.
- **[Svelte](https://svelte.dev/)**: A radical new approach to building user interfaces. Whereas traditional frameworks do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.
- **[Lit](https://lit.dev/)**: A simple library for building fast, lightweight web components. It provides reactive templates and a small footprint.
- **[Ember JS](https://emberjs.com/)**: a productive, battle-tested JavaScript framework for building modern web applications. It includes everything you need to build rich UIs that work on any device.
- **[Solid JS](https://www.solidjs.com/)**: It emphasizes performance by compiling templates into real DOM nodes and updating them with fine-grained reactions, rather than using a Virtual DOM.

## State Management

- **[Redux](https://redux.js.org/)**: A predictable state container for JavaScript apps. It helps you write applications that behave consistently across different environments (client, server, and native), and are easy to test.
- **[Zustand](https://zustand-demo.pmnd.rs/)**: A small, fast, and scalable bearbones state-management solution using a simplified flux-like architecture.
- **[Recoil](https://recoiljs.org/)**: An experimental state management library for React apps, providing a powerful and flexible way to manage shared state. Developed by Facebook.
- **[MobX](https://mobx.js.org/)**: Simple, scalable state management. It makes state management simple and scalable by transparently applying functional reactive programming (TFRP).

## Build Tools & Bundlers

- **[Webpack](https://webpack.js.org/)**: A static module bundler for modern JavaScript applications. It processes your application's modules into one or more bundles.
- **[Vite](https://vitejs.dev/)**: A next-generation frontend tooling that provides a significantly faster and leaner development experience for modern web projects.
- **[Rollup](https://rollupjs.org/)**: A module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application.
- **[Parcel](https://parceljs.org/)**: A blazing fast, zero configuration web application bundler. It aims to make web development faster and easier.
- **[Babel](https://babeljs.io/)**: A JavaScript compiler that transforms ECMAScript 2015+ code into a backward compatible version of JavaScript in current and older browsers or environments.

## Testing

- **[Jest](https://jestjs.io/)**: A delightful JavaScript Testing Framework with a focus on simplicity. Used by Facebook for testing all JavaScript code including React applications.
- **[React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)**: A set of utilities for testing React components. Its guiding principle is to help you write tests that resemble how your users interact with your app.
- **[Cypress](https://www.cypress.io/)**: A fast, easy, and reliable testing for anything that runs in a browser. It's an end-to-end testing framework.
- **[Playwright](https://playwright.dev/)**: A Node.js library to automate Chromium, Firefox and WebKit with a single API. Enables reliable end-to-end testing.
- **[Mocha](https://mochajs.org/)**: A feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun.
- **[Chai](https://www.chaijs.com/)**: A BDD / TDD assertion library for Node.js and the browser that can be paired with any JavaScript testing framework.

## Backend (Node.js)

- **[Express](https://expressjs.com/)**: A fast, unopinionated, minimalist web framework for Node.js. It's a popular choice for building RESTful APIs and web applications.
- **[NestJS](https://nestjs.com/)**: A progressive Node.js framework for building efficient, reliable, and scalable server-side applications. It uses TypeScript and combines elements of OOP, FP, and FRP.
- **[Koa](https://koajs.com/)**: A new web framework designed by the team behind Express, aiming to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- **[Fastify](https://www.fastify.io/)**: A fast and low-overhead web framework for Node.js, designed to be highly performant and extensible.
- **[Next.js](https://nextjs.org/)**: (Also a Frontend Framework) A React framework for building full-stack web applications. Enables server-side rendering (SSR), static site generation (SSG), and API routes.

## Mobile Development

- **[React Native](https://reactnative.dev/)**: A framework for building native mobile apps using React. Allows you to write cross-platform mobile applications with JavaScript.
- **[NativeScript](https://nativescript.org/)**: An open-source framework for building native apps with JavaScript, TypeScript, or Angular.
- **[Ionic](https://ionicframework.com/)**: An open-source mobile toolkit for building high-quality, cross-platform native and web app experiences.

## Desktop Development

- **[Electron](https://www.electronjs.org/)**: A framework for building cross-platform desktop applications with web technologies (HTML, CSS, and JavaScript).
- **[NW.js (formerly Node-Webkit)](https://nwjs.io/)**: An app runtime based on Chromium and Node.js. You can write native apps in HTML, CSS, and JavaScript directly.
- **[Tauri](https://tauri.app/)**: Build smaller, faster, and more secure desktop applications with a web frontend. Uses Rust for the backend, but the UI is web-based.

## Game Development

- **[Phaser](https://phaser.io/)**: A fast, free, and fun open source HTML5 game framework that offers WebGL and Canvas rendering across desktop and mobile web browsers.
- **[PixiJS](https://pixijs.com/)**: A fast and flexible 2D WebGL renderer that allows you to create rich, interactive graphics, cross-platform applications, and games without messing with the WebGL API.
- **[Babylon.js](https://www.babylonjs.com/)**: A powerful, beautiful, simple, and open game and rendering engine packed into a friendly JavaScript framework.
- **[Three.js](https://threejs.org/)**: (Also in Data Visualization) A versatile 3D library that can be used to create and display animated 3D computer graphics in a web browser, suitable for games and complex visualizations.
- **[PlayCanvas](https://playcanvas.com/)**: An open-source 3D game engine/interactive 3D application engine alongside a proprietary cloud-hosted creation platform that allows for real-time collaboration.

## Data Visualization

- **[D3.js](https://d3js.org/)**: A JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS.
- **[Chart.js](https://www.chartjs.org/)**: Simple, clean, and engaging HTML5 charts for your website. It's a flexible charting library for designers and developers.
- **[Three.js](https://threejs.org/)**: A JavaScript 3D library that makes it easier to display 3D graphics in a web browser using WebGL.
- **[ECharts](https://echarts.apache.org/en/index.html)**: A powerful, interactive charting and visualization library for browser.
- **[Recharts](https://recharts.org/)**: A composable charting library built on React components.

## UI Components & Toolkits

- **[Bootstrap](https://getbootstrap.com/)**: A popular CSS framework with a vast collection of pre-built components (buttons, forms, navigation) and JavaScript plugins for creating responsive websites.
- **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework with predefined classes that you can use to build and design web pages directly in your markup. Often paired with headless UI components.
- **[Material-UI (MUI)](https://mui.com/)**: A comprehensive suite of UI tools to help you ship new features faster. Offers a robust library of React components.
- **[Ant Design](https://ant.design/)**: An enterprise-class UI design language and React UI library with a set of high-quality React components, one of best React UI library for enterprises.
- **[Chakra UI](https://chakra-ui.com/)**: A simple, modular and accessible component library that gives you the building blocks you need to build your React applications.
- **[Headless UI](https://headlessui.com/)**: A set of completely unstyled, fully accessible UI components, designed to integrate beautifully with Tailwind CSS. For React and Vue.
- **[Storybook](https://storybook.js.org/)**: A tool for developing UI components in isolation for React, Vue, Angular, and more. It makes building stunning UIs organized and efficient.
- **[Shadcn/ui](https://ui.shadcn.com/)**: Beautifully designed components that you can copy and paste into your apps. Accessible. Customizable. Open Source. Not a component library, but a collection of re-usable components.

## DOM Manipulation

_(Libraries for direct DOM manipulation, event handling, and utilities, including modern alternatives to jQuery or libraries that complement vanilla JavaScript)._

- **[jQuery](https://jquery.com/)**: A fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, and animation much simpler with an easy-to-use API.
- **[Cash](https://github.com/fabiospampinato/cash)**: A small, modern jQuery alternative for modern browsers (IE10+). Provides a similar API to jQuery.
- **[Umbrella JS](https://umbrellajs.com/)**: A lightweight JavaScript library inspired by jQuery for DOM manipulation and events.
- **[DOMPurify](https://github.com/cure53/DOMPurify)**: A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG. Essential for securely manipulating HTML from untrusted sources.

## Utility Libraries

General utilities for everyday tasks, and specialized libraries for media and file manipulation.

### General Utilities

- **[Lodash](https://lodash.com/)**: A modern JavaScript utility library delivering modularity, performance, and extra features.
- **[Underscore.js](https://underscorejs.org/)**: A JavaScript library that provides a lot of the functional programming helpers that are missing from the native JavaScript implementation.
- **[date-fns](https://date-fns.org/)**: A modern JavaScript date utility library. Provides a comprehensive, yet simple and consistent toolset for manipulating dates in the browser and Node.js.
- **[Luxon](https://moment.github.io/luxon/)**: A powerful, modern, and friendly wrapper for JavaScript dates and times. A successor to Moment.js.
- **[Ramda](https://ramdajs.com/)**: A practical functional library for JavaScript programmers.

### File & Content Handling

- **[fs-extra (Node.js)](https://github.com/jprichardson/node-fs-extra)**: Adds file system methods that aren't included in the native `fs` module and adds promise support to `fs` methods.
- **[FilePond](https://pqina.nl/filepond/)**: A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience.
- **[Papa Parse](https://www.papaparse.com/)**: The powerful, in-browser CSV parser for the web. Handles large files, malformed input, and is easy to use.
- **[FileSaver.js](https://github.com/eligrey/FileSaver.js/)**: A solution to save files on the client-side, and is perfect for web apps that need to generate files.
- **[JSZip](https://stuk.github.io/jszip/)**: A JavaScript library for creating, reading and editing .zip files, with a lovely and simple API.

### Image Manipulation

- **[Sharp (Node.js)](https://sharp.pixelplumbing.com/)**: High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and AVIF images. Uses libvips.
- **[Jimp](https://github.com/jimp-dev/jimp)**: An image processing library for Node.js, written entirely in JavaScript, with zero native dependencies.
- **[Cropper.js](https://fengyuanchen.github.io/cropperjs/)**: A JavaScript image cropper.
- **[Fabric.js](http://fabricjs.com/)**: JavaScript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser. Provides an interactive object model on top of canvas element.
- **[Pica](https://nodeca.github.io/pica/demo/)**: High quality image resize in browser.

### Audio Processing

- **[Howler.js](https://howlerjs.com/)**: An audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio. This makes working with audio in JavaScript easy and reliable across all platforms.
- **[Tone.js](https://tonejs.github.io/)**: A Web Audio framework for creating interactive music in the browser. The architecture of Tone.js aims to be familiar to both musicians and audio programmers.
- **[WaveSurfer.js](https://wavesurfer.xyz/)**: A customizable audio waveform visualization, built on top of Web Audio API and HTML5 Canvas.
- **[soundbank-player](https://github.com/mmckegg/soundbank-player)**: A simple soundbank player (GM mapped) for Web Audio and Web MIDI.

### Video Processing & Players

- **[Video.js](https://videojs.com/)**: An open source HTML5 video player framework. Makes it easier to work with and build on HTML5 video.
- **[FFmpeg.wasm](https://ffmpegwasm.netlify.app/)**: FFmpeg for browser and Node.js, powered by WebAssembly. Allows for video and audio recording, conversion and streaming.
- **[Plyr](https://plyr.io/)**: A simple, lightweight, accessible and customizable HTML5, YouTube and Vimeo media player.
- **[Hls.js](https://github.com/video-dev/hls.js)**: A JavaScript library that implements an HTTP Live Streaming client. It relies on HTML5 video and MediaSource Extensions for playback.

## Templating Engines

- **[Handlebars.js](https://handlebarsjs.com/)**: A simple templating language that lets you build semantic templates effectively.
- **[EJS](https://ejs.co/)**: Embedded JavaScript templating. Allows you to generate HTML markup with plain JavaScript.
- **[Pug (formerly Jade)](https://pugjs.org/api/getting-started.html)**: A high-performance Node.js templating engine with a clean, whitespace-sensitive syntax.
- **[Nunjucks](https://mozilla.github.io/nunjucks/)**: A rich and powerful templating language for JavaScript, inspired by jinja2.

## Static Site Generators

- **[Next.js](https://nextjs.org/)**: (Also a Frontend Framework/Backend) A React framework that supports static site generation (SSG) for building fast, SEO-friendly websites.
- **[Gatsby](https://www.gatsbyjs.com/)**: A free and open-source framework based on React that helps developers build blazing-fast websites and apps.
- **[Astro](https://astro.build/)**: A modern framework for building content-driven websites. Focuses on performance by shipping less JavaScript.
- **[Eleventy (11ty)](https://www.11ty.dev/)**: A simpler static site generator. It works with a directory of templates, combines them with data, and outputs HTML.

## Package Managers

- **[npm](https://www.npmjs.com/)**: The default package manager for Node.js. The world's largest software registry.
- **[Yarn](https://yarnpkg.com/)**: A fast, reliable, and secure dependency management tool for JavaScript.
- **[pnpm](https://pnpm.io/)**: A fast, disk space efficient package manager. Uses a content-addressable filesystem to store all files from all versions of all packages only once.

## Type Checking

- **[TypeScript](https://www.typescriptlang.org/)**: A superset of JavaScript that adds optional static typing to the language. Compiles to plain JavaScript.
- **[Flow](https://flow.org/)**: A static type checker for JavaScript, developed by Facebook.

## Code Quality & Formatting

- **[ESLint](https://eslint.org/)**: A pluggable linting utility for JavaScript and JSX. Helps identify and report on patterns found in ECMAScript/JavaScript code.
- **[Prettier](https://prettier.io/)**: An opinionated code formatter that enforces a consistent style by parsing your code and re-printing it with its own rules.
- **[Standard JS](https://standardjs.com/)**: JavaScript style guide, linter, and formatter. No configuration necessary.

## Code Editors (Embeddable/JS-based)

- **[VSCode](https://code.visualstudio.com/)**: integrated development environment developed by Microsoft. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded version control with Git.
- **[WebStorm](https://www.jetbrains.com/webstorm/)**: powerful integrated development environment (IDE) from JetBrains specifically designed for JavaScript and TypeScript development

## Learning Resources

- **[MDN Web Docs (JavaScript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**: The definitive resource for web technologies, including comprehensive JavaScript documentation, tutorials, and references.
- **[The Modern JavaScript Tutorial](https://javascript.info/)**: A comprehensive, up-to-date tutorial covering modern JavaScript from the basics to advanced topics.
- **[freeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)**: Offers interactive coding challenges and projects to learn JavaScript, algorithms, and data structures.
- **[JavaScript.com](https://www.javascript.com/)**: A simple, easy-to-follow guide to learning JavaScript, powered by Pluralsight.
- **[You Don't Know JS Yet (Book Series)](https://github.com/getify/You-Dont-Know-JS)**: A series of books diving deep into the core mechanisms of the JavaScript language.

## Awesome Resources & Communities

- **[JavaScript Weekly](https://javascriptweekly.com/)**: A popular free weekly newsletter featuring curated JavaScript news, articles, and projects.
- **[Dev.to (JavaScript Tag)](https://dev.to/t/javascript)**: A vibrant online community for developers to share articles, tutorials, and discussions on JavaScript and other web technologies.
- **[Stack Overflow (JavaScript Tag)](https://stackoverflow.com/questions/tagged/javascript)**: The go-to Q&A site for programmers, with an enormous and active JavaScript community.
- **[JSConf](https://jsconf.com/)**: A series of global conferences focused on JavaScript and its ecosystem.
- **[Node.js Official Website](https://nodejs.org/en/docs/)**: The official documentation and resources for Node.js, the JavaScript runtime.
- **[GitHub (JavaScript Language Filter)](https://github.com/topics/javascript)**: The primary platform for hosting open-source JavaScript projects, discoverable via language topics.
- **[Awesome Lists (sindresorhus/awesome)](https://github.com/sindresorhus/awesome)**: The original meta-list of awesome lists, a great place to discover even more specific JavaScript-related lists.

---

## Contributing

Contributions are always welcome! Please read the [contribution guidelines](CONTRIBUTING.md) to ensure your suggestions are added smoothly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
