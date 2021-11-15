# hello-cli

## 1. Run like an app

- Add to package.json

```json
"main": "bin/index.js",
"bin": {
  "hello": "./bin/index.js"
},
```

- Run the app

```console
node .
```

- Install global and run

```console
npm install -g .

hello
```

- Uninstall

```console
npm uninstall -g hello-cli
```

- List all globally installed

```console
npm ls -g --depth=0
```
