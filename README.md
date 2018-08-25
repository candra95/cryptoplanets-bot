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
$ git clone https://github.com/meetdani/cryptoplanets-bot.git
$ cd cryptoplanets-bot
```
### Config

Download Packet Capture From Playstore
if you are using Nox or other Emulator Use Fiddler and setup the proxy

Open your BCH Diamonds APP.

Close all ads and Press Play On Packet Capture APP:
```sh
$ node app
```

Click Claim:
```sh
$ gulp watch
```

Copy the Urls and Cookie Headers and paste to $config variable:
```sh
$ karma test
```

### Explain

$config variable on the script.

| Variable | Description |
| ------ | ------ |
| urls | Url From Packet Capture or Fiddler |
| sessid | PHPSESSID cookie header from Packet Capture or Fiddler |
| worker | Numbers of Worker/claim, be careful |

### How To Run

```sh
$ php cryptoplanets-bch.php
```
### Issues 
> Please report this problem through the issue page [Create New Issue] (https://github.com/meetdani/cryptoplanets-bot/issues)
