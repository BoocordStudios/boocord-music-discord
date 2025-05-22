# Boocord Music (Discord)

A feature-rich music bot for Discord with MySQL stats and playlist support, built on the Boocord Music API.

## Installation

1. Clone this repository  
   `git clone ...`
2. Install dependencies  
   `npm install`
3. Copy `.env.example` to `.env` and fill in your credentials.
4. Make sure you have Node.js (19.9.x), MySQL and ffmpeg installed.

## Disclaimer

Only Node.js 19.9.x was tested and is used to run the bot in a production environment.  
There is no guarantee that it will work with higher or lower versions.

## Usage

Start the bot with  
`node src/index.js`  
or  
`npm start` (if defined in your package.json)

## Configuration

Edit the `.env` file:

DISCORD_TOKEN=your-discord-bot-token
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=password
DB_NAME=boocordmusic

## License

This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.

## API Terms

**Commercial use is only permitted in video and streaming contexts**  
(e.g., YouTube, Twitch, or similar platforms).  
All other commercial uses are prohibited. See [API_TERMS.md](./API_TERMS.md).