# &lt;bing-maps&gt;

Web Component wrapper for Bing Maps using Polymer.

> Maintained by [Breno Polanski](https://github.com/brenopolanski).

## Demo

![bing-maps](https://raw.githubusercontent.com/msp-brasil/bing-maps-element/gh-pages/bing-maps.png)

[Check it live](http://msp-brasil.github.io/bing-maps-element).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install bing-maps-element --save
```

Or [download as ZIP](https://github.com/msp-brazil/bing-maps-element/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/bing-maps-element/src/bing-maps.html">
    ```

3. Start using it!

    ```html
    <bing-maps></bing-maps>
    ```

## Options

Attribute     | Options                   | Default                         | Description
---           | ---                       | ---                             | ---
`credentials` | *string*                  | `Your Bing Maps Key`            | Your Bing Maps Key
`latitude`    | *int*                     | `45.5`                          | The latitude coordinate
`longitude`   | *int*                     | `-122.5`                        | The longitude coordinate
`type`        | *object*                  | `Microsoft.Maps.MapTypeId.road` | The map type to construct
`zoom`        | *int*                     | `7`                             | The zoom level of the map

> See [Bing Maps documentation](http://msdn.microsoft.com/en-us/library/gg427610.aspx).

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

3. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```
    
4. To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

5. To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Browser Support

![IE](https://raw.github.com/alrra/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :)

## History

For detailed changelog, check [Releases](https://github.com/msp-brazil/bing-maps-element/releases).

## License

[MIT License](http://brenopolanski.mit-license.org/) © Breno Polanski
