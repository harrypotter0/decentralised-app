## Hello World Dapp

This updates his tutorial with new web3 1.X bindings, and packages the tutorial for easy installation.

## Dependencies

* ethereumjs-testrpc 
* web3
* solc

### Installation and Usage

Clone repository and run
```
npm install
```
Then launch the testpc server with
```
npm run ganache
```
and from a separate shell
```
npm run http_server
```

Then point your browser to `http://localhost:8000` for the web version of the voting app.

The `server.js` file includes the VotingContract setup and deployment. For comparision you should be able to follow the original tutorial to get an idea of what was changed from the pre 1.0 `web3` to the 1.0 `web3` bindings.
