# Vipcase Telegram bot

This is the code for the Telegram bot — [@vipcasebot](http://t.me/vipcasebot), that control VIP access to chat rooms and channels.

# Installation and local launch

1. Clone this repo: `git clone https://github.com/Kiku-Reise/vipcase`
2. Launch the [mongo database](https://www.mongodb.com/) locally
3. Create `.env` with the environment variables listed below
4. Run `yarn install` in the root folder
5. Run `yarn develop`

And you should be good to go! Feel free to fork and submit pull requests. Thanks!

# Environment variables

- `USERNAME` — Telegram bot username
- `TOKEN` — Telegram bot token
- `CHANNEL_HANDLE` — Handle of the Telegram ad channel
- `CHANNEL_ID` — ID of the Telegram ad channel
- `MONGO`— URL of the mongo database

Bot should be admin at `CHANNEL_ID`.
Also, please, consider looking at `.env.sample`.

# License

MIT — use for any purpose. Would be great if you could leave a note about the original developers. Thanks!
