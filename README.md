
# jquery-johnnys-path

 [![Patreon](https://img.shields.io/badge/Support%20me%20on-Patreon-%23e6461a.svg)][patreon] [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/jquery-johnnys-path.svg)](https://www.npmjs.com/package/jquery-johnnys-path) [![Downloads](https://img.shields.io/npm/dt/jquery-johnnys-path.svg)](https://www.npmjs.com/package/jquery-johnnys-path) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> A small jQuery plugin that animates an absolute positioned element according to a path you give.

## :cloud: Installation

```sh
$ npm i --save jquery-johnnys-path
```


## :clipboard: Example



```js
var options = {
    // Animation durations: 500 ms
    d: 500

    // Animation type
  , e: "linear"
};

$("...").johnnysPath(options, [
    { x: 100, y: 0   }
  , { x: 100, y: 100 }
  , { x: 000, y: 100 }
  , { x: 0,   y: 0   }
]);
```

## :memo: Documentation


### `johnnysPath(options, points, callback)`

A small jQuery plugin that animates an absolute positioned
element according to a path you give.

#### Params
- **Object** `options`: An object containing:
  - `d` (Number): The duration (default: 400 ms)
  - `e` (String): The animation type (default: "linear")
- **Array** `points`: An array of objects containing the `x` and `y` values.
- **Function** `callback`: The callback function.

#### Return
- **jQuery** The selected elements.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :moneybag: Donations

Another way to support the development of my open-source modules is
to [set up a recurring donation, via Patreon][patreon]. :rocket:

[PayPal donations][paypal-donations] are appreciated too! Each dollar helps.

Thanks! :heart:


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[patreon]: https://www.patreon.com/ionicabizau
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
