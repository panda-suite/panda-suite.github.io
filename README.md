# Panda Suite
For developers building on top of Bitcoin Cash, Pandacash speeds up a development workflow and enables to work locally. It does it by providing a set of tools that can used to start one-click test blockchain, run tests, execute commands, and inspect transactions while controlling how the chain operates.

Join us on Telegram: [https://t.me/panda_suite](https://t.me/panda_suite).

## Intro
Panda Suite has been started during the BCH DEVCON in Amsterdam 18'. It started because there was a lack of development tools for BCH and no standardized development environment. The Panda Suite is inspired by the Truffle Suite for the Ethereum network.

## Value proposition
1. Better tooling will attract more application developers 
2. Spend more time building user applications instead of dev-ops 
3. Make application testing more consistent and applications more secure 

## Features
• Fast: Instant blockchain start (no need to sync up 150GB)  
• Responsive: No mining needed (new blocks are created with new transactions)  
• Timesaving: Multiple addresses pre-filled with spendable coins  
• Clean start: Throw away and restart blockchain  
• For web developers: Completly written in Javascript with the most modern standards  
• Needed: BCH apps need to be developed and tested locally  
• Open: Fully open-sourced with MIT licence and documented  

## Panda power: Usability
PandaCash is easily installed as a CLI and can immediately be used with BCH applications
```javascript
npm install -g pandacash-cli
```

PandaCash can also be imported as an npm package:
```javascript
npm install --save pandacash-core
```

## Components
**Panda Suite = CLI + Core + bchJS + Explorer + Web Sandbox**

### [pandacash-cli](https://www.npmjs.com/package/pandacash-cli)
Fast Bitcoin Cash RPC client for testing and development (inspired by ganache-cli)

Github: [github.com/panda-suite/pandacash-cli](https://github.com/panda-suite/pandacash-cli)

### [pandacash-core](https://www.npmjs.com/package/pandacash-core)
is core code for pandacash. Can be imported as node module in other applications. (inspired by ganache-core)

Github: [github.com/panda-suite/pandacash-cli](https://github.com/panda-suite/pandacash-core)

### [bchjs](https://www.npmjs.com/package/bchjs)
is a lightweight wrapper around a Bitcoin Cash Node RPC. This allows you to easily create tooling around any Bitcoin Cash Node functionality. (inspired by web3)

Github: [github.com/panda-suite/pandacash-cli](https://github.com/panda-suite/bchjs)

### Pandacash Explorer (in development)
It complements the pandacash-cli with a graphical interface. It is desktop application. Pandacash Explorer will available for Windows, Mac, and Linux.

### Pandacash Sandbox (in development)
Pandacash Sandbox is a browser-based development tool for BCH applications. Sanbox provides a JavaScript implementation of the BCH blockchain which can be used for simple testing.

## Under the hood
Pandacash is powered by the bcash implementation of Bitcoin Cash.

<img src="https://raw.githubusercontent.com/panda-suite/panda-suite.github.io/master/bcoin-logo-gradient-text.png" alt="bcash / bcoin blockchain" width="200"/>

# Licence
Copyright 2018 Panda Suite

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
