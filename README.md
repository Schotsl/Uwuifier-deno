# Project Title

Uwuifier is a lightweight package that allows you to uwuify any sentence or word (excluding URL's) with many configurable parameters while giving you access to many vewy kawaii sentences, stuttering and faces!

This repository contains the Uwuifier Deno package!  It's a Deno package which means it's written in TypeScript, and makes use of the build-in Deno testing.

## Quickstart

```typescript
// Import the Uwuifier package
import { Uwuifier } from 'https://deno.land/x/uwuifier/src/index.ts';

// Create a "Uwuifier" instance
const uwuifier = new Uwuifier();

// Uwuifiy a sentence
console.log(uwuifier.uwuifySentence('This package is amazing!'));
```

## Developing the package

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

Deno automaticly downloads the dependencies, so the only thing you need to get started is [install Deno](https://deno.land/manual/getting_started/installation) and install [Denon](https://deno.land/x/denon@2.4.5) if you wanna make use of hot reloading:

```bash
deno install -qAf --unstable https://deno.land/x/denon@2.4.4/denon.ts
```

Then you can finish the Denon install by following the instructions from the terminal!

### Compiling

#### Execute

```bash
deno run index.ts
```

#### Hot-reload

```bash
denon run index.ts
```

#### Lint files

```bash
deno lint --unstable
```

#### Testing

```bash
deno test
```

## Deployment

The code will be deployed every at every version release, every commit will be linted and tested with the help of GitHub Actions

## Built With

* [Seed](https://github.com/Schotsl/Seed) - Seeded generated used to keep the results consistent

## Acknowledgement

I was inspired to write this god awful package by this site, I would've given full credit but it appears he got most of the Regex from the OwO Google Chrome extension made by leafysweetsgarden, I would include a link but the page is offline. So short story short: I'd like to give a big thanks to leafysweetsgarden for the Regex and the inspiration!


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
