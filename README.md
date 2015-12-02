# jquery-johnnys-path [![Support this project][donate-now]][paypal-donations]

A small jQuery plugin that animates an absolute positioned element according to a path you give.

## Installation

```sh
$ npm i --save jquery-johnnys-path
```

## Example

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

## Documentation

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

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md