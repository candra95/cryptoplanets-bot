# CryptoPlanet Bots

Free AutoClaim Diamonds on CryptoPlanets Faucets.

List of Bots :

  - BCH Diamonds
  - Crypto Diamonds
  - etc

## Contributors

Thanks goes to these wonderful people :

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars.githubusercontent.com/u/1500684?v=3" width="100px;"/><br /><sub><b>Eka Syahwan</b></sub>](https://github.com/radenvodka)<br /> sdata author (PHP cURL multi-threading)
<!-- ALL-CONTRIBUTORS-LIST:END -->

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```
### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```

### Explained

$config variable on the script.

| Variable | Description |
| ------ | ------ |
| urls | Url From Packet Capture or Fiddler |
| sessid | PHPSESSID cookie header from Packet Capture or Fiddler |
| worker | Numbers of Worker/claim, be careful |


