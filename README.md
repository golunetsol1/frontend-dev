# frontend-dev
================================================================================
              60-DAY FRONTEND DEVELOPMENT ROADMAP  (VERSION 2.0)
          Advanced JavaScript  ->  React.js  ->  Next.js  ->  Advanced Track
              For Web Designers Moving into Frontend Development
================================================================================

Last reviewed: November 2026
Target versions: React 19, React Router 7, Next.js 16 (App Router),
                 Tailwind CSS 4, TypeScript 5, Zod 4, TanStack Query 5

--------------------------------------------------------------------------------
TABLE OF CONTENTS
--------------------------------------------------------------------------------
  0. Goal, Study Routine and How to Use This Roadmap
  1. Day 0 - Setup and Pre-check (before you start)
  2. Phase 1 - Advanced JavaScript ........................ Days 1-15
  3. Phase 2 - React.js ..................................... Days 16-45
  4. Phase 3 - Next.js ...................................... Days 46-60
  5. Phase 4 - Advanced Track (optional) .................... Days 61-75
  6. Portfolio Projects (Standard + Pro features)
  7. Video Courses (Hindi + English)
  8. Practice Platforms, Free APIs and Design Sources
  9. Interview Preparation
 10. Learning Advice for Web Designers
 11. Suggested Toolkit
 12. Progress Tracker

NOTE ON DAY NUMBERS
Every day now has a GLOBAL number (Day 1-75) and a PHASE number in
brackets, e.g. "DAY 16 [React 1]". This avoids confusion when you track
progress.


================================================================================
0. GOAL, STUDY ROUTINE AND HOW TO USE THIS ROADMAP
================================================================================

GOAL
Turn existing web design skills into practical frontend development
skills. Learn to convert Figma or static website designs into responsive,
reusable, accessible, interactive, API-connected websites and deploy them.

DAILY STUDY ROUTINE (2-3 hours)
  - 30 min : Learn the concept (read the "Learn" links) and take notes
  - 60 min : Code along, then repeat WITHOUT looking
  - 60 min : Build the "Practice" task
  - 30 min : Revise, debug, commit to Git, and explain what you learned
             (write 3-5 lines in a learning journal or README)

HOW EACH DAY IS STRUCTURED
  Topics    : What you must understand
  Learn     : Hand-picked links (docs + tutorials). Read the FIRST link
              fully; use the others as backup or for depth.
  Practice  : A small build task
  Advanced  : Optional extra depth. Do it only if you finish early.
  Check     : You are done when you can do/answer this without help.

LINK LEGEND
  [MDN]  MDN Web Docs (Mozilla)        [JSI]  javascript.info
  [DOC]  Official documentation        [WEB]  web.dev / Chrome docs
  [VID]  Video                         [ART]  Article / guide

IMPORTANT
  - Day counts are a suggested plan, not a promise of mastery. If a topic
    is hard, spend extra days on it. Consistency beats speed.
  - Documentation URLs sometimes move. If a link breaks, search the topic
    name inside that site's documentation.
  - Video courses may use older versions. Official docs are the source of
    truth when the two disagree.


================================================================================
1. DAY 0 - SETUP AND PRE-CHECK (BEFORE YOU START)
================================================================================

Setup
  - Install VS Code, Node.js LTS, Git and Google Chrome
  - Create a GitHub account and one repository named "frontend-journey"
  - VS Code extensions: ESLint, Prettier, Error Lens, GitLens,
    Tailwind CSS IntelliSense, ES7+ React snippets

Learn
  [DOC] Node.js download ............ https://nodejs.org/en/download
  [DOC] VS Code basics .............. https://code.visualstudio.com/docs/getstarted/getting-started
  [DOC] Git - first-time setup ...... https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
  [DOC] GitHub Hello World .......... https://docs.github.com/en/get-started/start-your-journey/hello-world

HTML/CSS pre-check (you should already be comfortable with these)
  - Semantic HTML, forms, Flexbox, Grid, media queries, CSS variables
  [WEB] Learn HTML .................. https://web.dev/learn/html
  [WEB] Learn CSS ................... https://web.dev/learn/css
  [ART] Flexbox guide ............... https://css-tricks.com/snippets/css/a-guide-to-flexbox/
  [ART] Grid guide .................. https://css-tricks.com/snippets/css/complete-guide-grid/
  [ART] Flexbox Froggy (game) ....... https://flexboxfroggy.com/
  [ART] Grid Garden (game) .......... https://cssgridgarden.com/

Check: You can build a responsive 3-column card layout with Grid that
becomes 1 column on mobile, and push it to GitHub.


================================================================================
2. PHASE 1 - ADVANCED JAVASCRIPT (DAYS 1-15)
================================================================================

GOAL
Build a strong JavaScript foundation before React. Focus on data handling,
functions, asynchronous code, browser APIs and debugging.

Main references for the whole phase
  [JSI] The Modern JavaScript Tutorial ... https://javascript.info/
  [MDN] JavaScript Guide ................. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide


--------------------------------------------------------------------------------
WEEK 1 - JAVASCRIPT FUNDAMENTALS AND ES6+
--------------------------------------------------------------------------------

DAY 1 [JS 1] - JavaScript foundations
  Topics
    - What JavaScript does in a website; linking scripts (defer, type=module)
    - Variables: var, let, const
    - Primitive and reference data types
    - Type conversion vs type coercion; == vs ===
    - Operators and expressions; truthy and falsy values
    - if/else, switch, ternary
    - for, while, for...of, for...in loops
  Learn
    [JSI] Variables ............... https://javascript.info/variables
    [JSI] Data types .............. https://javascript.info/types
    [JSI] Type conversions ........ https://javascript.info/type-conversions
    [JSI] Comparisons ............. https://javascript.info/comparison
    [JSI] Conditional branching ... https://javascript.info/ifelse
    [JSI] Loops ................... https://javascript.info/while-for
    [MDN] Grammar and types ....... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types
    [MDN] Loops and iteration ..... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration
  Practice
    Calculator, age checker, multiplication table, grade calculator.
  Advanced
    - Nullish coalescing (??) vs OR (||)
      https://javascript.info/nullish-coalescing-operator
  Check: Explain why "5" + 1 is "51" but "5" - 1 is 4.

DAY 2 [JS 2] - Functions and scope
  Topics
    - Function declarations vs expressions; arrow functions
    - Parameters, return values, default parameters
    - Global, function and block scope; lexical scope
    - Hoisting and the Temporal Dead Zone (TDZ)
  Learn
    [JSI] Functions ............... https://javascript.info/function-basics
    [JSI] Function expressions .... https://javascript.info/function-expressions
    [JSI] Arrow functions ......... https://javascript.info/arrow-functions-basics
    [JSI] The old "var" ........... https://javascript.info/var
    [MDN] Functions guide ......... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
    [MDN] Hoisting ................ https://developer.mozilla.org/en-US/docs/Glossary/Hoisting
  Practice
    Reusable functions: applyDiscount(), calculateTotal(), isValidEmail().
  Advanced
    - Recursion: https://javascript.info/recursion
  Check: Predict the output of console.log(x) before "let x = 1" vs "var x".

DAY 3 [JS 3] - Arrays and array methods
  Topics
    - Create, read, update arrays; push, pop, shift, unshift, splice, slice
    - map, filter, reduce
    - find, findIndex, includes, some, every, forEach
    - sort (with compare function), reverse
    - Immutable versions: toSorted, toReversed, with (ES2023)
  Learn
    [JSI] Arrays .................. https://javascript.info/array
    [JSI] Array methods ........... https://javascript.info/array-methods
    [MDN] Array reference ......... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array
    [MDN] Indexed collections ..... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections
  Practice
    Display products, filter by category, sort by price, reduce to cart total.
  Advanced
    - Array.from, flat, flatMap, Object.groupBy
      https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/groupBy
  Check: Solve "total price of in-stock items" with one filter + one reduce.

DAY 4 [JS 4] - Objects
  Topics
    - Creating and updating objects; nested objects; arrays of objects
    - Object methods and shorthand
    - Object and array destructuring
    - Optional chaining (?.)
    - Object.keys, Object.values, Object.entries, Object.fromEntries
  Learn
    [JSI] Objects ................. https://javascript.info/object
    [JSI] Object methods, "this" .. https://javascript.info/object-methods
    [JSI] Destructuring ........... https://javascript.info/destructuring-assignment
    [JSI] Optional chaining ....... https://javascript.info/optional-chaining
    [JSI] keys/values/entries ..... https://javascript.info/keys-values-entries
    [MDN] Working with objects .... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects
  Practice
    Create a user-profile object (with nested address) and render it.
  Advanced
    - Getters/setters: https://javascript.info/property-accessors
  Check: Safely read user.address.city when address may be missing.

