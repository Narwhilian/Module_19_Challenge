# Blockchain Wallet Transactions

This python file establishes a wallet for the ethererium 'ether' crypto currency and allows the user to make easy transactions to pay a wage to a preselected set of accounts and validates the transaction.

---

## Technologies

This project uses the Python Programming language in a python file (.py) as well as the following libraries
    
    - streamlit
    - dataclass
      - List (type)
      - Any (type)
    - os
    - requests
    - dotenv
    - bip44
    - web3

---

## Installation Guide

To install you will want to pull the entire Blockchain_Wallet folder from github. The folder contains the following files and subfolders
    

    * fintech_finder.py (the python file you will be running)
    * crypto_wallet.py (python file we import into the fintech_finder to allow us to generate a wallet, find the ether balance, and send transactions)
    * Images (folder containing images used in the streamlit user profiles)
    * Screenshots (folder containing screenshots used in this readme file)
    * ReadMe (This file)


You will also need to be sure to have a .env file containing a mnemonic seed phrase and a web3 infura project id. They will need to be labled identically to the following example for the code to run correctly

```
MNEMONIC = 'your seed phrase here'
WEB3_INFURA_PROJECT_ID = 'your project ID here'
```

---

## How it works

1) First the user will open their terminal (I used git bash) and navigate into the Blockchain_Wallet folder
2) Then the user will simply run the fintech_finder.py file using streamlit by typing in 
```
streamlit run fintech_finder.py
```
    
3) from there it should automatically open a webpage displaying your account balance in ether as well as the hiring options and hourly rates they charge
4) Then all you have to do is select a person to hire from the dropdown menu and the number of hours you want to hire them for and click the 'send transaction' button on the sidebar like in the example below.

![streamlit-fintech_finder-2021-10-04-16-10-54](https://user-images.githubusercontent.com/84096312/135939218-195186e6-d7cd-4093-8e2e-53daa1093aca.gif)



Here is a screenshot of my activity on etherscan. You can see the transaction above on the top of my transaction history.

![etherscan](https://user-images.githubusercontent.com/84096312/135938897-a91fd98c-68d4-4a0b-b28d-7afbd04c4fdf.png)


Here are the details of the example transaction

![transaction details](https://user-images.githubusercontent.com/84096312/135938935-4b1e604b-9fe9-49a8-b048-8ad6f42bcb2f.png)


And Finally here is the transaction history of the account recieving my example transaction. You will notice that my transaction is at the top of the list since it is the most recent one for this account 

![receiver history](https://user-images.githubusercontent.com/84096312/135939030-e04445aa-c630-4dd7-8d34-8397eafd6284.png)



---

## Usage

Overall it should be a very simple application to use, all you need to do is open the terminal, navigate to where you have stored the fintech_finder.py file and then run the file on streamlit by typing the following line into your terminal
```
streamlit run fintech_finder.py
```
---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

(c) Copyright 2021 Colin Benjamin

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
