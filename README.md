# Crypto Quest Candy Machine UI

## Clone the project:

```shell
git clone https://github.com/anth226/cryptoquest-candy-machine-ui.git
```

## Install dependencies:

```shell
cd cryptoquest-candy-machine-ui
npm install
```

## Update .env:

- After successfull upload of candy machine new hidden folder '.cache' will be created inside metaplex folder (js/packages/cli/src/.cache)
- Inside file 'devnet-example.json' will be candy machine id as "program.candyMachine"
- Update .env file, set REACT_APP_CANDY_MACHINE_ID for recieved "program.candyMachine" id

## Run locally:

```shell
npm start
```
