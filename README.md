# env-checker

Utility script to find environment variables in a config file and check that they're defined in a `.env.example`.

## Usage

Clone the repo and run `npm link` in the directory.

Run `check-config` in the project directory you want to check.

## Options

* `--config` - the name of the config file - default `./config.js`
* `--env` - the name of the env file in which the variables should be defined - default `./.env.example`
