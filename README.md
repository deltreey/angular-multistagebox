angular-multistagebox
=====

angular-multistagebox is like a checkbox but with more than two states.

It's a simple angularjs directive that uses font-awesome icons and ng-click to create a 3-state box.

Because it's such a small amount of code, it should be able to read and understand so you can even tweak it for your needs.  In fact, I encourage it!

Available on Bower
-----

'bower install angular-multistagebox'

How To
-----
Simply include the multistagebox module

```javascript
var app = angular.module('app', [ 'multistagebox' ]);
```

Then use the multi-stage-box node in your html

```html
<multi-stage-box status="status"></multi-stage-box>
```

That fancy status attribute is where you can plug in your angular scope variable to set and retrieve the state of the box.

That's it!