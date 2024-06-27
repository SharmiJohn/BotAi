# AI Bot Application

This is an AI Bot application that answers your questions. You can interact with the bot by typing in your questions, and it will provide relevant answers. The application also includes features for giving feedback, switching between light and dark modes, and saving your chat history.

## Features

- **Question and Answer Interaction**: Type in your questions and receive answers from the AI Bot.
- **Feedback System**: Provide feedback by clicking the like or dislike button.
- **Rating**: Rate the bot's responses.
- **Dark and Light Mode**: Switch between dark mode for night view and light mode for day view.
- **Save and View Chats**: Save your chat history and view it whenever you want.

## Technologies Used

- **React**: For building the user interface.
- **Material UI**: For styling and UI components.
- **Date-fns**: For date formatting.
- **React Icons**: For icons used in the application.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SharmiJohn/BotAi
   cd ai-bot-application
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start the application**:

   ```bash
   npm start
   ```

4. **Build the application** (for production):

   ```bash
   npm run build
   ```

## Usage

1. **Ask a Question**: Type your question in the input box and hit enter. The AI Bot will respond with an answer.
2. **Provide Feedback**: Click the like or dislike button to provide feedback on the bot's response.
3. **Rate the Response**: If you like a response, you can give it a rating by clicking the rating stars.
4. **Switch Modes**: Use the toggle switch to switch between dark mode and light mode.
5. **Save Chats**: Save your chat history by clicking the save button. You can view your saved chats later.

## File Structure

```plaintext
ai-bot-application/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── ChattingCard.js
│   │   ├── FeedbackModal.js
│   │   └── ...
│   ├── assets/
│   │   ├── AI.png
│   │   ├── human.png
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
└── README.md
```
