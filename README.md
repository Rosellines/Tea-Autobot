# Tea Auto Bot 🍵

A command-line interface (CLI) tool for automating interactions with the Tea Sepolia Testnet. This bot helps you manage your TEA tokens, stake, claim rewards, and perform various transactions on the Tea blockchain.

## Features

- 🔄 Send TEA to random addresses (single or batch)
- 📌 Stake TEA tokens
- 💰 Claim staking rewards
- 🔙 Withdraw stTEA tokens
- 🤖 Automated daily task (100 transfers)
- 🌐 Proxy support for network requests

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Rosellines/Tea-Autobot.git
cd Tea-Auto-Bot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with your private key:
```
PRIVATE_KEY=your_private_key_here
```

## Proxy Setup (Optional)

To use proxies with the bot, create a `proxies.txt` file in the root directory with one proxy per line in the format:
```
ip:port
http://username:password@username:password
```

## Usage

Start the bot:
```bash
npm start
```

### Main Menu Options:

1. **Send TEA to random addresses** - Transfer TEA to randomly generated addresses
2. **Stake TEA** - Stake your TEA tokens to earn rewards
3. **Claim rewards** - Claim your staking rewards
4. **Withdraw stTEA** - Withdraw your staked TEA tokens
5. **Daily task** - Execute 100 transfers of 0.0001 TEA (good for activity)
6. **Exit** - Exit the application

## Network Information

- **Network**: Tea Sepolia Testnet
- **RPC URL**: https://tea-sepolia.g.alchemy.com/public
- **Chain ID**: 10218
- **Symbol**: TEA
- **Explorer**: https://sepolia.tea.xyz/

## Security Notice

⚠️ **Important**: Never share your private key or `.env` file with anyone. Keep your keys secure.

## Support

Join our Telegram channel for support and updates: https://t.me/AirdropInsiderID

## License

MIT
