# 🎚 React Smooth Input Range

[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=🎚+React+Smooth+Range+Input&url=https://github.com/bluebill1049/react-smooth-range-input/) [![CircleCI](https://circleci.com/gh/bluebill1049/react-smooth-range-input.svg?style=svg)](https://circleci.com/gh/bluebill1049/react-smooth-range-input) [![Coverage Status](https://coveralls.io/repos/github/bluebill1049/react-smooth-range-input/badge.svg?branch=master)](https://coveralls.io/github/bluebill1049/react-smooth-range-input?branch=master) [![npm downloads](https://img.shields.io/npm/dm/react-smooth-range-input.svg?style=flat-square)](https://www.npmjs.com/package/react-smooth-range-input) [![npm](https://img.shields.io/npm/dt/react-smooth-range-input.svg?style=flat-square)](https://www.npmjs.com/package/react-smooth-range-input) [![npm](https://img.shields.io/npm/l/react-smooth-range-input.svg?style=flat-square)](https://www.npmjs.com/package/react-smooth-range-input)

## Features:

- Butter smooth input range
- Beautiful animation interaction
- Tiny size

## Install

    $ npm install react-smooth-range-input

## Example

<p>
    <a href="https://react-smooth-range-input.now.sh" target="_blank">
        <img height="500" src="https://raw.githubusercontent.com/bluebill1049/react-smooth-range-input/master/example/example.gif" alt="https://react-smooth-range-input.now.sh" />
    </a>
</p>

Navigate into `example` folder and install

    yarn && yarn start || npm install && npm run start

😍 <a href="https://react-smooth-range-input.now.sh" target="_blank">Check it out.</a>

## Quickstart

```jsx
import react from 'react';
import Slider from 'react-smooth-range-input';

export default () => <Slider value={1} min={1} max={30} />;
```

## Props

| Prop                  | Type           | Required | Description                              |
| :-------------------- | :------------- | :------: | :--------------------------------------- |
| `value`               | number         |    ✓     | current value                            |
| `min`                 | number         |    ✓     | min number range                         |
| `max`                 | number         |    ✓     | max number range                         |
| `onChange`            | Function       |          | on value change callback                 |
| `type`                | string         |          | two types: 'thick' and 'thin'            |
| `textColor`           | string         |          | text color                               |
| `textBackgroundColor` | string         |          | text background color                    |
| `backgroundColor`     | string         |          | the bar color                            |
| `hasTickMarks`        | boolean = true |          | show tick marks only apply to thick type |
| `tickColor`           | string         |          | tick color                               |
| `disabled`            | boolean        |          | disable the range input                  |
