# &lt;github-ribbon&gt;

Web Component Displays a Github ribbon [Github Ribbon] using Polymer.

## Demo
> [Check it live](http://ignaciorivas.me/github-ribbon/).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install github-ribbon --save
```

Or [download as ZIP](https://github.com/sabarasaba/github-ribbon/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="bower_components/github-ribbon/src/github-ribbon.html">
  ```

3. Start using it!

  ```html
<github-ribbon user="sabarasaba" repo="tookie" color="orange" position="right"></github-ribbon>
  ```

## Options

Attribute  | Options         | Default                    | Description
---        | ---             | ---                        | ---
`user`     | *username*      | `sabarasaba`               | The username of the repo
`repo`     | *repository*    | `github-ribbon`            | The name of the repo
`color`    | `red`, `green`, `black`, `orange`, `gray`, `black` | `red`                  | The background color of the ribbon
`position` | `right`, `left` | `right`                    | The position of the ribbon

## Browser Support

![IE](https://raw.github.com/paulirish/browser-logos/master/internet-explorer/internet-explorer_48x48.png) | ![Chrome](https://raw.github.com/paulirish/browser-logos/master/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/paulirish/browser-logos/master/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/paulirish/browser-logos/master/opera/opera_48x48.png) | ![Safari](https://raw.github.com/paulirish/browser-logos/master/safari/safari_48x48.png)
--- | --- | --- | --- | --- |
IE 10+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/sabarasaba/github-ribbon/releases) list.

## License

[MIT License](http://mvaldetaro.mit-license.org/) © Ignacio Rivas
