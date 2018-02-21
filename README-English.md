### Single Page Application - Bitcoin blockchain explorer

Your task is to create web application for monitoring the status of the Bitcoin blockchain network.

Bitcoin blockchain is a chain of blocks.
Each block has a link to the previous block in the chain.
Unique block identifier is called `height`.
A new block is generated approximately every 10 minutes.
The block stores information about a certain number of transactions.
Transaction is the transfer of funds from the one wallet to another.
The unique identifier for the transaction is its `hash`.

#### Functionality to be implemented:
1. Home page (list of the last 10 blocks,
list of the last 10 transaction,
chart with Bitcoin price for the last month,
form to search block by `height` and transaction by `hash`);
2. The page with a list of blocks and pagination;
3. A page with detailed information about a block and its transaction (with pagination);
4. A page with detailed information about a transaction.

#### Technical requirements:
* JavaScript with ES5+ or TypeScript;
* Build tools (webpack/grunt/gulp);
* Responsive layout (usage of Bootstrap is a plus);
* Redux or RxJS;
* Immutable data structures (Immutable.js, Seamless-immutable, etc.);
* All information about Bitcoin blockchain is accessible through
[blockchain.info](https://blockchain.info/api/blockchain_api) public API.

#### Expected result:
* Source code on GitHub or Bitbucket.

#### Examples:
[Home page #1](https://blockchain.info/ru/home)  
[Home page #2](https://blockexplorer.com/)  
[List of blocks](https://blockchain.info/en/blocks)  
[Block page](https://blockchain.info/ru/block/0000000000000000002e1baaee54d9e6fa34c6dbd4115b0f0df9dd88598c91e0)  
[Transaction page](https://blockchain.info/ru/tx/3ab30534c82e4a0ad071767610315cde64fb6923775ab5a96f0cb9a56368ca5e)

#### Public APIs:
[Blockchain HTTP API](https://blockchain.info/api/blockchain_api)  
[Blockchain WebSocket API](https://blockchain.info/api/api_websocket)  
[Bitcoin Rates API](https://blockchain.info/api/exchange_rates_api)
