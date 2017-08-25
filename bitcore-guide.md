https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04
How To Install Node.js on Ubuntu 16.04 

    sudo apt-get update
    sudo apt-get install build-essential libssl-dev
    
curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh

bash install_nvm.sh

source ~/.profile

node -v

sudo apt-add-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install bitcoind

bitcore create mynode --testnet

cd mynode
vi bitcore-node.json

cd mynode
bitcored
