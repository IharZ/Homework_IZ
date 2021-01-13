Background

New startup market race - initial requirement
Main focus of a newly founded company is to build a portfolio management system (PMS) that supports both, traditional assets (like gold, silver, stocks, etc) and currently very hot topic - crypto-assets!!! But, as there are so many coins out there, our task to understand how HD wallets work, and to build out a system that can create them. 

You're in a race to get to the market. There aren't as many tools available in Python for this sort of thing, yet. Thankfully, you've found a command line tool, hd-wallet-derive that supports not only BIP32, BIP39, and BIP44, but also supports non-standard derivation paths for the most popular wallets out there today! However, you need to integrate
the script into your backend with your dear old friend, Python. Once you've integrated this "universal" wallet, you can begin to manage billions of addresses across 300+ coins, giving you a serious edge against the competition. In this assignment, however, you will only need to get 2 coins working: Ethereum and Bitcoin Testnet. Ethereum keys are the same format on any network, so the Ethereum keys should work with your custom networks or testnets.







Executing test transactions by calling the functions from wallet.py
BTCTest transaction
```btc_acc = priv_key_to_account(BTCTEST,btc_PrivateKey) ``` ```create_trx(BTCTEST,btc_acc,"miZgMxdGzSxCTpWazfD2KqhewoUvcQ6CC1", 0.1)``` ```send_trx(BTCTEST,btc_acc,'m_____________________',0.1)```

Confirmation of Executed Transaction






ETH transaction - using local private blockchain
```eth_acc = priv_key_to_account(ETH,eth_PrivateKey) ```
```create_trx(ETH,eth_acc,"_________________", 1000)``` 
```send_trx(ETH, eth_acc,"__________________", 1000)```

Confirmation of Executed Transaction
