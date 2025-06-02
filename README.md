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
- KiteAI testnet access https://testnet.gokite.ai?referralCode=S86CD815

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

## Configuration ⚙️

Edit the `prompt.txt` file to customize your agent interactions. Format:
```
[Professor]
What is Kite AI's core technology?
How does Kite AI improve developer productivity?
What are the key features of Kite AI's platform?
How does Kite AI handle data security?
Explain Kite AI tokenomics in detail
What is the role of AI in blockchain technology?
How does Kite AI ensure data privacy?
What are the benefits of decentralized AI systems?

[Crypto Buddy]
What makes Kite AI different from other AI platforms?
How does Kite AI integrate with existing systems?
What programming languages does Kite AI support
How does Kite AI's API work?
What are Kite AI's scalability features?
How does Kite AI help with code quality?
What is Kite AI's approach to machine learning?
How does Kite AI handle version control?

[Sherlock] 
Analyze this transaction: 0x252c02bded9a24426219248c9c1b065b752d3cf8bedf4902ed62245ab950895b
Is this address safe? 0x7c3dD8E62A7C32c04172042e0Ec4C42428d57958
Check the security of this contract: 0x7c3dD8E62A7C32c04172042e0Ec4C42428d57958
Analyze this transaction: 0xbbe4ffa3cd53cc5e6bd64b4ab07e8e1166460e726a564479578d733c2b8f342b
Is this address safe? 0x8a2BcE14093493D52c23d3cDa913056893c3ACB5
Check the security of this contract: 0x6a7c453f5777e205953c03D3bFA20e6539419Ae3
Analyze this transaction: 0x25c7e00a6bbbafa636d99b60c156efa98911e4bbbbfd5672bf60f87a8a53d6cf
Is this address safe? 0x297C897Cb327d71C2f6590AFEA95446b666F61c9
Check the security of this contract: 0xeE567Fe1712Faf6149d80dA1E6934E354124CfE3
Analyze this transaction: 0x5d02e6e3a7183caf283e69b27477b97c618e91744f00244f1a5bfa298d48f50f
Is this address safe? 0x3786B8a73186a44a89e0C6461F12910924FbB969
Check the security of this contract: 0x5FbE74A283f7954f10AA04C2eDf55578811aeb03
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

## Contribution 🤝

Pull requests are welcome! For major changes, please open an issue first.

## Disclaimer ⚠️

This is an unofficial tool for educational purposes only. Use at your own risk. The developers are not responsible for any losses.

## License 📜

MIT
