# Raise an error when there is a route with uppercased letters in router.js (no-capital-letters-in-routes)

When you accidentally uppercase any of your routes or create uppercased route using ember-cli the application will crash without any clear information what's wrong. This rule makes it more obvious, so you don't have to think about it any more.


## Rule Details

Examples of **incorrect** code for this rule:

```js

this.route('Home');
this.route('SignUp');

```

Examples of **correct** code for this rule:

```js

this.route('home');
this.route('sign-up');

```

### References

* [Ember Routing Guide](https://guides.emberjs.com/release/routing/)

### Related Rules

* [no-unnecessary-route-path-option](no-unnecessary-route-path-option.md)
* [route-path-style](route-path-style.md)
* [routes-segments-snake-case](routes-segments-snake-case.md)
