jQuery-johnnys-path
==================

A small jQuery plugin that animates an absolute positioned element according to a path you give.

## How to use?

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


## License
See [LICENSE](https://github.com/IonicaBizau/jQuery-jonnys-path/blob/master/LICENSE) file.
