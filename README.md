## Installation
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/zer-far/swervebin)

1. Install Git and node.js: `sudo apt-get install git nodejs`
2. Clone this repository: `git clone https://github.com/zer-far/swervebin.git swervebin`
3. Open `config.json` and change the settings (if you want to)
4. Install dependencies: `npm install`
5. Start the application: `npm start`

## Update
1. Pull changes from this repository: `git pull`
2. Install new dependencies: `npm install`

## Settings
| Key                    | Description                                     | Default value |
| ---------------------- | ----------------------------------------------- | ------------- |
| `host`                 | The host the server runs on                     | `0.0.0.0`     |
| `port`                 | The port the server runs on                     | `8080`        |
| `dataPath`             | The directory where all pastes are stored       | `./data`      |
| `keyLength`            | The length of the pastes' key                   | `10`          |
| `maxLength`            | Maximum chars in a paste                        | `500000`      |
| `createKey`            | Needs to be in front of paste to allow creation | ` `           |
| `documents`            | Static documents to serve                       | See below     |

### Default Config
```json
{
	"host": "0.0.0.0",
	"port": 8080,
	"dataPath": "./data",
	"keyLength": 10,
	"maxLength": 500000,
	"createKey": "",
	"documents": {
		"about": "./README.md",
		"javaTest": "./documents/test.java"
	}
}
```
