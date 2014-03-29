# &lt;bing-maps&gt;

Web Component wrapper for Bing Maps using Polymer.

> Maintained by [Breno Polanski](https://github.com/brenopolanski).

## Demo

> [Check it live](https://github.com/msp-brasil/bing-maps-element).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/bing-maps.html">
    ```

3. Start using it!

    ```html
    <bing-maps></bing-maps>
    ```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute     | Options                   | Default                         | Description
---           | ---                       | ---                             | ---
`credentials` | *string*                  | `Your Bing Maps Key`            | Lorem ipsum
`latitude`    | *int*                     | `45.5`                          | Lorem ipsum
`longitude`   | *int*                     | `-122.5`                        | Lorem ipsum
`type`        | *object*                  | `Microsoft.Maps.MapTypeId.road` | Lorem ipsum
`zoom`        | *int*                     | `7`                             | Lorem ipsum

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

For detailed changelog, check [Releases](https://github.com/msp-brasil/bing-maps-element/releases).

## License

[MIT License](http://brenopolanski.mit-license.org/) © Breno Polanski