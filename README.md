Angular timeago directive
=========================

Edited based on this jQuery plugin [https://github.com/rmm5t/jquery-timeago](https://github.com/rmm5t/jquery-timeago) by @rmm5t.

Provided a directive `angularTimeago` from module `angularTimeago`.

# How to use

* Include `angular-timeago.js`
* Inject `angularTimeago` module in your app's main module, like `demoApp` in the example
* Use the markup on page `<div angular-timeago="2015-01-29T09:35:56Z"></div>`
* Date format is in ISO8601

It'll be translated into:

```html
<div angular-timeago="2015-01-29T09:35:56Z" class="ng-isolate-scope">
  <span class="ng-binding">about an hour ago</span>
</div>
```
