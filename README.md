# validationIonic
Directive validation ionic

```js
var app = angular.module('app', ['ionic', 'validationIonic'])
```

```html
<form novalidate="novalidate" on-valid-submit="update()">
<label class="item item-input validated">
<input type="text" required="required" tabindex="1" ng-model="var" name="var">
<i class="icon ion-alert-circled error"></i>
</label>

<button class="button">
  EDIT
 </button>
</form>
```
