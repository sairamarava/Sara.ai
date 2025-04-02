# SaraAI - AI Chatbot

SaraAI is a simple AI chatbot that interacts with users using OpenRouter's API. It maintains conversation history and provides responses dynamically. This project is designed for seamless integration with the web and uses environment variables for API security.
## Features
- AI-powered chatbot using OpenRouter API.
- Conversation history tracking.
- Mobile-responsive UI with a sidebar menu.

## How It Works

1. **Frontend (JavaScript)**

   - Users type a query, and it is sent to the chatbot.
   - The chatbot sends the query to the OpenRouter API.
   - The response is fetched and displayed dynamically.

## Installation & Setup

### 1. Clone the Repository

```sh
 git clone https://github.com/your-repo/sara-ai.git
 cd sara-ai
```

### 2. Setup Environment Variables

Create a `.env` file in the root directory and add:

```sh
 API_KEY=your-api-key-here
 API_URL=https://openrouter.ai/api/v1/chat/completions
```

### 3. Run Frontend

Serve the `index.html` file using Live Server or any static file server.
## License

This project is open-source. Modify and distribute as needed.

## Contributors

- [Your Name]
- Feel free to contribute via pull requests!

