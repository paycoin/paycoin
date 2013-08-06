[ANN][PYC]Paycoin-PoW/PoS |Transaction Comment|Fair start|0 Premine

Version [1.0.0]



[Announcing Paycoin - PYC, the latest and most innovative PoW/PoS coin! Fair start and zero premined!

Paycoin combines the best from Bitcoin/Litecoin/Novacoin/Florincoin/Cosmoscoin, it uses both Proof of Work and Proof of Stake. This provides good resistence to 51% attack. It also supports transaction comments like Florincoin, so when you send transactions to the pay, you and your receiver won't be lost! Moreover, this coin has very low transaction fees (only 0.1% of most other coins), and fast transaction confirmation time (1.5 min). It provides steady coin supply at 3.5 coins per block.

Paycoin has a fair start and zero premined, making it one of the very best of the alt coins exist today.


Features:

- Proof of Work Combined with Proof of Stake
- Transacation Comment like FlorinCoin
- Low Transaction Fee (Min Fee is 0.00001 Coins)
- Quick Confirmation fro Transaction
- Resistence to 51% attack
- Stable Reward Per Block (with the total number of 1 billion and reward 3.5 coins per block, the generation of paycoinis stable during more than 270 years)


Specifications:

- Proof of work/proof of stake 
- Scrypt
- 30 seconds block time
- 3.5 coins per block
- Day generation: 10080 coins or 2880 blocks
- 480 blocks retarget (4 hours)
- Trade confirm: 3
- Mine confirm: 30
- Total number of coins 1000000000 (1 billion) 
- fair start, no premine
- port: Connection: 9288 and RPC Port:9289 


Website:
http://www.paycoin.co

Blockchain Explorer:
- to be added -


Sample Paycoin.conf:

[code]listen=1
daemon=1
server=1
rpcuser=**Yourusername**
rpcpassword=**Yourpassword**
rpcport=9289
rpcconnect=127.0.0.1




Getting Started:

1. Start up paycoin-qt, wait for it to load, then exit.
2. Put paycoin.conf (see sample file above) in your c:/users/**yourcomputername**/Appdata/Roaming/Paycoin
3. restart paycoin-qt, and you should connect and sync.
4. For solo mining, launch cgminer or the mining program you use and begin mining.
      cgminer ex: cgminer.exe --scrypt -o localhost:9289 -u **yourusername** -p **password** (without **)
