# rc-switch

---

Switch ui component for react.

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![npm download][download-image]][download-url]
[![bundle size][bundlephobia-image]][bundlephobia-url]

[npm-image]: http://img.shields.io/npm/v/rc-switch.svg?style=flat-square
[npm-url]: http://npmjs.org/package/rc-switch
[travis-image]: https://img.shields.io/travis/react-component/switch/master?style=flat-square
[travis-url]: https://travis-ci.org/react-component/switch
[circleci-image]: https://img.shields.io/circleci/react-component/switch/master?style=flat-square
[circleci-url]: https://circleci.com/gh/react-component/switch
[coveralls-image]: https://img.shields.io/coveralls/react-component/switch.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/react-component/switch?branch=master
[david-url]: https://david-dm.org/react-component/switch
[david-image]: https://david-dm.org/react-component/switch/status.svg?style=flat-square
[david-dev-url]: https://david-dm.org/react-component/switch?type=dev
[david-dev-image]: https://david-dm.org/react-component/switch/dev-status.svg?style=flat-square
[download-image]: https://img.shields.io/npm/dm/rc-switch.svg?style=flat-square
[download-url]: https://npmjs.org/package/rc-switch
[bundlephobia-url]: https://bundlephobia.com/result?p=rc-switch
[bundlephobia-image]: https://badgen.net/bundlephobia/minzip/rc-switch

## Install

[![rc-switch](https://nodei.co/npm/rc-switch.png)](https://npmjs.org/package/rc-switch)

## Usage

```js
import Switch from 'rc-switch';

export default () => <Switch />;
```

## Compatibility

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/electron/electron_48x48.png" alt="Electron" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Electron |
| --- | --- | --- | --- | --- |
| IE11, Edge | last 2 versions | last 2 versions | last 2 versions | last 2 versions |

## API

| Property       | Type                     | Default   | Description                                              |
| -------------- | ------------------------ | --------- | -------------------------------------------------------- |
| prefixCls      | String                   | rc-switch |                                                          |
| className      | String                   | ''        | additional class name of root node                       |
| checked        | boolean                  | false     | whether switch is checked                                |
| defaultChecked | boolean                  | false     | whether switch is checked on init                        |
| onChange       | Function(checked, event) |           | called when switch is checked or unchecked               |
| tabIndex       | number                   |           | tab-index of switch node                                 |
| onClick        | Function(checked, event) |           | called when switch is clicked                            |
| autoFocus      | boolean                  |           | get focus when mounts                                    |
| disabled       | boolean                  | false     | whether switch is disabled                               |
| loadingIcon    | React.ReactNode          |           | specific the extra node. generally used in loading icon. |

## Development

```
npm install
npm start
```

Online demo: http://react-component.github.io/switch/examples/

## License

rc-switch is released under the MIT license.
