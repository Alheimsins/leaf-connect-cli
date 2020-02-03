# leaf-connect-cli

## Requirements

Install [node.js](https://nodejs.org/en/)

# Installation

### Globally

```bash
npm i -g leaf-connect-cli
# Then use the "leaf-connect-cli" to run it
leaf-connect-cli
```

### Without installation - [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b)

```bash
npx leaf-connect-cli
```

# Usage

## Commands

| Command             | Description               |
| ------------------- | ------------------------- |
| status              | Retrive status            |
| cachedStatus        | Retrieve cached status    |
| climateControlStatus| Retrive climate control status |
| climateControlTurnOn| Turn on climate control   |
| climateControlTurnOff| Turn off climate control |
| chargingStart       | Start charging            |
| history             | Get history               |


## Options

| Option              | Description               |
| ------------------- | ------------------------- |
| -v, --verbose       | Verbose logging           |
| -h, --help          | Display help              |
| -u, --username      | Your username             |
| -p, --password      | Your password             |
| -r, --regionCode    | [Required] see "region codes" |             |
| -l, --locale        | Locale to use. Default: en-US |

## Example

```
leaf-connect-cli status -u username -p password -r NE
```

# Region codes

| Region | Code |
|--------|------|
| Europe | NE   |
| Canada | NCI  |
| USA    | NNA  |
| Australia | NMA |
| Japan | NML |

### Example script

See [my bash](https://gist.github.com/maccyber/d3d69337e3d074d5be710ef14240d657) to use with i3/i3bar/i3cat

# Acknowledgements

This library was inspired by [Jason Horne's](https://github.com/jdhorne) [`pywings2`](https://github.com/jdhorne/pycarwings2) Carwings library for Python.

# License

[MIT](LICENSE)

# About

Created with ❤  for [Alheimsins](https://alheimsins.net)

<img src="https://image.ibb.co/dPH08G/logo_black.png" height="150px" width="150px" />