DAY 5 [JS 5] - Modern ES6+
  Topics
    - Template literals; spread and rest operators
    - Enhanced object literals; default parameters
    - ES Modules: named vs default import/export
  Learn
    [MDN] Template literals ....... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals
    [JSI] Rest and spread ......... https://javascript.info/rest-parameters-spread
    [JSI] Modules intro ........... https://javascript.info/modules-intro
    [JSI] Export and import ....... https://javascript.info/import-export
    [MDN] JavaScript modules ...... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules
  Practice
    Split a small app into utils.js, data.js, ui.js and main.js.
  Advanced
    - Dynamic import(): https://javascript.info/modules-dynamic-imports
  Check: Explain when to use a default export vs named exports.

DAY 6 [JS 6] - Advanced functions
  Topics
    - Callbacks and higher-order functions
    - Closures
    - The "this" keyword; call, apply, bind
    - Pure functions and side effects
  Learn
    [JSI] Closures ................ https://javascript.info/closure
    [JSI] call/apply .............. https://javascript.info/call-apply-decorators
    [JSI] Function binding ........ https://javascript.info/bind
    [MDN] Closures ................ https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
    [MDN] this .................... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this
    [VID] Namaste JS - Closures (playlist below, section 7.A)
  Practice
    Reusable sort/filter/format helpers; a createCounter() using a closure.
  Advanced
    - Debounce and throttle (used in search boxes and scroll handlers)
      https://javascript.info/task/debounce
      https://javascript.info/task/throttle
    - Currying: https://javascript.info/currying-partials
  Check: Write a debounced search input that logs only after typing stops.

DAY 7 [JS 7] - WEEK 1 MINI PROJECT: Product Listing Page (plain JS)
  Requirements
    - Product data in an array of objects (or a products.json file)
    - Render products dynamically
    - Search (debounced), filter by category, sort by price
    - Cart: add/remove, quantity, total
  Pro features (optional)
    - Price range slider, "no results" state, URL query params for filters
      https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams
  Design source: pick a free Figma e-commerce kit (see section 8)


--------------------------------------------------------------------------------
WEEK 2 - BROWSER JAVASCRIPT AND ASYNCHRONOUS PROGRAMMING
--------------------------------------------------------------------------------

DAY 8 [JS 8] - DOM manipulation
  Topics
    - DOM tree basics; querySelector, querySelectorAll
    - textContent vs innerHTML (and why innerHTML can cause XSS)
    - Attributes, dataset, classList, style
    - Create, append, remove elements; DocumentFragment
  Learn
    [JSI] DOM tree ................ https://javascript.info/dom-nodes
    [JSI] Searching elements ...... https://javascript.info/searching-elements-dom
    [JSI] Modifying the document .. https://javascript.info/modifying-document
    [JSI] Styles and classes ...... https://javascript.info/styles-and-classes
    [MDN] DOM introduction ........ https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction
  Practice
    Mobile menu toggle, tab interface, accordion, modal.
  Advanced
    - IntersectionObserver (lazy-load, reveal-on-scroll animations)
      https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API
  Check: Build a modal that closes on Esc, outside click and close button.

DAY 9 [JS 9] - Events and browser storage
  Topics
    - click, input, change, submit, keydown events
    - Bubbling, capturing and event delegation
    - preventDefault, stopPropagation
    - localStorage vs sessionStorage; JSON.stringify / JSON.parse
  Learn
    [JSI] Browser events .......... https://javascript.info/introduction-browser-events
    [JSI] Bubbling and capturing .. https://javascript.info/bubbling-and-capturing
    [JSI] Event delegation ........ https://javascript.info/event-delegation
    [JSI] Default actions ......... https://javascript.info/default-browser-action
    [JSI] localStorage ............ https://javascript.info/localstorage
    [JSI] JSON .................... https://javascript.info/json
    [MDN] Web Storage API ......... https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API
  Practice
    To-do list saved in localStorage (add, complete, delete, filter).
  Advanced
    - Form validation with the Constraint Validation API
      https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation
  Check: Use ONE listener on a <ul> to handle clicks on all <li> items.

DAY 10 [JS 10] - Asynchronous JavaScript
  Topics
    - Sync vs async code; setTimeout, setInterval
    - Callbacks and callback hell
    - Promises: then, catch, finally; promise chaining
  Learn
    [JSI] setTimeout/setInterval .. https://javascript.info/settimeout-setinterval
    [JSI] Callbacks ............... https://javascript.info/callbacks
    [JSI] Promise basics .......... https://javascript.info/promise-basics
    [JSI] Promise chaining ........ https://javascript.info/promise-chaining
    [MDN] Using promises .......... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises
  Practice
    Simulated "loading" process with a promise that resolves after 2s.
  Check: Convert a 3-level callback chain into a promise chain.

DAY 11 [JS 11] - Async/await and error handling
  Topics
    - async and await; try/catch/finally
    - Promise.all, Promise.allSettled, Promise.race, Promise.any
    - Handling rejected promises; custom Error classes
  Learn
    [JSI] Async/await ............. https://javascript.info/async-await
    [JSI] Promise API ............. https://javascript.info/promise-api
    [JSI] Error handling .......... https://javascript.info/try-catch
    [JSI] Custom errors ........... https://javascript.info/custom-errors
    [MDN] async function .......... https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
  Practice
    Fetch 3 data sources in parallel; show partial results if one fails.
  Check: Explain the difference between Promise.all and Promise.allSettled.

DAY 12 [JS 12] - HTTP, REST APIs and Fetch
  Topics
    - What an API is; REST basics; JSON
    - HTTP methods: GET, POST, PUT, PATCH, DELETE
    - Headers, body, query params; status codes (2xx, 4xx, 5xx)
    - Fetch API; checking response.ok; CORS basics
    - Cancelling requests with AbortController
  Learn
    [MDN] HTTP overview ........... https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview
    [MDN] HTTP status codes ....... https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
    [MDN] Using Fetch ............. https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch
    [JSI] Fetch ................... https://javascript.info/fetch
    [JSI] Fetch: Abort ............ https://javascript.info/fetch-abort
    [MDN] CORS .................... https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
  Practice
    Fetch and display products from https://dummyjson.com/products with
    pagination (limit & skip).
  Check: Why does fetch NOT throw on a 404, and how do you handle it?

DAY 13 [JS 13] - How JavaScript works + DevTools debugging
  Topics
    - Execution context and call stack
    - Event loop; microtasks vs macrotasks
    - Primitive vs reference values; shallow vs deep copy (structuredClone)
    - Debugging: breakpoints, watch, Network tab, Console
  Learn
    [JSI] Event loop .............. https://javascript.info/event-loop
    [JSI] Microtasks .............. https://javascript.info/microtask-queue
    [MDN] structuredClone ......... https://developer.mozilla.org/en-US/docs/Web/API/Window/structuredClone
    [WEB] Debug JS in Chrome ...... https://developer.chrome.com/docs/devtools/javascript
    [WEB] Network panel ........... https://developer.chrome.com/docs/devtools/network
    [VID] "What the heck is the event loop" - Philip Roberts (JSConf)
          https://www.youtube.com/watch?v=8aGhZQkoFbQ
    [ART] Loupe event-loop visualiser http://latentflip.com/loupe/
  Practice
    Predict the output order of mixed setTimeout / Promise / console.log code.
  Advanced
    - Prototypes and classes (needed to read library code)
      https://javascript.info/prototype-inheritance
      https://javascript.info/classes
    - Memory leaks: https://developer.chrome.com/docs/devtools/memory-problems
  Check: Explain why Promise.then runs before setTimeout(fn, 0).

DAY 14 [JS 14] - Developer tooling and project setup
  Topics
    - Node.js and npm basics; package.json; npm scripts
    - dependencies vs devDependencies; package-lock.json
    - Vite project setup; environment variables (import.meta.env)
    - ESLint + Prettier; VS Code debugging
  Learn
    [DOC] Intro to Node.js ........ https://nodejs.org/en/learn/getting-started/introduction-to-nodejs
    [DOC] About npm ............... https://docs.npmjs.com/about-npm
    [DOC] package.json ............ https://docs.npmjs.com/cli/configuring-npm/package-json
    [DOC] Vite - Getting started .. https://vite.dev/guide/
    [DOC] Vite env variables ...... https://vite.dev/guide/env-and-mode
    [DOC] ESLint getting started .. https://eslint.org/docs/latest/use/getting-started
    [DOC] Prettier ................ https://prettier.io/docs/
  Practice
    Create a Vite vanilla project; add ESLint, Prettier and npm scripts.
  Security
    Anything in VITE_* env variables is PUBLIC in the browser bundle.
    Never put secret keys there.
  Check: Explain what "npm run build" produces and where.

DAY 15 [JS 15] - PHASE 1 FINAL PROJECT: API Dashboard (plain JS + Vite)
  Requirements
    - Fetch data from an API (e.g. DummyJSON users or products)
    - Loading, error and empty states
    - Debounced search and filtering; pagination
    - Form with validation
    - Save theme/preference in localStorage
    - Responsive layout; code organised into modules
    - Deployed on Netlify or Vercel; code on GitHub with a README
  Pro features (optional)
    - Request cancellation with AbortController
    - Accessible keyboard navigation

