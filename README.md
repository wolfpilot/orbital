# Orbital

## NOTE: This is a WIP.

In the meantime, feel free to check out my other pinned [repos](https://github.com/wolfpilot)!

## Table of contents

- [Intro](#intro)
- [Demo](#demo)
- [Features (done)](#features-done)
- [Features (TBA)](#features-tba)
- [Technologies](#technologies)
- [Getting started](#getting-started)
- [License](#license)

## Intro

_“It is a beautiful and delightful sight to behold the body of the Moon.”_

_― Galileo Galilei, The Starry Messenger, Venice 1610_

Visualize planet orbits. Wind, unwind, have fun and learn.

## Demo

## Features (done)

## Features (TBA)

## Technologies

## Getting started

### Requirements

- [Pnpm](https://pnpm.io/) (built on v9.1.4)
- [Docker](https://www.docker.com/) (built on v27.2.0)

### Installation

```bash
$ git clone https://github.com/wolfpilot/orbital.git
$ cd orbital
$ pnpm install
```

### How to run

```bash
# Grab the latest image
docker pull wolfpilot/orbital:latest

# Run a local container
docker run -d -p 8080:80 orbital

# Visit http://localhost:8080/ in your browser
```

### Scripts

```bash
# Compiles and hot-reloads for development
pnpm serve
```

```bash
# Compiles and minifies for production
pnpm build
```

```bash
# Lints and fixes files
pnpm lint
```

### Customize configuration

See [Vue Configuration Reference](https://cli.vuejs.org/config/).

## License

This project is licensed under the [MIT License](LICENSE).
