# `@lukasnys/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @lukasnys/streak-counter
```

```shell
npm install @lukasnys/streak-counter
```

## Usage

```js
import { streakCounter } from "@lukasnys/streak-counter";

const today = new Date();
const streak = streakCounter(localStorage, today);
// streak returns an object:
// {
//      currentStreak: 1,
//      lastLoginDate: "11/11/2021",
//      startDate: "11/11/2021",
// }
```