PHASE 1 CHECKPOINT
You can work with arrays and objects, write reusable functions, explain
closures and the event loop, use promises and async/await, call APIs,
manipulate the DOM safely and debug with DevTools.
Self-test: https://javascript.info/ tasks at the end of each chapter.


================================================================================
3. PHASE 2 - REACT.JS (DAYS 16-45)
================================================================================

GOAL
Turn static designs into reusable, responsive, interactive React apps.
Learn component architecture, hooks, routing, APIs, state management,
TypeScript and professional libraries.

Main references for the whole phase
  [DOC] React Learn ............. https://react.dev/learn
  [DOC] React API reference ..... https://react.dev/reference/react
  [DOC] React Tic-Tac-Toe tutorial https://react.dev/learn/tutorial-tic-tac-toe


--------------------------------------------------------------------------------
WEEK 3 - REACT FUNDAMENTALS AND COMPONENT ARCHITECTURE
--------------------------------------------------------------------------------

DAY 16 [React 1] - React introduction and setup
  Topics
    - What React is and when to use it; React vs plain JS
    - Single Page Applications; Virtual DOM and reconciliation (concept)
    - Create a React + Vite project; src, public, package.json, main.jsx
    - React DevTools browser extension
  Learn
    [DOC] Creating a React app .... https://react.dev/learn/creating-a-react-app
    [DOC] Build from scratch (Vite) https://react.dev/learn/build-a-react-app-from-scratch
    [DOC] Vite - Scaffolding ...... https://vite.dev/guide/#scaffolding-your-first-vite-project
    [DOC] React DevTools .......... https://react.dev/learn/react-developer-tools
    [DOC] Next.js React Foundations https://nextjs.org/learn/react-foundations
  Practice
    Run the starter app and explain each file in the project.
  Check: Explain what happens in the browser when a React app starts.

DAY 17 [React 2] - JSX and components
  Topics
    - JSX rules; JS expressions in { }
    - Function components; naming; import/export
    - Component composition; children prop
  Learn
    [DOC] Your first component .... https://react.dev/learn/your-first-component
    [DOC] Import/export components . https://react.dev/learn/importing-and-exporting-components
    [DOC] Writing markup with JSX . https://react.dev/learn/writing-markup-with-jsx
    [DOC] JS in JSX with braces ... https://react.dev/learn/javascript-in-jsx-with-curly-braces
  Practice
    Build Header, Footer, Button and Card components.
  Check: Why must a component return a single root element (or Fragment)?

DAY 18 [React 3] - Props and reusable components
  Topics
    - Passing props parent -> child; destructuring; default values
    - children prop; reusable Button, Card, Input, Badge
    - One-way data flow; keeping components pure
  Learn
    [DOC] Passing props ........... https://react.dev/learn/passing-props-to-a-component
    [DOC] Keeping components pure . https://react.dev/learn/keeping-components-pure
    [DOC] Thinking in React ....... https://react.dev/learn/thinking-in-react
  Practice
    A reusable ServiceCard component rendered with different data.
  Advanced
    - Button "variants" pattern (primary/secondary/ghost, sm/md/lg)
  Check: Break a Figma section into a component tree on paper first.

DAY 19 [React 4] - Lists and conditional rendering
  Topics
    - Rendering arrays with map; why keys matter
    - Conditional rendering: if, ternary, &&
    - Empty states; dynamic content
  Learn
    [DOC] Conditional rendering ... https://react.dev/learn/conditional-rendering
    [DOC] Rendering lists ......... https://react.dev/learn/rendering-lists
    [DOC] Preserving/resetting state (keys) https://react.dev/learn/preserving-and-resetting-state
  Practice
    Product grid with category labels and an empty-results message.
  Check: Why is using the array index as a key risky?

DAY 20 [React 5] - Styling React applications
  Topics
    - Plain CSS, CSS Modules, conditional classes (clsx), inline styles
    - Tailwind CSS v4 fundamentals with Vite
    - Bootstrap (optional, for legacy projects)
    - Responsive design in React
  Learn
    [DOC] Vite CSS Modules ........ https://vite.dev/guide/features#css-modules
    [DOC] Tailwind + Vite install . https://tailwindcss.com/docs/installation/using-vite
    [DOC] Tailwind utility classes  https://tailwindcss.com/docs/styling-with-utility-classes
    [DOC] Tailwind responsive ..... https://tailwindcss.com/docs/responsive-design
    [DOC] clsx .................... https://github.com/lukeed/clsx
    [DOC] Bootstrap 5.3 ........... https://getbootstrap.com/docs/5.3/getting-started/introduction/
  Practice
    Convert a static landing page into React components with Tailwind.
  Advanced
    - Design tokens with Tailwind @theme
      https://tailwindcss.com/docs/theme
  Check: Recreate one Figma section pixel-close at mobile and desktop.

DAY 21 [React 6] - Component architecture and project structure
  Topics
    - components/, pages/, layouts/, hooks/, services/, assets/
    - Shared vs feature components; naming conventions
    - Small, focused components; separate data from presentation
    - Absolute imports (path aliases)
  Learn
    [DOC] Thinking in React ....... https://react.dev/learn/thinking-in-react
    [ART] Bulletproof React (structure guide)
          https://github.com/alan2207/bulletproof-react
    [DOC] Vite resolve.alias ...... https://vite.dev/config/shared-options#resolve-alias
  Practice
    Reusable layout with header, sidebar and footer.
  Advanced
    - Feature-based folder structure (read the Bulletproof React docs folder)

DAY 22 [React 7] - WEEK 3 PROJECT: Responsive Business Website
  Requirements
    - Header with navigation, hero, service cards, testimonials
    - Reusable buttons and cards; responsive mobile menu; footer
    - Built from a real Figma design (see section 8)
  Pro features (optional)
    - Accessible mobile menu (focus trap, aria-expanded, Esc to close)
      https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/
    - Lighthouse score 90+ on all categories


--------------------------------------------------------------------------------
WEEK 4 - REACT HOOKS AND STATE
--------------------------------------------------------------------------------

DAY 23 [React 8] - useState
  Topics
    - What state is; useState; state vs normal variables
    - State updates are async-like snapshots; updater functions
    - Updating objects and arrays immutably
    - Choosing state structure; lifting state up
  Learn
    [DOC] State: a component's memory https://react.dev/learn/state-a-components-memory
    [DOC] State as a snapshot ..... https://react.dev/learn/state-as-a-snapshot
    [DOC] Queueing state updates .. https://react.dev/learn/queueing-a-series-of-state-updates
    [DOC] Updating objects ........ https://react.dev/learn/updating-objects-in-state
    [DOC] Updating arrays ......... https://react.dev/learn/updating-arrays-in-state
    [DOC] Choosing state structure  https://react.dev/learn/choosing-the-state-structure
    [DOC] Sharing state ........... https://react.dev/learn/sharing-state-between-components
  Practice
    Counter, tabs, show/hide panel, image gallery.
  Check: Why does calling setCount(count + 1) three times only add 1?

DAY 24 [React 9] - Events and forms
  Topics
    - onClick, onChange, onSubmit; controlled inputs
    - Form state; field-level errors; disabling submit while sending
  Learn
    [DOC] Responding to events .... https://react.dev/learn/responding-to-events
    [DOC] Reacting to input with state https://react.dev/learn/reacting-to-input-with-state
    [DOC] <input> reference ....... https://react.dev/reference/react-dom/components/input
    [DOC] <form> reference ........ https://react.dev/reference/react-dom/components/form
  Practice
    Registration form with validation and inline error messages.
  Check: Explain controlled vs uncontrolled inputs.

DAY 25 [React 10] - useEffect
  Topics
    - What effects are; dependency arrays; cleanup functions
    - Fetching data in an effect (with race-condition handling)
    - When you do NOT need an effect
  Learn
    [DOC] Synchronizing with effects https://react.dev/learn/synchronizing-with-effects
    [DOC] You might not need an effect https://react.dev/learn/you-might-not-need-an-effect
    [DOC] Lifecycle of effects .... https://react.dev/learn/lifecycle-of-reactive-effects
    [DOC] useEffect reference ..... https://react.dev/reference/react/useEffect
  Practice
    Fetch and display users; cancel the request on unmount.
  Check: Why does the effect run twice in development (Strict Mode)?

DAY 26 [React 11] - useRef
  Topics
    - useRef basics; accessing DOM elements; focus management
    - Storing mutable values (timers, previous values); useRef vs useState
  Learn
    [DOC] Referencing values with refs https://react.dev/learn/referencing-values-with-refs
    [DOC] Manipulating DOM with refs https://react.dev/learn/manipulating-the-dom-with-refs
    [DOC] useRef reference ........ https://react.dev/reference/react/useRef
  Practice
    Auto-focus search field; stopwatch using a ref for the interval id.

