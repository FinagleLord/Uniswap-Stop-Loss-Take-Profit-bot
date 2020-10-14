Bot Instructions:

First things first, you're going to want to find the .env.example file, open it up and you'll find some variabless 
you need to fill out, such as your API_KEY, PORT, and PRIVATE_KEY. Once filled out, rename the file to '.env'
.
.
.
.
.
.
Next, you'll want to open the index.js file. Inside you'll find variables numbered 1-6 that you're going to have to change. 
.
.
1. DAI_CONTRACT_ADDRESS                            <--- Default is testnet be sure to change contract addresses if you plan to use Mainnet!!!
2. UNISWAP_EXCHANGE_DAI_CONTRACT_ADDRESS           <--- Default is testnet be sure to change contract addresses if you plan to use Mainnet!!!    
3. TRADING_AMOUNT
4. STOP_LOSS_PRICE
5. TAKE_PROFIT_PRICE
6. GAS_SPEED_PREFERENCE
.
.
Once these are filled out your on to the last step...
.
.
.
.
INSTALL:

cd PATH_YOU_INSTALLED_TO

npm install

USE:

cd PATH_YOU_INSTALLED_TO

npm run start

