
## bootstrap-bower-carousel

This is the bower repository for the carousel component of of the [angular-ui/bootstrap project](https://github.com/angular-ui/bootstrap) project.

### Usage

Include the js file into your HTML with a `<script>` tag or your preferred tool.

Use `ui-carousel-tpls.js` to use the default html templates (recommended). Alternatively, Use `ui-carousel.js` if you wish to create your own html templates.

Then, be sure to include the module as a dependency for your app:
```js
angular.module('myApp', ['ui.bootstrap.carousel']
```



And if you are using `ui-carousel-tpls.js`, be sure to additionally include the bundled html templates as dependencies:
```js
angular.module('myApp', [
  'ui.bootstrap.carousel',
  'template/carousel/carousel.html',
  'template/carousel/slide.html'
])
```

