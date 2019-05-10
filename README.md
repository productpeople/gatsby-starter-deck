# gatsby-starter-deck

[![dependencies](https://img.shields.io/david/fabe/gatsby-starter-deck.svg)](./package.json)
[![deploys by netlify](https://img.shields.io/badge/deploys%20by-netlify-00c7b7.svg)](https://www.netlify.com)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

Create presentations using Gatsby, React & Markdown. Inspired by Guillermo Rauch’s [deck on Next.js](https://deck.now.sh/) and [mdx-deck](https://github.com/jxnblk/mdx-deck).

➡️ **[See a live example](//gatsby-deck.netlify.com)**

## Installation

### With [`gatsby-cli`](https://www.npmjs.com/package/gatsby-cli)

```bash
$ gatsby new my-slides https://github.com/fabe/gatsby-starter-deck
```

### With `git clone`

```bash
$ git clone git@github.com:fabe/gatsby-starter-deck.git my-slides
$ cd my-slides
$ yarn
```

## Usage

Edit and extend your slides inside the `src/slides.md` file. Navigate with the arrow keys.

```bash
# To develop & write
$ yarn develop

# To build
$ yarn build
```

## Writing

By default, use [src/slides/](src/slides/).

Markdown files are loaded in sorted path order. Slides are generated by
splitting each markdown file along `<hr/>` elements (`---` in Markdown lingo).

- Fabian Schultz ([@fschultz\_](https://twitter.com/fschultz_))
- Frank Murphy ([AnIrishDuck](https://github.com/AnIrishDuck))
