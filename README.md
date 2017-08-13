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
