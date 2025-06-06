# KiteAI Auto Bot

An automated bot for interacting with KiteAI testnet, performing daily tasks, and maximizing rewards.

## Features ✨

- **Automated Interactions**: Chat with KiteAI agents (Professor, Crypto Buddy, Sherlock)
- **Daily Faucet Claim**: Automatically claim daily KITE tokens
- **Staking System**: Stake tokens and claim rewards automatically
- **Multi-Wallet Support**: Manage multiple wallets simultaneously
- **Smart Analytics**: Track XP points, staking info, and rewards
- **Scheduled Execution**: Runs daily with countdown timer

## Prerequisites 📋

- Node.js v16+
- Ethereum wallet private key(s)
- [2Captcha API key](https://2captcha.com/)(for faucet claims)

## Installation ⚙️

1. Clone the repository:
```bash
git clone https://github.com//kazmight/KiteAI-Auto-Bot.git
cd KiteAI-Auto-Bot
```

2. Install dependencies:
```bash
npm install
```

3. Open a `.env` file 
```env
PRIVATE_KEY_1=your_private_key_here
# Add more wallets as needed
```

## For running script

Run the bot:
```bash
node index.js
```

The bot will:
1. Login with your wallet(s)
2. Display profile information
3. Claim daily faucet (if 2Captcha key provided)
4. Stake tokens and claim rewards
5. Interact with all agents using random prompts
6. Schedule next run in 24 hours

## Wallet Setup 💰

1. Get testnet ETH from a faucet
2. Get initial KITE tokens from the [KiteAI faucet](https://testnet.gokite.ai)
3. Stake at least 1 KITE token to start earning rewards


- Never share your private keys
- Use environment variables for sensitive data
- The bot only interacts with official KiteAI endpoints
- Code is open for audit

## Don't forget to join my telegram channel for update script

https://t.me/dasarpemulung


## Disclaimer ⚠️

This is an unofficial tool for educational purposes only. Use at your own risk. The developers are not responsible for any losses.

## License 📜

MIT
