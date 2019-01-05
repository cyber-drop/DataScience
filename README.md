# DataScience

## Ethereum Miners Analysis over Time  
`How mining pools and miners behaved in time`  
Paper here: https://medium.com/cyber-drop/ethereum-miners-analysis-over-time-7dbe32b328fe  

## How we searched for miners for Robonomics token airdrop  
`We found the addresses of active mining pools and miners`  
Paper here: https://medium.com/cyber-drop/how-we-searched-for-miners-for-robonomics-token-airdrop-9b64e5c70f68  

## DApp Transactions Analysis: Etheroll suspicious gambler  
`41% of the bets were delivered by a suspicious system of linked addresses.`  
Paper here: https://medium.com/@cyber_drop/dapp-transactions-analysis-etheroll-suspicious-gambler-f37a7263da5  

## [DApp Transactions Analysis: Dice2win Case Study](https://github.com/cyber-drop/DataScience/blob/master/dice2win/dice2win.md)  
`52% of the bets were delivered by a suspicious system of linked addresses.`  
Paper here: https://medium.com/@cyber_drop/dapp-transactions-analysis-dice2win-case-study-cbbf0f29f2f0  

## Huge Ethereum Mixer  
`68% of total Ethereum transaction value controlled by one system`  
Paper here:https://blog.cyber.fund/huge-ethereum-mixer-6cf98680ee6c  
Python notebook here: [transaction_analysis_huge_ethereum_mixer_171125.ipynb](https://github.com/cyber-drop/DataScience/blob/master/transaction_analysis_huge_ethereum_mixer_171125.ipynb)
For working with ipython3 notebook you need:
1. Install and synchronize Parity 1.6.10 (sync Parity db isn't less than 24GB)
2. Launch ethdrain.py (https://github.com/cyberFund/ethdrain) with following parametrs:
    python3 ethdrain.py -o csv
3. Copy "transactions.csv" to path ipython3 notebook
4. Run all in transaction_analysis_huge_ethereum_mixer.ipynb
