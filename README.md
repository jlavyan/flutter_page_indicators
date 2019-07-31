


# flutter_page_indicator ![](https://img.shields.io/pub/v/flutter_page_indicator.svg)

Page indicator for flutter, with multiple build-in layouts.

> NOTE:this project is a fork of [flutter_page_indicator](https://github.com/best-flutter/flutter_page_indicator),
because the author doesn't maintain any more.

## Show cases

![showcases](https://github.com/jzoom/images/raw/master/page_indicator.gif)


### Installation

Add 

```bash

flutter_page_indicators:

```
to your pubspec.yaml ,and run 

```bash
flutter packages get 
```
in your project's root directory.


### Basic Usage

```
new PageIndicator(
  layout: PageIndicatorLayout.SLIDE,
  size: 20.0,
  controller: YOUR_PAGE_CONTROLLER,
  space: 5.0,
  count: 4,
)

```

### All build-in layouts


| Layout  | Showcase   | Support version   | 
| :------------ |:---------------:|:---------------:|
| PageIndicatorLayout.NONE | ![](https://raw.githubusercontent.com/jzoom/images/master/indicator1.gif)  | From 0.0.1 |
| PageIndicatorLayout.SLIDE | ![](https://raw.githubusercontent.com/jzoom/images/master/indicator2.gif)  | From 0.0.1 |
| PageIndicatorLayout.WARM | ![](https://raw.githubusercontent.com/jzoom/images/master/warm.gif)  | From 0.0.1 |
| PageIndicatorLayout.COLOR | ![](https://raw.githubusercontent.com/jzoom/images/master/indicator4.gif)  | From 0.0.1 |
| PageIndicatorLayout.SCALE | ![](https://raw.githubusercontent.com/jzoom/images/master/indicator5.gif)  | From 0.0.1 |
| PageIndicatorLayout.DROP | ![](https://raw.githubusercontent.com/jzoom/images/master/indicator7.gif)  | From 0.0.1 |
