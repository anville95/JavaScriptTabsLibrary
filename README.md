# JS Tabs Library

A JavaScript library offering a simple yet powerful API for creating and managing responsive tab interfaces.

## Tab Types Supported

1. **swipableTabs** – Change tabs by swiping or using tab buttons.
2. **swipableTabsWithoutTabButtons** – Swipe only; no tab buttons.
3. **nonSwipableTabs** – Navigate via tab buttons only; no swipe support.

## Features

- Tabs are fully **responsive**, automatically resizing to fit the container.
- Style customization supported via CSS strings.
- **Debugging dialogs** can be enabled/disabled:
  - `enableDebuggingDialogs()`
  - `disableDebuggingDialogs()`
- **Helper methods**:
  - `showFunctionsList()`
  - `showDocumentation()`

## Tech Stack

- Vanilla JavaScript
- HTML5/CSS3

## Challenges

Responsiveness logic, especially recalculating dimensions on browser resize, was a significant hurdle that was successfully overcome.
