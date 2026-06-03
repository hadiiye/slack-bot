# My very first Fun Slack Bot 🏓🐱

## About
Slack Bot provides simple and entertaining slash commands for Slack users. The bot responds to commands with useful information, random cat facts, and jokes fetched from public APIs.
This project was built to learn Slack bot development, API integration, and cloud deployment.

## Features
   ### `/dsb-ping`
   Checks whether the bot is online and measures response latency.
   eg: Pong!
      Latency: 5ms
  
   ### `/dsb-catfact`
   Returns a random cat fact.
   eg:Cat Fact:
      Cats can jump up to six times their length.

  ### `/dsb-joke`
  Returns a random joke.
  eg:Why don't scientists trust atoms?
  Because they make up everything!

## Tech Stack
- JavaScript
- Node.js
- Slack Bolt
- Slack Socket Mode
- Axios
- dotenv
  
## How It Works
The bot uses Slack Bolt and Socket Mode to listen for slash commands. When a command is received, the bot either:
- Calculates and returns latency information
- Fetches a random cat fact from an API
- Fetches a random joke from an API
The response is then sent directly back to Slack.

## What I Learned
This project was built while I was learning JavaScript and Slack app development. 
Through building this bot, I gained experience working with APIs, environment variables, slash commands, and deploying applications to the cloud.
Through this project I learned a lot of things:
- How to create a Slack app
- How slash commands work
- Basic JavaScript and Node.js development
- How to use external APIs
- How to manage environment variables
- How to deploy applications on Hack Club Nest

## Challenges
I had faced little difficulty as I was still learning a lot of things
- Understanding Slack app configuration
- Setting up Socket Mode
- Working with asynchronous API requests
- Deploying and keeping the bot running 24/7

## Future Improvements
I have a lot to improve on, and I'm planning to:
- Add more slash commands
- Add weather and trivia features
- Improve message formatting
- Add user preferences
- Integrate AI-powered responses

## Acknowledgements <3
- Stardust Hackathon
- Hack Club
- Slack Developer Platform
- Cat Fact API
- Official Joke API

## Author
Built by Hadiya for Stardust Hack club Hackathon 🚀💗

  

