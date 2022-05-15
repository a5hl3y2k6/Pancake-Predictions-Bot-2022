
# **🥞 The Only Real PancakeSwap Prediction Bot  🤖**

Predictions bot for PancakeSwap & CandleGenie

![PancakeSwap-Logo-Big](https://github.com/parames3010/PancakeswapPredictionBot-2022/blob/main/pancake.png)
<p align="center">
  <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022/releases">
    <img alt="GitHub all releases" src="https://img.shields.io/github/followers/parames3010?style=social">
  </a>
  <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/stars/parames3010/PancakeswapPredictionBot-2022?style=social">
  </a>
   <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/forks/parames3010/PancakeswapPredictionBot-2022?style=social">
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=PancakeSwap">
    <img src="https://img.shields.io/twitter/follow/PancakeSwap?style=social" alt="Follow @PancakeSwap" />
  </a>

This bot wins majority of rounds on PancakeSwap & CandleGenie based on both market conditions, and the strategy chosen.

## 🧑‍🚀 Setup

1. open/edit **.env** file with notepad, you may need to show hidden files to see it if your using a mac
2. Provide your private key to .env PRIVATE_KEY field. between the " "
3. Adjust your bet amount by changing the number between the " "in bet amount "0.01" - is the minimum.
4. Start Installation Procedure below.



## 💡 Installation

Download & Install Node here :
https://nodejs.org/en/download/

Windows:
Go to Start > Run > 'type cmd and press enter'
This will open command prompt, enter the following commands

- Type ``cd``  and then input the directory you have downloaded the bot folder too, or drag the folder into the command prompt after typing cd then press enter.
- Type ``yarn install`` and then press enter, this will download the required components for the script to run.
- Type ``yarn start`` the script will then start and wait for the next predictions epoch to begin.


``yarn start`` will run the bot with the standard algorithm and bet against the majority for better odds. but less success.

``yarn start --exp`` will run the bot 'With' the majority for more wins, but less odds

Both results are roughly the same, although standard seems to have a slightly better payout in most situations.

### 🦊 How to Export Private Key from MetaMask
1. Open your account
2. Click on three points at top-right corner
3. Account details
4. Export Private Key.


## 🧪 Screenshots

To check history of the rounds you played, head over to: https://pancakeswap.finance/prediction

![History](https://user-images.githubusercontent.com/37302442/142716425-eb32f875-a767-4f22-abf1-6d97071dbd6d.png)


#### 📢 Advice:

- Run the bot with your wallet at a ratio of 10x the amount you choose to bet
- Adjust the bot accordingly to bet with or against the majority.
- When the chart swings, use the "--with" strategy.
- When the chart trends sideways, use the default, against strategy.
- Always monitor & adjust the bot accordingly but allow room for error.
- Consistent gains will be made by running smaller betting amounts over longer periods of time.
- Always account & allow room for error. Losing 3 sucks, but stopping it only prevents it from potentially winning the next 4 & bringing you to a profit.
- Majority of the runs with over 2k plays I have a standard 54-66% win rate depending on how well I monitor it & based on market conditions.


## 💥 Disclaimers

All investment strategies and investments involve risk of loss.

**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, and should not be construed as, a recommendation or as a guarantee of any specific outcome or profit. By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.
