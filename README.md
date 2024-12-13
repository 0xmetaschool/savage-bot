# SavageBot Discord

SavageBot is the most brutally honest AI-powered Discord bot that delivers savage, witty, and hilariously brutal responses. It's designed to roast users with creative comebacks while keeping it entertaining. 

## Live Demo


## Features
* Brutally honest and savage short one sentence responses 
* Sleek black and white landing page with smooth animations
* Easy set up and integration to discord

## Technologies Used
* Next.js 14 for the landing page
* OpenAI API for generating savage responses
* Discord.js for bot functionality
* Tailwind CSS for styling
* Lucide icons for UI elements

## Use Cases
* Providing savage commentary on user activities
* Making your Discord server less boring and more entertaining

## Installation Steps

### 1. Clone and Setup

#### Clone the repository
```bash
git clone https://github.com/0xmetaschool/savage-bot
```

#### Navigate to project directory
```bash
cd dicord-bot
```

#### Install dependencies
```bash
npm install
```

### 2. Discord Bot Setup
1. Go to [Discord Developer Portal](https://discord.com/developers/applications)
2. Click "New Application" and name it
3. Go to "Bot" section
   - Click "Add Bot"
   - Under "Privileged Gateway Intents", enable:
     * Presence Intent
     * Server Members Intent
     * Message Content Intent
   - Reset Token and copy it (save for .env)

4. Set up OAuth2:
   - Go to OAuth2 > URL Generator
   - Under "Scopes" select:
     * `bot`
     * `applications.commands`
   - Under "Bot Permissions" select:
     * Read Messages/View Channels
     * Send Messages
     * Read Message History
   - Copy the generated URL to invite bot to servers

### 3. Environment Setup
Create a `.env` file in the root directory:
```env
DISCORD_TOKEN=your_discord_bot_token
OPENAI_API_KEY=your_openai_api_key


### 4. Start the Application
```bash
# Start the Next.js development server
npm run dev

# In a separate terminal, start the bot
node bot/bot.js
```
Open your browser and navigate to http://localhost:3000

## Screenshots


## How to Use
1. Add the bot to your server using the generated OAuth2 URL
2. The URL format will be:
```
https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&permissions=199744&scope=bot+applications.commands
```
3. Start chatting with the bot
4. Prepare to be roasted
5. Try not to cry


## Contributing
We love contributions! Here's how you can help make the project even better:

Fork the project (gh repo fork https://github.com/0xmetaschool/savage-bot.git)
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
If you can handle more roasting, open an issue in the GitHub repository.

## Credits
- OpenAI for providing the GPT-4 API
- Discord.js team for the amazing library
