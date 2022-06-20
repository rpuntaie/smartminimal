# Initialize
``` sh
npm install

# in separate terminal
ganache-cli
```

# Develop

``` sh
cd smartcontract

truffle compile
truffle migrate

# change contract address in ui/index.html

truffle test
#truffle console
#truffle develop

chromium file://$PWD/../ui/index.html
```

# Deploy

This needs fee. 
Fill in the mnemonic `...` in truffle-config.js, representing the private key of your account.


``` sh
# change the pass phrase in smartcontract/truffle-config.js

truffle migrate --network smartzeniq
```

# Use

One needs Metamask. Set it to the right network.
Change to `window.ethereum` in `ui/index.html`.