DAY 27 [React 12] - useContext
  Topics
    - Prop drilling; createContext; Provider; useContext
    - Theme and auth context; when NOT to use context
  Learn
    [DOC] Passing data deeply with context https://react.dev/learn/passing-data-deeply-with-context
    [DOC] useContext reference .... https://react.dev/reference/react/useContext
  Practice
    Light/dark theme (respect prefers-color-scheme) and shared user info.

DAY 28 [React 13] - useReducer and custom hooks
  Topics
    - Reducers, actions, dispatch; useReducer vs useState
    - Reducer + Context pattern
    - Custom hooks to reuse logic
  Learn
    [DOC] Extracting state logic into a reducer https://react.dev/learn/extracting-state-logic-into-a-reducer
    [DOC] Scaling up with reducer + context https://react.dev/learn/scaling-up-with-reducer-and-context
    [DOC] Reusing logic with custom hooks https://react.dev/learn/reusing-logic-with-custom-hooks
    [ART] usehooks-ts (examples) .. https://usehooks-ts.com/
  Practice
    Cart reducer; custom hooks: useFetch, useLocalStorage, useDebounce.

DAY 29 [React 14] - WEEK 4 PROJECT: Interactive Admin Dashboard
  Requirements
    - Collapsible sidebar, theme switcher, search and filters
    - Forms; reusable components; state shared between components
  Pro features (optional)
    - Charts with Recharts: https://recharts.org/
    - Keyboard shortcuts and accessible focus states


--------------------------------------------------------------------------------
WEEK 5 - ROUTING, API INTEGRATION AND AUTH
--------------------------------------------------------------------------------

DAY 30 [React 15] - React Router setup
  Topics
    - React Router v7 modes (declarative / data / framework)
    - BrowserRouter, Routes, Route, Link, NavLink
  Learn
    [DOC] Picking a mode .......... https://reactrouter.com/start/modes
    [DOC] Installation ............ https://reactrouter.com/start/library/installation
    [DOC] Routing ................. https://reactrouter.com/start/declarative/routing
    [DOC] Navigating .............. https://reactrouter.com/start/declarative/navigating
  Practice
    Home, About and Contact pages with an active NavLink style.

DAY 31 [React 16] - Advanced routing
  Topics
    - Nested and layout routes; Outlet; index routes
    - Dynamic routes; useParams, useNavigate, useLocation
    - useSearchParams for filters in the URL; 404 page
  Learn
    [DOC] URL values .............. https://reactrouter.com/start/declarative/url-values
    [DOC] Routing (nested/layouts)  https://reactrouter.com/start/declarative/routing
  Practice
    Product list -> dynamic product detail route; filters saved in URL.
  Advanced
    - Lazy-loaded routes with React.lazy: https://react.dev/reference/react/lazy

DAY 32 [React 17] - REST API integration
  Topics
    - Request/response flow in React; Fetch vs Axios
    - GET, POST, PUT, PATCH, DELETE
    - A reusable API client (base URL, headers, interceptors)
  Learn
    [DOC] Axios intro ............. https://axios-http.com/docs/intro
    [DOC] Axios instance .......... https://axios-http.com/docs/instance
    [DOC] Axios interceptors ...... https://axios-http.com/docs/interceptors
    [DOC] DummyJSON docs .......... https://dummyjson.com/docs
  Practice
    services/api.js + services/products.js; fetch and show records.

DAY 33 [React 18] - Loading, error and empty states
  Topics
    - Skeleton loaders; error messages; empty results
    - HTTP status handling; retry; timeouts
  Learn
    [DOC] Suspense ................ https://react.dev/reference/react/Suspense
    [ART] Skeleton screens (NN/g) . https://www.nngroup.com/articles/skeleton-screens/
    [ART] Error message guidelines  https://www.nngroup.com/articles/error-message-guidelines/
  Practice
    Simulate slow 3G in DevTools; handle slow, failed and empty responses.

DAY 34 [React 19] - CRUD operations
  Topics
    - Create, read, update, delete; edit forms; confirm dialogs
    - Refreshing data after changes; pagination
  Learn
    [DOC] JSON Server (local fake REST API) https://github.com/typicode/json-server
    [DOC] DummyJSON (add/update/delete) https://dummyjson.com/docs/products
  Practice
    User-management CRUD screen with JSON Server.

DAY 35 [React 20] - Authentication fundamentals
  Topics
    - Authentication vs authorization; login/registration flow
    - Sessions vs tokens (JWT); access + refresh tokens
    - httpOnly cookies vs localStorage (security trade-offs)
    - Protected routes; logout; role-based UI
  Learn
    [MDN] HTTP cookies ............ https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies
    [ART] OWASP Authentication .... https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html
    [ART] OWASP Session Management  https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html
    [ART] JWT introduction ........ https://jwt.io/introduction
    [DOC] DummyJSON auth demo ..... https://dummyjson.com/docs/auth
  Practice
    Login flow with DummyJSON auth; protected dashboard route; logout.
  Security
    Never store real passwords or secret keys in frontend code. Frontend
    role checks are for UX only - the backend must enforce permissions.

DAY 36 [React 21] - WEEK 5 PROJECT: User Management Dashboard
  Requirements
    - Login page, protected pages, user list with search and pagination
    - Add, edit, delete users; API integration; loading and error states
  Pro features (optional)
    - Role-based menus (admin vs viewer), toast notifications
      https://sonner.emilkowal.ski/


--------------------------------------------------------------------------------
WEEK 6 - PROFESSIONAL REACT ECOSYSTEM
--------------------------------------------------------------------------------

DAY 37 [React 22] - TypeScript for React (moved earlier on purpose)
  Topics
    - Types: string, number, boolean, arrays, unions, literal types
    - Interfaces vs type aliases; optional properties; generics (basic)
    - Typing props, useState, events, refs and API responses
  Learn
    [DOC] TS Handbook ............. https://www.typescriptlang.org/docs/handbook/intro.html
    [DOC] Everyday types .......... https://www.typescriptlang.org/docs/handbook/2/everyday-types.html
    [DOC] Narrowing ............... https://www.typescriptlang.org/docs/handbook/2/narrowing.html
    [DOC] Generics ................ https://www.typescriptlang.org/docs/handbook/2/generics.html
    [DOC] Using TS with React ..... https://react.dev/learn/typescript
    [ART] React TS Cheatsheet ..... https://react-typescript-cheatsheet.netlify.app/
    [ART] Total TypeScript (free beginner tutorials) https://www.totaltypescript.com/tutorials
  Practice
    Create a react-ts Vite project; type a Product, User and API response.
  Why earlier: Every later library (RTK, TanStack Query, Zod, Next.js) is
  easier with TypeScript. From now on, build everything in TypeScript.

DAY 38 [React 23] - Redux Toolkit fundamentals
  Topics
    - Local vs global vs server state
    - Store, slices, reducers, actions; useSelector, useDispatch
    - Typed hooks with TypeScript
  Learn
    [DOC] RTK Quick Start ......... https://redux-toolkit.js.org/tutorials/quick-start
    [DOC] RTK TypeScript Quick Start https://redux-toolkit.js.org/tutorials/typescript
    [DOC] Redux Essentials ........ https://redux.js.org/tutorials/essentials/part-1-overview-concepts
  Practice
    Store shared cart data in Redux Toolkit.

DAY 39 [React 24] - Redux Toolkit in a real app
  Topics
    - Auth, cart and preferences slices; Redux DevTools
    - Persisting state; organising slices; best practices
  Learn
    [DOC] Redux Style Guide ....... https://redux.js.org/style-guide/
    [DOC] createAsyncThunk ........ https://redux-toolkit.js.org/api/createAsyncThunk
    [DOC] Redux DevTools .......... https://github.com/reduxjs/redux-devtools
  Practice
    Cart quantity + auth state in a project.
  Advanced
    - Zustand (a lighter alternative used by many teams)
      https://github.com/pmndrs/zustand

DAY 40 [React 25] - TanStack Query: queries
  Topics
    - Server state vs client state; QueryClient and provider
    - useQuery; query keys; loading/error states; caching; staleTime
    - Pagination and dependent queries
  Learn
    [DOC] Overview ................ https://tanstack.com/query/latest/docs/framework/react/overview
    [DOC] Quick start ............. https://tanstack.com/query/latest/docs/framework/react/quick-start
    [DOC] Queries ................. https://tanstack.com/query/latest/docs/framework/react/guides/queries
    [DOC] Query keys .............. https://tanstack.com/query/latest/docs/framework/react/guides/query-keys
    [ART] Practical React Query (TkDodo) https://tkdodo.eu/blog/practical-react-query
  Practice
    Fetch and cache a paginated product list; add React Query Devtools.

