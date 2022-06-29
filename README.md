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
