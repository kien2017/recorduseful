# recorduseful

Knex.js is a "batteries included" SQL query builder for Postgres, MSSQL, MySQL, MariaDB, SQLite3, and Oracle designed to be flexible,

Getting Test-Driven Development (TDD) Right

https://blog.risingstack.com/getting-node-js-testing-and-tdd-right-node-js-at-scale/

A Beginner’s Guide to npm — the Node Package Manager

https://www.sitepoint.com/beginners-guide-node-package-manager/

https://github.com/bitcoinjs/bip39

https://bitcore.io/api/lib/transaction

https://github.com/bitcoinjs/bitcoinjs-lib


C:\Users\  \AppData\Roaming\Bitcoin add bitcoin.conf  server=1

C:\Program Files\Bitcoin\daemon add to enviroment path

run ./bitcoind -testnet


var cmd=require('node-cmd');

var hexdata = ""
   cmd.get(
        "bitcoin-cli -testnet decoderawtransaction "+hexdata,
        function(err, data, stderr){
            console.log('the current working dir is : ',data)
        }
    );


82 Error: The amount of data is too big to be stored in a QR Code


dumpprivkey "mtyHrM2HrgdmqzvHd6FCWKRXEp74epGY65"

cSwJfUZqxx5zSNCW7wXbLbZqd51mA2PjFHrUaP6Y9SXvJD5qhsei




82 6ed369581647e200c909e6686a4a0d3a35d394cdb5a516577e03d15a765333fb 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr 7465f04be56925cdf0665cc5878d6b3123c5b21464977cb8bde56a350dbe58a9 1 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr ee6ebd410708f40b662f6ad51eceb1697972d0571a6a33468c0fa95fbf49c996 1 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr 90fce21979a144be0334a8280ad69724b6f92e26fb598c1778cf0ff57fde99d0 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr eca89c56f9b3ccc4d3394c0ce3c6c870f7849e506daa5fa71d1977f27b8d91f4 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr f9e174978b8a2ae27fac4c7459338318477d6003922b2a5a4802139b65e5cee5 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr 00ef67bdb6d1bfe5dc3eff72d8e592b134aa756973ece9ed1629798bfec17140 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr 59e381b1bf9fc43f3aa170b51fde42806cb003d55f16f049cec580ae210318bc 0 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr mwCwTceJvYV27KXBc3NJZys6CjsgsoeHmf 6.758 mnjxWZWLQSFw4dor1GERYpHc4sy5nu4yKr 0.04942322

wuwang duan   Error: The amount of data is too big to be stored in a QR Code

72 mei you wen ti ke yi yong


var utxo = new UnspentOutput({
  "txid" : "a0a08e397203df68392ee95b3f08b0b3b3e2401410a38d46ae0874f74846f2e9",
  "vout" : 0,
  "address" : "mgJT8iegL4f9NCgQFeFyfvnSw1Yj4M5Woi",
  "scriptPubKey" : "76a914089acaba6af8b2b4fb4bed3b747ab1e4e60b496588ac",
  "amount" : 0.00070000
});
var utxo = new UnspentOutput({
  "txId" : "a0a08e397203df68392ee95b3f08b0b3b3e2401410a38d46ae0874f74846f2e9",
  "outputIndex" : 0,
  "address" : "mgJT8iegL4f9NCgQFeFyfvnSw1Yj4M5Woi",
  "script" : "76a914089acaba6af8b2b4fb4bed3b747ab1e4e60b496588ac",
  "satoshis" : 70000
});
