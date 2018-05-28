electron + express server + create-react-app in single repo

## Setup

Currently manaul dependency install is required, could use `lerna` instead to automate the setup process.

```sh
npm install -g express
npm install
cd server && npm install
cd web && npm install
```

## Start Electron window

```sh
npm run electron
```

## Start Server only

```sh
cd server && npm start
```

## Start frontend only

```sh
cd web && npm start
```
