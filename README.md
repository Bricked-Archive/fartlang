# FARTlang 💨

[![license](https://custom-icon-badges.demolab.com/github/license/brckd/fartlang?logo=law)](LICENSE.md)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![version](https://img.shields.io/npm/v/@bricked/fartlang?color=crimson&logo=npm)](https://www.npmjs.com/package/@bricked/fartlang)

The first ever Fanscript targeting Advanced and Robust Text-based language preprocessor.

> [!Warning]
> This project has been archived, as it was meant as a joke and I'll try to make it in Rust later.

## Usage

FARTscript will be written in different flavours to support FARTscripters from any kind of programming background. It's definitely not because I'm too lazy to make up my own syntax or decide on an existing one.

### FARTthon
```py
$you = player(0.1) # place down player block

def grass player(self, speed): # define player block
    position, rotation = get_position(self)
    position += vector(0, 0, speed)
    set_position(self, position)
```

### JavaFART
```js
$you = player(0.1) // place down player block

// define player block
function grass player(speed) {
    [position, rotation] = getPosition(this)
    position += vector(0, 0, speed)
    setPosition(this, position)
}
```

*insert syntax of other popular programming languages*

### FARTy
(my favorite)

```lisp
set $you (player 0.1) ; place down player block

grass player (self) (speed): ; define player block
    set position (get_position self)
    increase position (vector 0 0 (get speed))
    set_position self position

def increase (var) (increment): ; define macro or something
    set var (add (get var) increment)
```


## Installation

[Node.js](https://nodejs.org/) 16.14.0 or newer is required.

```sh
npm install @bricked/fartlang
yarn add @bricked/fartlang
pnpm add @bricked/fartlang
```

## Building

### Building Publicly

Pulls to the repository will automatically be built with [semantic-release](https://github.com/semantic-release/npm).
The built package can be found on [npm](https://www.npmjs.com/package/@bricked/fartlang?activeTab=code) or in the
[latest github release](https://github.com/brckd/fartlang/releases/latest).

### Building Locally

The package can also be built locally using the `build` script.

```sh
npm run build
yarn run build
pnpm run build
```
