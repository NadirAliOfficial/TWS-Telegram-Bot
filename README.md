# TWS Telegram Bot

A Telegram bot interface for Interactive Brokers TWS — receive alerts and control trades via Telegram commands.

## Features
- Telegram command interface for TWS
- Real-time trade notifications
- Position and account status queries

## Requirements
```
pip install python-telegram-bot ib_insync
```

## Configuration
```python
TELEGRAM_TOKEN = "your_bot_token"
IB_HOST = "127.0.0.1"
IB_PORT = 7497
```

## Usage
```bash
python bot.py
```

## License
MIT
<!-- updated: 2023-10-28-r01 -->
