# What Is Riot?

Riot is a `javascript` library designed to help build rich, interactive, web experiences contained in a small package that compliments the core web stack (html, css, javascript) -- without imposing any crazy syntax or tooling.

By if that isn't good enough for you, Riot defines itself as

"A React-like user interface micro-library"

Riot, while small, includes essentials building-blocks around three core capibilites to help you develop your next modern client-side web application: 

- **Custom Tags**  to build custom web-components that takes care of the user interface.
- **A Router** for URL negotation with the back button support
- **And A Event Emmitter (observable)** to tie components together and bring modularity, 

Riot tries not to enforce strict rules, but rather provide basic building-blocks to use creatively. This flexible approach defers the larger architectural decisions up to the developer.

## Features

### Build system optional

The compiler weights only 3.2KB (1.7K gzipped) so you can safely perform client-side compilation on production without download or performance or issues.

### Concise syntax

- Power shortcuts: class={ enabled: is_enabled, hidden: hasErrors() }.
- No extra brain load such as render, state, constructor or shouldComponentUpdate
- Interpolation: Add #{ items.length + 1 } or class="item { selected: flag }"
- Compact ES6 method syntax.
- Only 9 public methods

### Virtual DOM

- Absolutely the smallest possible amount of DOM updates and reflows.
- One way data flow: updates and `unmounts` are propagated downwards from parent to children.
- Expressions are pre-compiled and cached for high performance.
- Lifecycle events for more control.

### Close to standards

- No proprietary event system.
- Event normalization.
- The rendered DOM can be freely manipulated with other tools.
- No extra HTML root elements or data- attributes.
- Plays well with jQuery.

### Use Your Tools

- Create tags with CoffeeScript, Jade, LiveScript, Typescript, ES6 or any pre-processor you want.
- Integrate with NPM, CommonJS, AMD, Bower or Component
- Develop with Gulp, Grunt, Browserify, or Wintersmith plugins
