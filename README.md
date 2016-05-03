# Angular QQ Emoji

## Installation

Use bower：

```shell
bower install angular-qqEmoji
```
Or use nodejs:

```
npm install angular-qqEmoji
```


## Usage

Demo:

```html
<html>
    <head>
        <meta charset="utf-8">
        <link rel="stylesheet" href="emoji.min.css">
        <script src="angular.min.js"></script>
        <script src="qqface.js"></script>
    </head>
    <body ng-app="app" ng-controller="AppCtrl">
        <ul>
            <li ng-repeat="item in items" ng-bind-html-unsafe="item | qqface"></li>
        </ul>
    </body>
</html>
```
