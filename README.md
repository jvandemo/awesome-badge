# Awesome badge web component

Displays awesome badge that links to Sindre Sorhus' [awesome list](https://github.com/sindresorhus/awesome).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install awesome-badge --save
```

Or [download as ZIP](https://github.com/jvandemo/awesome-badge/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/awesome-badge/awesome-badge.html">
    ```

3. Start using it!

    ```html
    <awesome-badge></awesome-badge>
    ```

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

v0.2.1

- Add `npm-debug.log` to `.gitignore`

v0.2.0

- Removed dependency on Polymer

v0.1.0

- Initial release

## License

[MIT License](http://opensource.org/licenses/MIT)
