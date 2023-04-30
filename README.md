# DiceTracker.py

## This version of the tool has been customized to work with the [AnuBitux](https://anubitux.org) live system. To use it with other environments, please refer to the [main branch](https://github.com/ASeriousMister/DiceTracker.py)

A tool that returns private keys and addresses or generates a printable paper wallet for many different cryptocurrencies, allowing users to paste a 256 bits binary key, the result of 256 dice rolls, or helping them tracking 256 dice rolls.

### Tutorial
[Here](https://anubitux.org/how-to-generate-random-paper-wallets-with-anubitux/) you can see how the tool works.


### Utilization
User simply has to provide answers to the prompted questions.
At the end, the tool will show private keys and public addresses and, if wanted, generates a printable paper wallet in the PaperWallet directory.
If user does not want to generate the printable paper wallet, keys are not stored anywhere.
QrCodes of the information can also be obtained with tools like qrencode.

### Example keys
- Binary key: 0000001100101011100101110101101000101000011001011010000111010100000011101100011111110010001000101010010010101101111100010011100111011100110110101001111001110110100011001010100110101101010000010100110000110011011010111101001110010101110010010001000001101001
- 256 dice rolls reuslts: 1423353625241324352413243526252525243534666554653645463535262525162525363532526251252626353433533536225356225251414255336355242142253633534242411252535364453534242525161525343422525161625253434252516162525434352521661252443434252516162525434352525166542512
These keys can be used only to test the tool. Do not send transactions to the addresses generated from the example keys.

### Supported coins
The tools supports the following coins, to add more simply edit the code referring to hdwallet documentation for the correct symbols
- Bitcoin
- Ethereum
- Litecoin
- Bitcoin Cash
- Bitcoin SV
- Dash
- ZCash
- DogeCoin
- Bitcoin Testnet
- Monero

### Disclaimer
This ool comes with no guarantees. Do your own research about how this tool works and in general about how cryptocurrency keys work before using it.

### Credits & Donations
This tool is part of the [AnuBitux](https://anubitux.org) project. 
If you appreciate this work visit https://anubitux.org and consider making a donation
- BTC: 1AnUbiYpuFsGrc1JFxFCh5K9tXFd1BXPg
- XMR: 87PTU58siKNb3WWXcP4Hq4CmCb7kMQUsEiUWFT7SvvMMUqVw9XXFGrJZqmnGvuJLGtLoRuEqovTG4SWqkPr8YLopTSxZkkL
