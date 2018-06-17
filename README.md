
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)
<img src="https://travis-ci.com/senorprogrammer/wtf.svg?branch=master" />

<p align="center">
  <img src="./docs/img/wtf.jpg?raw=true" title="WTF" width="852" height="240" />
</p>

A personal terminal-based dashboard utility, designed for
displaying infrequently-needed, but very important, daily data.

<p align="center">
<img src="./docs/img/screenshot.jpg" title="screenshot" width="720" height="420" />
</p>

## Quick Start

### Installation from Source

**Note:** WTF is _only_ compatible with Go versions **1.9.2** or later. It currently _does not_ compile with `gccgo`.

```bash
go get -u github.com/senorprogrammer/wtf
cd $GOPATH/src/github.com/senorprogrammer/wtf
make install
make run
```

Or [download the latest binary](https://github.com/senorprogrammer/wtf/releases).

## Support

Chat on Gitter
[![Join the chat at https://gitter.im/wtfutil/Lobby](https://badges.gitter.im/wtfutil/Lobby.svg)](https://gitter.im/wtfutil/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Documentation

See [https://wtfutil.com](https://wtfutil.com) for the definitive
documentation. Here's some short-cuts:

* [Installation](http://wtfutil.com/posts/installation/)
* [Configuration](http://wtfutil.com/posts/configuration/)
* [Module Documentation](http://wtfutil.com/posts/modules/)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests.

## Author

* Chris Cummer, [senorprogrammer](https://github.com/senorprogrammer)


## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/6413?v=4" width="64px;"/><br /><sub><b>Chris Cummer</b></sub>](https://twitter.com/senorprogrammer)<br />[💻](https://github.com/senorprogrammer/wtf/commits?author=senorprogrammer "Code") | [<img src="https://avatars1.githubusercontent.com/u/34973359?v=4" width="64px;"/><br /><sub><b>Hossein Mehrabi</b></sub>](https://github.com/jeangovil)<br />[💻](https://github.com/senorprogrammer/wtf/commits?author=jeangovil "Code") | [<img src="https://avatars0.githubusercontent.com/u/11779018?v=4" width="64px;"/><br /><sub><b>FengYa</b></sub>](https://github.com/Fengyalv)<br />[💻](https://github.com/senorprogrammer/wtf/commits?author=Fengyalv "Code") |
| :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

## License

See [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

The inspiration for `WTF` came from Monica Dinculescu's
[tiny-care-terminal](https://github.com/notwaldorf/tiny-care-terminal).

Many thanks to <a href="https://lendesk.com">Lendesk</a> for supporting this project by
providing time to develop it.

The following open-source libraries were used in the creation of `WTF`.
Many thanks to all these developers.

* [calendar](https://google.golang.org/api/calendar/v3)
* [config](https://github.com/olebedev/config)
* [go-github](https://github.com/google/go-github)
* [goreleaser](https://github.com/goreleaser/goreleaser)
* [newrelic](https://github.com/yfronto/newrelic)
* [openweathermap](https://github.com/briandowns/openweathermap)
* [tcell](https://github.com/gdamore/tcell)
* [tview](https://github.com/rivo/tview)

<p align="center">
<img src="./docs/img/dude_wtf.png?raw=true" title="Dude WTF" width="251" height="201" />
</p>