DAY 41 [React 26] - TanStack Query: mutations
  Topics
    - useMutation; create/update/delete; query invalidation
    - Optimistic updates; error rollback
  Learn
    [DOC] Mutations ............... https://tanstack.com/query/latest/docs/framework/react/guides/mutations
    [DOC] Invalidation from mutations https://tanstack.com/query/latest/docs/framework/react/guides/invalidations-from-mutations
    [DOC] Optimistic updates ...... https://tanstack.com/query/latest/docs/framework/react/guides/optimistic-updates
  Practice
    CRUD screen using queries and mutations with optimistic delete.
  Advanced
    - RTK Query (Redux's built-in alternative)
      https://redux-toolkit.js.org/rtk-query/overview

DAY 42 [React 27] - React Hook Form + Zod
  Topics
    - Schema validation; required, email, password rules; custom messages
    - React Hook Form basics; zodResolver; inferring TS types from schemas
  Learn
    [DOC] React Hook Form - Get started https://react-hook-form.com/get-started
    [DOC] RHF resolvers ........... https://github.com/react-hook-form/resolvers
    [DOC] Zod ..................... https://zod.dev/
    [DOC] Zod API ................. https://zod.dev/api
  Practice
    Validated registration form with password confirmation.

DAY 43 [React 28] - Modern UI development
  Topics
    - Tailwind layout patterns; responsive tables and forms
    - shadcn/ui setup and usage; Radix primitives
    - Accessible dialogs, dropdowns, tabs; data tables
  Learn
    [DOC] shadcn/ui - Vite install  https://ui.shadcn.com/docs/installation/vite
    [DOC] shadcn/ui components .... https://ui.shadcn.com/docs/components
    [DOC] Radix Primitives ........ https://www.radix-ui.com/primitives/docs/overview/introduction
    [DOC] TanStack Table .......... https://tanstack.com/table/latest
    [DOC] WAI-ARIA patterns ....... https://www.w3.org/WAI/ARIA/apg/patterns/
  Practice
    A polished, responsive settings page using shadcn/ui.

DAY 44 [React 29] - Performance and production readiness
  Topics
    - How rendering works; avoiding unnecessary renders
    - React.memo, useMemo, useCallback (and when NOT to use them)
    - React Compiler (automatic memoization)
    - Code splitting: lazy + Suspense; error boundaries
    - React DevTools Profiler
  Learn
    [DOC] memo .................... https://react.dev/reference/react/memo
    [DOC] useMemo ................. https://react.dev/reference/react/useMemo
    [DOC] useCallback ............. https://react.dev/reference/react/useCallback
    [DOC] lazy .................... https://react.dev/reference/react/lazy
    [DOC] React Compiler .......... https://react.dev/learn/react-compiler
    [DOC] Error boundaries ........ https://react.dev/reference/react/Component#catching-rendering-errors-with-an-error-boundary
    [DOC] react-error-boundary .... https://github.com/bvaughn/react-error-boundary
    [DOC] Profiler ................ https://react.dev/reference/react/Profiler
  Practice
    Profile a data-heavy product screen and remove wasted renders.
  Advanced
    - Virtualised long lists: https://tanstack.com/virtual/latest

DAY 45 [React 30] - PHASE 2 FINAL PROJECT: E-commerce + Deployment
  Requirements
    - Catalogue and detail pages; search, filters, sorting (in URL)
    - Cart with quantity logic (Redux Toolkit); wishlist
    - Checkout UI with RHF + Zod; order summary
    - API integration with TanStack Query
    - TypeScript throughout
    - Git workflow (feature branches + pull requests)
    - Production build and deployment
  Learn
    [DOC] Vite static deploy ...... https://vite.dev/guide/static-deploy
    [DOC] Vercel docs ............. https://vercel.com/docs
    [DOC] Netlify docs ............ https://docs.netlify.com/
    [ART] Learn Git Branching ..... https://learngitbranching.js.org/
  Note: SPA routing on Netlify/Vercel needs a rewrite rule so deep links
  (e.g. /products/5) do not return 404 on refresh.

PHASE 2 CHECKPOINT
You can build reusable typed React interfaces, forms, dashboards,
routing, API-driven CRUD screens, manage local/global/server state and
ship a complete deployed project.


================================================================================
4. PHASE 3 - NEXT.JS (DAYS 46-60)
================================================================================

GOAL
Learn the Next.js App Router and build fast, SEO-friendly websites with a
database-backed admin workflow and production deployment.

Main references for the whole phase
  [DOC] Next.js docs (App Router)  https://nextjs.org/docs/app
  [DOC] Next.js Learn (Dashboard)  https://nextjs.org/learn/dashboard-app
  [DOC] Next.js blog (releases) .. https://nextjs.org/blog

VERSION NOTE (Next.js 16)
  - "middleware.ts" was renamed to "proxy.ts" in Next.js 16.
  - Always check the version in package.json and read docs for that version.


--------------------------------------------------------------------------------
WEEK 7 - NEXT.JS FUNDAMENTALS
--------------------------------------------------------------------------------

DAY 46 [Next 1] - Next.js introduction
  Topics
    - What Next.js is; React vs Next.js; why use it
    - CSR vs SSR vs SSG vs ISR (concepts)
    - Create a Next.js TypeScript project; project structure
  Learn
    [DOC] Installation ............ https://nextjs.org/docs/app/getting-started/installation
    [DOC] Project structure ....... https://nextjs.org/docs/app/getting-started/project-structure
    [DOC] Rendering on the web (patterns.dev) https://www.patterns.dev/react/
  Practice
    Create and run a new Next.js project; explain each folder.

DAY 47 [Next 2] - App Router, layouts and pages
  Topics
    - app directory; page.tsx; layout.tsx; nested routes
    - Dynamic routes [slug]; route groups (folder); not-found.tsx
  Learn
    [DOC] Layouts and pages ....... https://nextjs.org/docs/app/getting-started/layouts-and-pages
    [DOC] Dynamic routes .......... https://nextjs.org/docs/app/api-reference/file-conventions/dynamic-routes
    [DOC] Route groups ............ https://nextjs.org/docs/app/api-reference/file-conventions/route-groups
    [DOC] not-found ............... https://nextjs.org/docs/app/api-reference/file-conventions/not-found
  Practice
    Home, About, Services and Contact pages with a shared layout.

DAY 48 [Next 3] - Server and Client Components
  Topics
    - React Server Components vs Client Components; "use client"
    - Server vs client responsibilities; composition patterns
    - Passing data from server to client; keeping secrets on the server
  Learn
    [DOC] Server and Client Components https://nextjs.org/docs/app/getting-started/server-and-client-components
    [DOC] "use client" directive .. https://react.dev/reference/rsc/use-client
    [DOC] Server Components (React) https://react.dev/reference/rsc/server-components
  Practice
    Server-rendered page with a client-side interactive menu.
  Check: Why can't you use useState inside a Server Component?

DAY 49 [Next 4] - Navigation and route UI
  Topics
    - next/link; prefetching; useRouter, usePathname, useSearchParams
    - Dynamic params; loading.tsx; error.tsx
  Learn
    [DOC] Linking and navigating .. https://nextjs.org/docs/app/getting-started/linking-and-navigating
    [DOC] Link component .......... https://nextjs.org/docs/app/api-reference/components/link
    [DOC] useSearchParams ......... https://nextjs.org/docs/app/api-reference/functions/use-search-params
    [DOC] loading.js .............. https://nextjs.org/docs/app/api-reference/file-conventions/loading
    [DOC] error.js ................ https://nextjs.org/docs/app/api-reference/file-conventions/error
    [DOC] Error handling .......... https://nextjs.org/docs/app/getting-started/error-handling
  Practice
    Service listing + dynamic service detail pages with loading/error UI.

DAY 50 [Next 5] - Data fetching
  Topics
    - Fetching in async Server Components; parallel vs sequential fetching
    - Streaming with Suspense
    - Caching and revalidation basics (Cache Components / "use cache")
  Learn
    [DOC] Fetching data ........... https://nextjs.org/docs/app/getting-started/fetching-data
    [DOC] Cache Components ........ https://nextjs.org/docs/app/getting-started/cache-components
    [DOC] Caching and revalidating  https://nextjs.org/docs/app/getting-started/caching-and-revalidating
  Practice
    Fetch and render service/product data with a streaming skeleton.

DAY 51 [Next 6] - Route Handlers and environment variables
  Topics
    - route.ts; GET/POST/PUT/PATCH/DELETE; Request and Response
    - Dynamic API segments; environment variables (server vs NEXT_PUBLIC_)
  Learn
    [DOC] Route handlers .......... https://nextjs.org/docs/app/getting-started/route-handlers
    [DOC] route.js reference ...... https://nextjs.org/docs/app/api-reference/file-conventions/route
    [DOC] Environment variables ... https://nextjs.org/docs/app/guides/environment-variables
  Practice
    A simple /api/services route; test it with Thunder Client or Postman.
  Security
    Only variables prefixed NEXT_PUBLIC_ reach the browser. Keep database
    URLs and API secrets WITHOUT that prefix.
  Note: If your company backend is a separate REST API (e.g. Laravel),
  you can call it directly from Server Components instead of building
  Route Handlers.

DAY 52 [Next 7] - WEEK 7 PROJECT: Multi-page Business Website
  Requirements
    - Home, About, Services, dynamic Service details, Contact
    - Shared header/footer; responsive design; loading and 404 pages
  Pro features (optional)
    - Statically generate service pages with generateStaticParams
      https://nextjs.org/docs/app/api-reference/functions/generate-static-params


--------------------------------------------------------------------------------
WEEK 8 - ADVANCED NEXT.JS
--------------------------------------------------------------------------------

DAY 53 [Next 8] - SEO and metadata
  Topics
    - Metadata API; static and dynamic metadata (generateMetadata)
    - Open Graph images; canonical URLs; robots.txt; sitemap.xml
    - Structured data (JSON-LD)
  Learn
    [DOC] Metadata and OG images .. https://nextjs.org/docs/app/getting-started/metadata-and-og-images
    [DOC] generateMetadata ........ https://nextjs.org/docs/app/api-reference/functions/generate-metadata
    [DOC] sitemap.xml ............. https://nextjs.org/docs/app/api-reference/file-conventions/metadata/sitemap
    [DOC] robots.txt .............. https://nextjs.org/docs/app/api-reference/file-conventions/metadata/robots
    [DOC] JSON-LD guide ........... https://nextjs.org/docs/app/guides/json-ld
    [ART] Google SEO Starter Guide  https://developers.google.com/search/docs/fundamentals/seo-starter-guide
  Practice
    Unique metadata + OG image for every page; generate a sitemap.

DAY 54 [Next 9] - Images, fonts and assets
  Topics
    - next/image (sizes, priority, remote patterns); responsive images
    - next/font; font optimisation; static assets in public/
  Learn
    [DOC] Images .................. https://nextjs.org/docs/app/getting-started/images
    [DOC] Image component ......... https://nextjs.org/docs/app/api-reference/components/image
    [DOC] Fonts ................... https://nextjs.org/docs/app/getting-started/fonts
    [WEB] Largest Contentful Paint  https://web.dev/articles/lcp
  Practice
    Optimise the business website's images and fonts; compare Lighthouse.

DAY 55 [Next 10] - Forms and Server Actions
  Topics
    - Server Actions / Server Functions; form submissions
    - Zod validation on the server; useActionState; pending UI
    - revalidatePath after mutations
  Learn
    [DOC] Updating data ........... https://nextjs.org/docs/app/getting-started/updating-data
    [DOC] Forms guide ............. https://nextjs.org/docs/app/guides/forms
    [DOC] useActionState .......... https://react.dev/reference/react/useActionState
    [DOC] useFormStatus ........... https://react.dev/reference/react-dom/hooks/useFormStatus
  Practice
    Contact form with server-side Zod validation and success/error states.
  Security
    Always re-validate and check auth INSIDE every Server Action.

DAY 56 [Next 11] - Authentication and access control
  Topics
    - Sessions and cookies; login/registration; protected pages
    - Authorization (roles); Proxy (formerly Middleware) for redirects
    - Data Access Layer pattern; never expose secrets to the client
  Learn
    [DOC] Authentication guide .... https://nextjs.org/docs/app/guides/authentication
    [DOC] Data security guide ..... https://nextjs.org/docs/app/guides/data-security
    [DOC] Proxy ................... https://nextjs.org/docs/app/getting-started/proxy
    [DOC] proxy.js reference ...... https://nextjs.org/docs/app/api-reference/file-conventions/proxy
    [DOC] Auth.js ................. https://authjs.dev/
    [DOC] Better Auth ............. https://www.better-auth.com/docs
  Practice
    Protected /admin area using an auth library.
  Important: Proxy is a first gate only. Check the session again in the
  page, Route Handler or Server Action that reads/changes data.

DAY 57 [Next 12] - Database integration
  Topics
    - Relational database concepts; PostgreSQL (or MySQL) basics
    - Prisma ORM: schema, models, migrations, Prisma Client, CRUD
    - Secure connection strings; avoiding N+1 queries
  Learn
    [DOC] PostgreSQL tutorial ..... https://www.postgresql.org/docs/current/tutorial.html
    [DOC] Prisma getting started .. https://www.prisma.io/docs/getting-started
    [DOC] Prisma schema ........... https://www.prisma.io/docs/orm/prisma-schema
    [DOC] Prisma + Next.js guide .. https://www.prisma.io/docs/guides/nextjs
    [DOC] Neon (free Postgres) .... https://neon.com/docs/introduction
    [DOC] Drizzle ORM (alternative) https://orm.drizzle.team/docs/overview
    [ART] SQLBolt (SQL practice) .. https://sqlbolt.com/
  Practice
    Save and list contact-form submissions and services.
  Note: Prisma also supports MySQL if that is your team's standard.

DAY 58 [Next 13] - Advanced rendering and caching
  Topics
    - Static vs dynamic rendering; ISR; on-demand revalidation
    - Partial Prerendering / Cache Components; streaming
    - Parallel and intercepting routes (e.g. modal routes)
  Learn
    [DOC] ISR guide ............... https://nextjs.org/docs/app/guides/incremental-static-regeneration
    [DOC] revalidatePath .......... https://nextjs.org/docs/app/api-reference/functions/revalidatePath
    [DOC] Parallel routes ......... https://nextjs.org/docs/app/api-reference/file-conventions/parallel-routes
    [DOC] Intercepting routes ..... https://nextjs.org/docs/app/api-reference/file-conventions/intercepting-routes
  Practice
    Revalidate the services page when an admin edits a service.

DAY 59 [Next 14] - Production and deployment
  Topics
    - GitHub repo; env variables per environment; production build
    - Vercel deployment; Node.js/VPS/Docker hosting
    - Custom domain, SSL; reading build errors; production checklist
  Learn
    [DOC] Deploying ............... https://nextjs.org/docs/app/getting-started/deploying
    [DOC] Self-hosting guide ...... https://nextjs.org/docs/app/guides/self-hosting
    [DOC] Production checklist .... https://nextjs.org/docs/app/guides/production-checklist
    [DOC] Vercel - Next.js ........ https://vercel.com/docs/frameworks/full-stack/nextjs
  Practice
    Deploy and test every production route (including 404 and errors).

DAY 60 [Next 15] - PHASE 3 FINAL PROJECT: Dynamic CMS Company Website
  Requirements
    - Public pages; dynamic service details
    - Admin login; protected admin pages; content CRUD
    - Contact form with Server Actions + Zod; database (Prisma)
    - SEO metadata, sitemap, robots; image optimisation
    - Production deployment with custom domain
  Pro features (optional)
    - Image uploads (e.g. UploadThing or S3-compatible storage)
    - Draft/publish workflow; audit log of admin changes

PHASE 3 CHECKPOINT
You understand the App Router, Server/Client Components, data fetching
and caching, metadata, Server Actions, Route Handlers, auth, database
access and deployment.


================================================================================
5. PHASE 4 - ADVANCED TRACK (OPTIONAL, DAYS 61-75)
================================================================================

Do this after Day 60, or mix one topic per week into earlier phases.
These are the skills that separate a junior from a strong mid-level
frontend developer.

DAY 61 [Adv 1] - Testing I: Unit and component tests
  Topics: Vitest, React Testing Library, user-event, testing hooks
  Learn
    [DOC] Vitest guide ............ https://vitest.dev/guide/
    [DOC] React Testing Library ... https://testing-library.com/docs/react-testing-library/intro/
    [DOC] Which query to use ...... https://testing-library.com/docs/queries/about/#priority
    [ART] Common RTL mistakes (Kent C. Dodds)
          https://kentcdodds.com/blog/common-mistakes-with-react-testing-library
  Practice: Test the cart reducer and the registration form.

DAY 62 [Adv 2] - Testing II: API mocking and end-to-end tests
  Topics: Mock Service Worker, Playwright, testing auth flows
  Learn
    [DOC] MSW ..................... https://mswjs.io/docs/
    [DOC] Playwright intro ........ https://playwright.dev/docs/intro
    [DOC] Next.js testing guide ... https://nextjs.org/docs/app/guides/testing
  Practice: E2E test: login -> add product to cart -> checkout.

DAY 63 [Adv 3] - Accessibility (a11y) in depth
  Topics: WCAG 2.2 AA, semantic HTML, keyboard navigation, focus
          management, ARIA, colour contrast, screen-reader testing
  Learn
    [WEB] Learn Accessibility ..... https://web.dev/learn/accessibility
    [DOC] WCAG 2.2 Quick Reference  https://www.w3.org/WAI/WCAG22/quickref/
    [DOC] ARIA Authoring Practices  https://www.w3.org/WAI/ARIA/apg/
    [ART] WebAIM contrast checker . https://webaim.org/resources/contrastchecker/
    [DOC] axe DevTools ............ https://www.deque.com/axe/devtools/
  Practice: Audit and fix one of your portfolio projects to WCAG AA.

DAY 64 [Adv 4] - Web performance and Core Web Vitals
  Topics: LCP, INP, CLS; Lighthouse; bundle analysis; image/font/JS
          optimisation; caching headers
  Learn
    [WEB] Core Web Vitals ......... https://web.dev/articles/vitals
    [WEB] Learn Performance ....... https://web.dev/learn/performance
    [WEB] Lighthouse .............. https://developer.chrome.com/docs/lighthouse/overview
    [WEB] Performance panel ....... https://developer.chrome.com/docs/devtools/performance
    [DOC] Next.js lazy loading .... https://nextjs.org/docs/app/guides/lazy-loading
  Practice: Get a 90+ Lighthouse performance score on mobile.

DAY 65 [Adv 5] - Frontend security
  Topics: XSS, CSRF, CSP, secure cookies, dependency auditing (npm audit),
          dangerouslySetInnerHTML risks, sanitising HTML (DOMPurify)
  Learn
    [ART] OWASP XSS Prevention .... https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html
    [ART] OWASP CSRF Prevention ... https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html
    [MDN] Content Security Policy . https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP
    [DOC] Next.js CSP guide ....... https://nextjs.org/docs/app/guides/content-security-policy
    [DOC] DOMPurify ............... https://github.com/cure53/DOMPurify
    [DOC] OWASP Top 10 ............ https://owasp.org/www-project-top-ten/
  Practice: Add a CSP and security headers to your Next.js project.

DAY 66 [Adv 6] - Modern React 19 features
  Topics: Actions, useActionState, useOptimistic, use(), form actions,
          ref as a prop, React Compiler in practice
  Learn
    [DOC] React 19 release post ... https://react.dev/blog/2024/12/05/react-19
    [DOC] useOptimistic ........... https://react.dev/reference/react/useOptimistic
    [DOC] use ..................... https://react.dev/reference/react/use
    [DOC] React blog (latest) ..... https://react.dev/blog
  Practice: Optimistic "like" button and comment form.

DAY 67 [Adv 7] - Advanced CSS for developers
  Topics: Container queries, :has(), cascade layers, logical properties,
          fluid typography with clamp(), view transitions
  Learn
    [MDN] Container queries ....... https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_containment/Container_queries
    [MDN] :has() .................. https://developer.mozilla.org/en-US/docs/Web/CSS/:has
    [MDN] Cascade layers .......... https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Cascade_layers
    [MDN] clamp() ................. https://developer.mozilla.org/en-US/docs/Web/CSS/clamp
    [MDN] View Transition API ..... https://developer.mozilla.org/en-US/docs/Web/API/View_Transition_API
    [ART] Utopia (fluid type scale) https://utopia.fyi/
  Practice: A card component that adapts to its container, not the screen.

DAY 68 [Adv 8] - Animation and micro-interactions
  Topics: CSS transitions/keyframes, Motion for React, reduced motion
  Learn
    [MDN] CSS animations .......... https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations/Using_CSS_animations
    [DOC] Motion for React ........ https://motion.dev/docs/react
    [MDN] prefers-reduced-motion .. https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion
  Practice: Animated page transitions and an accessible animated menu.

DAY 69 [Adv 9] - Design systems and Storybook
  Topics: Design tokens, component APIs, variants (cva), documentation,
          Figma-to-code handoff, visual regression basics
  Learn
    [DOC] Storybook docs .......... https://storybook.js.org/docs
    [DOC] class-variance-authority  https://cva.style/docs
    [DOC] Figma Dev Mode .......... https://www.figma.com/dev-mode/
    [ART] Design Systems Handbook . https://www.designbetter.co/design-systems-handbook
  Practice: Document Button, Input, Card and Modal in Storybook.

DAY 70 [Adv 10] - Code quality and CI/CD
  Topics: ESLint + Prettier in CI, Husky + lint-staged, conventional
          commits, GitHub Actions (lint, type-check, test, build), PR reviews
  Learn
    [DOC] GitHub Actions .......... https://docs.github.com/en/actions
    [DOC] Husky ................... https://typicode.github.io/husky/
    [DOC] lint-staged ............. https://github.com/lint-staged/lint-staged
    [DOC] Conventional Commits .... https://www.conventionalcommits.org/
  Practice: A CI pipeline that blocks merging if tests or types fail.

DAY 71 [Adv 11] - Real-time features
  Topics: WebSockets, Server-Sent Events, polling vs push, live UI updates
  Learn
    [MDN] WebSockets API .......... https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API
    [MDN] Server-sent events ...... https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events
    [DOC] Socket.IO ............... https://socket.io/docs/v4/
  Practice: Live notification bell or simple chat room.

DAY 72 [Adv 12] - Internationalisation (i18n)
  Topics: Locale routing, translations, date/number/currency formatting,
          RTL layouts
  Learn
    [DOC] Next.js i18n guide ...... https://nextjs.org/docs/app/guides/internationalization
    [DOC] next-intl ............... https://next-intl.dev/docs/getting-started
    [MDN] Intl API ................ https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl
  Practice: English + Hindi (or Gujarati) version of the business website.

DAY 73 [Adv 13] - Monitoring, analytics and error tracking
  Topics: Error tracking, performance monitoring, product analytics,
          logging in production
  Learn
    [DOC] Sentry for Next.js ...... https://docs.sentry.io/platforms/javascript/guides/nextjs/
    [DOC] Vercel Analytics ........ https://vercel.com/docs/analytics
  Practice: Add Sentry and track a custom error.

DAY 74 [Adv 14] - Frontend system design + PWA
  Topics: Architecture for large apps, rendering strategy choice,
          state strategy, caching, monorepos, Progressive Web Apps
  Learn
    [ART] Front End System Design Playbook https://www.greatfrontend.com/front-end-system-design-playbook
    [ART] patterns.dev ............ https://www.patterns.dev/
    [WEB] Learn PWA ............... https://web.dev/learn/pwa
    [DOC] Turborepo ............... https://turborepo.com/docs
  Practice: Write a 1-page design doc for your CMS project.

DAY 75 [Adv 15] - CAPSTONE: SaaS-style Product
  Build a multi-user SaaS dashboard (e.g. invoice or project manager):
    - Next.js + TypeScript + Prisma + auth with roles (owner/admin/member)
    - TanStack Query or Server Actions; RHF + Zod forms
    - Data tables, charts, dark mode, i18n
    - Unit + E2E tests, CI pipeline, Sentry, Lighthouse 90+, WCAG AA
    - Deployed with custom domain and a detailed README + case study


================================================================================
6. PORTFOLIO PROJECTS
================================================================================

For each project: live URL, GitHub repo, README with screenshots,
tech stack, features, and "challenges I solved".

PROJECT 1 - E-COMMERCE FRONTEND (React + TypeScript)
  Standard: Listing + detail pages, search/filter/sort, cart, wishlist,
            checkout UI, Redux Toolkit, API integration
  Pro:      URL-synced filters, optimistic cart, skeleton loaders,
            Lighthouse 90+, unit tests for cart logic

PROJECT 2 - ADMIN DASHBOARD (React + TypeScript)
  Standard: Login, analytics cards/charts, user & record management,
            CRUD, TanStack Query, RHF + Zod, responsive tables and forms
  Pro:      Role-based access, TanStack Table with server-side
            pagination, CSV export, dark mode, E2E tests

PROJECT 3 - BUSINESS WEBSITE (Next.js)
  Standard: Home, About, Services, dynamic service pages, responsive UI,
            SEO metadata, contact form, image optimisation
  Pro:      JSON-LD, OG images, 95+ Lighthouse, i18n, animations

PROJECT 4 - DYNAMIC CMS WEBSITE (Next.js full stack)
  Standard: Public site, admin panel, auth and access control,
            DB-backed content, page/service management, SEO and image
            management, contact submissions, deployment
  Pro:      Draft/publish, image upload, audit log, CI/CD, Sentry

Portfolio inspiration
  [ART] Frontend Mentor (real designs to build) https://www.frontendmentor.io/challenges
  [ART] roadmap.sh project ideas  https://roadmap.sh/frontend/projects


================================================================================
7. VIDEO COURSES (HINDI + ENGLISH)
================================================================================

Choose ONE main course per phase. Do not try to watch everything. Use the
official docs as the reference and build your own projects alongside.

A. JAVASCRIPT
  1. Chai aur JavaScript - Hitesh Choudhary (Hindi)
     https://www.youtube.com/playlist?list=PLu71SKxNbfoBuX3f4EOACle2y-tRC5Q37
  2. JavaScript Tutorials for Beginners - CodeWithHarry (Hindi)
     https://www.youtube.com/playlist?list=PLu0W_9lII9ahR1blWXxgSlL4y9iQBnLpR
  3. Namaste JavaScript - Akshay Saini (Hinglish, deep concepts)
     https://www.youtube.com/playlist?list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP
  4. javascript.info - written tutorial ... https://javascript.info/
  5. MDN JavaScript Guide ................. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide
  Use: Chai aur JS or CodeWithHarry for structure; Namaste JS for
  closures, hoisting, event loop; javascript.info + MDN for reference.

B. REACT.JS
  1. Chai aur React - Hitesh Choudhary (Hindi)
     https://www.youtube.com/playlist?list=PLu71SKxNbfoBAaWGtn9GA2PTw0HO0tXzq
  2. React JS Tutorials - CodeWithHarry (Hindi)
     https://www.youtube.com/playlist?list=PLu0W_9lII9agx66oZnT6IyhcMIbUMNMdt
  3. React JS - WsCube Tech (Hindi)
     https://www.youtube.com/playlist?list=PLjVLYmrlmjGdnIQKgnTeR1T9-1ltJEaJh
  4. Official React Learn ................. https://react.dev/learn
  5. React Foundations (Next.js course) ... https://nextjs.org/learn/react-foundations
  6. React Router docs .................... https://reactrouter.com/start/library/installation
  7. Redux Toolkit docs ................... https://redux-toolkit.js.org/tutorials/overview
  8. TanStack Query docs .................. https://tanstack.com/query/latest/docs/framework/react/overview
  9. TypeScript Handbook .................. https://www.typescriptlang.org/docs/handbook/intro.html
 10. Zod docs ............................. https://zod.dev/
 11. React Hook Form docs ................. https://react-hook-form.com/
 12. Tailwind CSS docs .................... https://tailwindcss.com/docs
 13. shadcn/ui docs ....................... https://ui.shadcn.com/docs
  Use: One complete video course for basics; react.dev for current
  patterns. Older videos may use Create React App (deprecated) - use
  Vite instead.

C. NEXT.JS
  1. Next.js Full Course in Hindi - Virtual Code
     https://www.youtube.com/watch?v=Mct6dyl_gz4
  2. Next.js Tutorials - CodeWithHarry (Hindi)
     https://www.youtube.com/playlist?list=PLu0W_9lII9agtWvR_TZdb_r0dNI8-lDwG
  3. Chai aur Code - Next.js videos (Hindi)
     https://www.youtube.com/@chaiaurcode/search?query=nextjs
     (FIXED: the old file linked this item to the Chai aur React
      playlist by mistake.)
  4. Next.js Learn (official) ............ https://nextjs.org/learn
  5. App Router docs ...................... https://nextjs.org/docs/app
  6. Deployment docs ...................... https://nextjs.org/docs/app/getting-started/deploying
  Use: Videos for walkthroughs; official docs as source of truth. Check
  that a video's Next.js version matches yours (v16 renamed middleware
  to proxy, and caching changed in v15/v16).

