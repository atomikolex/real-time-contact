# &lt;real-time-contact&gt;

> A simple contact form built with [Polymer](https://www.polymer-project.org/) and [Firebase](https://www.firebase.com/)..

## Why?

We needed a form to wire up to our [slackbot](https://github.com/StickmanVentures/inquiry-bot).

## Demo

[Check it live!](https://stickmanventures.github.io/real-time-contact)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install StickmanVentures/real-time-contact --save
```

Or [download as ZIP](https://github.com/stickmanventures/real-time-contact/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/stickmanventures/real-time-contact.html">
    ```

3. Start using it!

    ```html
    <real-time-contact firebase="https://YOUR_ENDPOINT.firebaseio.com/requests"></real-time-contact>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`firebase`    | *string*    | ``           | Firebase instance endpoint.

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

3. Start development server and open `http://localhost:8080/components/real-time-contact/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/stickmanventures/real-time-contact/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
