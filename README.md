# AiOverlay
Minimal Overlay / Backdrop React Component

![npm bundle size](https://img.shields.io/bundlephobia/min/@aiui/ai-overlay)
![npm bundle size](https://img.shields.io/bundlephobia/minzip/@aiui/ai-overlay)
![npm download](https://img.shields.io/npm/dm/@aiui/ai-overlay.svg)

## Install
    npm i @aiui/ai-overlay

## Import
    import AiOverlay from '@aiui/ai-overlay';


## Props
|   Name   |  Type  |   Default       | Description |
|----------|:-------|:----------------|:--------|
| opened   | bool   | false           | If true, the overlay is open |
| color    | string | #e0e0e0         | Overlay Color |
| onClose  | func   | ( ) => { }      | Callback fired when the component requests to be closed |