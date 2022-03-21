# ETH-Batch-Import-Privatekey-Brute-Force
A simple python script that generate random privatekeys and check if there's Ether in the account.
# Kizmeow-OpenSea-and-Etherscan-Discord-Bot

Requirements
-----------------
**environment**

+ Python > 3.8

**packages**

+ web3.py

Usage
-----------------
change infura api url in `main.py` and run it.

This is only a concept. According to Etherscan, there are 191,119,471 eth holders currently. 

Private key is a 64 bits hex number. That means there are 

`16 ** 64 = 115792089237316195423570985008687907852837564279074904382605163141518161494336 (1.157920892373162e+77)`

permutations. And you have 

`191,119,471` / `1.157920892373162e+77` = `1.6505399657164846e-69`
chance to broke into an account with ETH per try

It will takes you centries to broke into an account with ETH😂