D. GIT AND DEPLOYMENT
  Pro Git book (free) ...... https://git-scm.com/book/en/v2
  Learn Git Branching ...... https://learngitbranching.js.org/
  GitHub Skills ............ https://skills.github.com/
  Vercel docs .............. https://vercel.com/docs
  Netlify docs ............. https://docs.netlify.com/

E. ADVANCED / ENGLISH (optional, for depth)
  Full Stack Open (free university course, React + Node + TS + testing)
     https://fullstackopen.com/en/
  The Odin Project - Full Stack JavaScript (free)
     https://www.theodinproject.com/paths/full-stack-javascript
  Epic React (paid, Kent C. Dodds) .. https://www.epicreact.dev/
  Josh Comeau's blog (CSS & React) .. https://www.joshwcomeau.com/


================================================================================
8. PRACTICE PLATFORMS, FREE APIs AND DESIGN SOURCES
================================================================================

Practice
  Frontend Mentor (design-to-code) .. https://www.frontendmentor.io/
  JavaScript30 (30 vanilla JS builds) https://javascript30.com/
  Exercism JavaScript track ......... https://exercism.org/tracks/javascript
  Type Challenges (TypeScript) ...... https://github.com/type-challenges/type-challenges
  roadmap.sh Frontend ............... https://roadmap.sh/frontend
  roadmap.sh React .................. https://roadmap.sh/react

