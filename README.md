## bower-commons-cloud

This repository contains the Bower release of [ngCommonsCloud](https://github.com/CommonsCloud/ngCommonsCloud).

### Installing CommonsCloud

Below is a sample set of commands:

```bash
cd yourProjectDir
bower install angular-commons-cloud --save
```

### Usage

CommonsCloud depends on Angular's ngRoute and ngResource libraries. Both scripts must be included after Angular and before CommonsCloud.

```html
<script src="bower_components/angular/angular.js"></script>
<script src="bower_components/angular-resource/angular-resource.js"></script>
<script src="bower_components/angular-route/angular-route.js"></script>
<script src="bower_components/angular-commons-cloud/angular-commons-cloud.js"></script>
```

Make sure to include the commons module in your app's dependencies.

```javascript
angular.module('YourApp', ['commons']);
```
