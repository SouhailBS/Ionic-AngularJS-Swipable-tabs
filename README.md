# Ionic-AngularJS-Swipable-tabs


A free, easy installation Ionic/AngularJS directive to support swipable tabs.


## Screenshot

![alt text](https://github.com/SouhailBS/Ionic-AngularJS-Swipable-tabs/blob/master/screenshot.gif)

## Features

- **Smooth Swipe**
-  **Animated navigation**
- **Fully Open Sourced**

## Installation

```bash
bower install ionic-angularjs-swipable-tabs --save
```
Add a `<script>` to your `index.html`:

    <script src="lib/ionic-angularjs-swipable-tabs/tabs-swipable.min.js"></script>
Add a `<link>` to your `index.html`:

    <link href="lib/ionic-angularjs-swipable-tabs/tabs-swipable.min.css" type="text/css" rel="stylesheet"/>

Add a `tabs-swipable`  directive to your tabs:

    <ion-tabs class="tabs-icon-top tabs-color-active-positive" tabs-swipable>
      ...
    </ion-tabs>
    
## Swipe Options
- **Swipe loop**
Add a `tabs-swipable-loop`  attribute to your tabs with "true" or "false" as value (dafault is false):

    <ion-tabs class="tabs-icon-top tabs-color-active-positive" tabs-swipable-loop="true|false">
      ...
    </ion-tabs>
    
## Limitation
- Next tab preview is shown only if the next view was cached.
-  No animation when moving between tabs by clicking on the tab button.

## License

[MIT](https://github.com/SouhailBS/Ionic-AngularJS-Swipable-tabs/blob/master/LICENSE)