Free test APIs
  DummyJSON (products, users, auth) . https://dummyjson.com/
  JSONPlaceholder ................... https://jsonplaceholder.typicode.com/
  Fake Store API .................... https://fakestoreapi.com/
  JSON Server (run your own) ........ https://github.com/typicode/json-server
  Public APIs list .................. https://github.com/public-apis/public-apis

Design sources (for Figma-to-code practice)
  Figma Community ................... https://www.figma.com/community
  Frontend Mentor designs ........... https://www.frontendmentor.io/challenges
  Dribbble (inspiration only) ....... https://dribbble.com/


================================================================================
9. INTERVIEW PREPARATION
================================================================================

Topics interviewers commonly ask
  JS:     closures, this, hoisting, event loop, promises, debounce/throttle,
          deep vs shallow copy, == vs ===, prototypes
  React:  rendering and reconciliation, keys, state vs props, effects,
          memoization, context vs Redux, controlled inputs, custom hooks
  Next:   SSR vs SSG vs ISR, Server vs Client Components, caching,
          Server Actions, SEO, auth and Proxy
  Web:    HTTP, CORS, cookies, accessibility, Core Web Vitals, security

Resources
  GreatFrontEnd (questions + system design) https://www.greatfrontend.com/
  BigFrontEnd.dev (coding problems) ......... https://bigfrontend.dev/
  javascript.info tasks ..................... https://javascript.info/

