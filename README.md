## Summary

- Connected to Ganache local port using Web3

- Used python to access ETH and BTC accounts in Web3 from Nmemonic/Secret seed phrase 

- Used python to access accounts in Web3 from Private keys

- Using load_env Load and set environment variables from .env 

- Understanding of BIP32, BIP39, and BIP44

- Worked with [`bit`](https://ofek.github.io/bit/) Python Bitcoin library to send crypto and view balances

- Worked with [`web3.py`](https://github.com/ethereum/web3.py) Python Ethereum library to estimate gas, create Raw transaction, sign the transaction and send transaction
- View the results on Ganache for Web3
- Worked with Faucets to get test BTC



### Ganache connections

Screenshot of Ganache Accounts before doing any transactions.

We will be using Account 1 and Account 2 for transaction.

![image-20210902232118745](Images/image-20210902232118745.png)





### Python Jupyter code

[Jupyter Notebook Wallet.ipynb](https://github.com/rchak007/PythonWeb3BitTransactions/blob/main/wallet.ipynb)



### Web3 transaction

![image-20211113105416827](Images/Web3Tx1.png)





### Viewing transactions on Ganache



![Ganache_transaction](Images/Ganache_transaction.png)



![image-20210903000219780](Images/GanacheResults.png)











### Mnemonic Code Converter

Generating Bitcoin Test accounts from Mnemonic

![image-20211106201007525](Images/MnemonicCodecnovertorBTCTestnet01.png)

Derivation Path for BTC testnet



![image-20211106201209899](Images/derivPathBTCTestnet.png)





### Deriving Address 

![image-20211106201330353](Images/BtctestnetAddrFrmDerivation.png)



### Python Bit transactions



Below we use the 2 addresses we derived and use it for transfer using Bit

We use wif_to_key to get the BTC address from private key

![image-20211113103357411](Images/tmpBit02.png)









### Faucets

Bitcoin Testnet faucets to request tokens:

* https://bitcoinfaucet.uo1.net/

* https://kuttler.eu/en/bitcoin/btc/faucet/

* https://testnet-faucet.mempool.co/

* https://testnet.help/en/btcfaucet/testnet

