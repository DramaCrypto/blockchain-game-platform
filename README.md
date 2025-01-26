
## Description
dApp which allows purchasing of games and then claiming the copy of ownership on any other game store/platform by presenting an NFT which confirms that a user has already bought it at another game store or gaming platform.

### Advantages for gamers
- Play the games using crypto
- Game information will be stored in blockchain ledger

### Advantages for game stores



## Architecture

The UI and API parts should be replicated for each game store separately, while the smart contract should be shared across them.



## How game stores can manage the shared NFT smart contract?



## How to run project
_Frontend_

```
cd frontend
npm install
npm start
```

http://localhost:3000/

_Backend_

`cd backend`

create a secret.json file with your eth private key with the following content

```
{
  "privateKey": "<INSERT-PRIVATE-KEY>"
}
```

```
npm install
npm start
```