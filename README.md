# Dextools Volumes Bot

## Briefly, this bot is needed to sell Volumes per 24h in order to raise the token to the top


for example, your budget is $2500
if your settings are like below you will get approximately 80k
These are the optimal settings; if you want to receive more Volumes, you need to increase the budget.
Moreover, if you change the settings, namely the sales time, the bot may become unstable!

after the profit is reached, your budget will automatically return from your working wallets to your main one.
if during the work the bot completed its work with an error or you accidentally closed the program, then your budget will be located in the last 5 wallets in the used folder
volumes per hour.
The bot checks the coin rate as well as the ETH rate.

approximate calculations of work and obtaining volume
We divide $1000 into 5 accounts
Each sale every 1 minute we receive about $1000-980 to our volume, but it is worth considering that with each round the balance decreases due to expenses for commissions, etc. Accordingly, our volumes decrease exponentially
From this we get what (1 lap = 1 minute)
1 minute profit = $1000-980
2 minute profit = $1000-950
3 minute profit = $980-930

etc.
Attention, all calculations are approximate!!


I made the slip automatic but no more than 40%

## how to use:

Go to etherscan\dextools - copy Contract Address token and paste in config
Create new MAIN wallet - Deposit $ - take private key and paste in config
Generate private key for Worker wallets - https://visualkey.link/ or another site\program and paste in generated.txt
Open **Volumes Trending Bot.exe** when the program starts, the config.ini check will pass; if the settings check was successful, the program will continue to work; if not, it will tell you what needs to be corrected; when the program starts, you will see an action log; if the program fails, you will receive an error in debug.log


-------------------------------------------------

## Settings:

1. paste your contract address token to "CA ="
2. paste your private key from main wallet to "MainWallet ="
3. generated wallet = path to .txt - don't touch, generated file in folder automatically.
4. used wallets = path to .txt - don't touch, generated file in folder automatically.
5. WalletMainSender_fix = 100 \\ 100$ | if WalletMainSender_smart is false then it sends a fixed amount to work wallets
6. time_to_sell_min = 30 \\ in sec "0" to off
7. time_to_sell_max = 85 \\ in sec "0" to off
8. WalletToWork = 5 \\ 1-2-3-10
9. RayUniJup = 2 \\ 1-Raydium | 2-Uniswap | 3-Jupiter
10. WalletMainSender_smart = true \\ sends different amounts to work wallets
11. StopVolumeProfit = 350000 \\ 350k

# TEST 30min:

![Screenshot_16](https://github.com/turbor1/Dextools-Volumes-Bot/assets/155108454/95ea7405-aed3-4e66-9e28-4b4f6203c4cc)
![Screenshot_17](https://github.com/turbor1/Dextools-Volumes-Bot/assets/155108454/b3f18d92-0dca-4216-848d-0c7c7b439d4d)


**This is a demo, if you want to buy the full version, write to me in PM**