Practice: Explain each portfolio project in 2 minutes - problem, stack,
your hardest bug, and what you would improve.


================================================================================
10. LEARNING ADVICE FOR WEB DESIGNERS
================================================================================

 1. Your design eye is an advantage - keep improving spacing,
    typography, hierarchy and responsive behaviour.
 2. Before coding a Figma screen, sketch its component tree.
 3. Test at 360px, 768px, 1024px and 1440px widths every time.
 4. Live in DevTools: Elements, Console, Network, Lighthouse.
 5. Always design and build loading, empty, error and success states.
 6. Use Git from Day 1 - commit small and often with clear messages.
 7. Switch to TypeScript from Day 37 onward.
 8. Understand the split: frontend UI vs backend API vs database.
 9. Never put private API keys, DB credentials or secret tokens in
    client-side code or NEXT_PUBLIC_/VITE_ variables.
10. Accessibility is not optional - keyboard + screen-reader friendly.
11. Read error messages fully before searching; write down each fix.
12. Use AI assistants to EXPLAIN code and review yours, not to write
    projects you cannot explain.
13. Build at least 3-4 portfolio projects you can demo and explain.


================================================================================
11. SUGGESTED TOOLKIT
================================================================================

Core      : VS Code, Node.js LTS, npm (or pnpm), Git, GitHub, Chrome DevTools
Build     : Vite, Next.js 16
UI        : React 19, Tailwind CSS 4, shadcn/ui, Radix, Motion
Routing   : React Router 7 (Vite apps), App Router (Next.js)
Data      : Fetch / Axios, TanStack Query, Redux Toolkit (or Zustand)
Forms     : React Hook Form, Zod
Language  : TypeScript
Backend   : Route Handlers / Server Actions, Prisma, PostgreSQL or MySQL
Auth      : Auth.js or Better Auth
Quality   : ESLint, Prettier, Vitest, React Testing Library, Playwright
Ops       : Vercel / Netlify, GitHub Actions, Sentry
API tools : Thunder Client (VS Code) or Postman


================================================================================
12. PROGRESS TRACKER
================================================================================

Mark each day:  [ ] not started   [~] in progress   [x] done

Phase 1 (JS)       : [ ]1  [ ]2  [ ]3  [ ]4  [ ]5  [ ]6  [ ]7  [ ]8
                     [ ]9  [ ]10 [ ]11 [ ]12 [ ]13 [ ]14 [ ]15
Phase 2 (React)    : [ ]16 [ ]17 [ ]18 [ ]19 [ ]20 [ ]21 [ ]22 [ ]23
                     [ ]24 [ ]25 [ ]26 [ ]27 [ ]28 [ ]29 [ ]30 [ ]31
                     [ ]32 [ ]33 [ ]34 [ ]35 [ ]36 [ ]37 [ ]38 [ ]39
                     [ ]40 [ ]41 [ ]42 [ ]43 [ ]44 [ ]45
Phase 3 (Next.js)  : [ ]46 [ ]47 [ ]48 [ ]49 [ ]50 [ ]51 [ ]52 [ ]53
                     [ ]54 [ ]55 [ ]56 [ ]57 [ ]58 [ ]59 [ ]60
Phase 4 (Advanced) : [ ]61 [ ]62 [ ]63 [ ]64 [ ]65 [ ]66 [ ]67 [ ]68
                     [ ]69 [ ]70 [ ]71 [ ]72 [ ]73 [ ]74 [ ]75

FINAL CAREER PATH
Web Designer -> Frontend Developer -> React Developer -> Next.js
Developer -> Full-stack / Senior Frontend Engineer

By the end you should independently be able to:
  - Convert a Figma design into a responsive, accessible website
  - Build reusable typed components, layouts and design systems
  - Build interactive forms, dashboards and data tables
  - Integrate REST APIs and manage local, global and server state
  - Build SEO-friendly, fast Next.js websites
  - Connect to a database with a secure, protected admin workflow
  - Test, monitor, deploy and maintain production projects

END OF ROADMAP
