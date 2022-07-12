# prettier-config

Shared config for code formatting

## Usage

### With yarn

In package.json add the line:

```json
"prettier": "prettier-config",
```

and at your project repo root in shell

```bash
yarn add -D git+ssh://git@github.com/te-papa/prettier-config.git
```

### Alternatively

Add this to your package.json

```json
"prettier": "prettier-config",

"devDependencies": {
  "prettier-config": "git+ssh://git@github.com/te-papa/prettier-config.git"

}
```

## Editor Config

This is sourced from <https://github.com/te-papa/init-config>

Add this to your package.json

```json
"scripts": {
    "editorconfig": "cp node_modules/prettier-config/.editorconfig ."
},
```

Then run:

```bash
yarn editorconfig
```

before commencing development
