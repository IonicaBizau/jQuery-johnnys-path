jQuery-johnnys-path
==================

A small jQuery plugin that animates an absolute positioned element according to a path you give.

## How to use?

Include **jQuery** and **jQuery-johnnys-path** scripts in your page:

```html
<script src="path/to/jQuery.js"></script>
<script src="path/to/jQuery-johnnys-path.js"></script>
```

Then you will be able to do this:

```js
var options = {};
$("...").johnnysPath(options, [
  { x: 100, y: 0   },
  { x: 100, y: 100 },
  { x: 000, y: 100 },
  { x: 0,   y: 0   }
]);
```

## Options

<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Description</th>
            <th>Default value</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code>d</code></td>
            <td><code>d</code> represents duration. It can be passed when calling <code>johnnysPath({d: 500}, ...)</code> function or in a point object: <code>{x: 100, y: 200, d: 500}</code></td>
            <td><code>400</code></td>
        </tr>
        <tr>
            <td><code>e</code></td>
            <td><code>e</code> represents easing. Like duration it can be passed in the function options or in a point object.</td>
            <td><code>"linear"</code></td>
        </tr>
    </tbody>
</table>

## Bugs & Features
Did you find a bug? Or do you want a feature? Please report any bugs and features here: [here](https://github.com/IonicaBizau/jQuery-johnnys-path/issues).

## Contributing
Do you want to contribute to this project? Great! Follow the following steps:

 1. Search [in the repo issues](https://github.com/IonicaBizau/jQuery-johnnys-path/issues) an issue you want to fix.
 1. If you want to add a new feature that is not added as issue, add it first in the issue list.
 1. Fork the project to your profile.
 1. Fix the issue you want to fix.
 1. Make a pull request.

I will try to merge the pull requests as fast I can.


## License
See [LICENSE](https://github.com/IonicaBizau/jQuery-jonnys-path/blob/master/LICENSE) file.
