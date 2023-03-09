Vite React.js ChatGPT App

This is a React.js chat application that allows users to chat with ChatGPT - an AI-based chatbot developed by OpenAI.
Setup

Before running the application, you need to set up the API_KEY in the config.js file. The API_KEY is a secret key that authorizes access to the ChatGPT API.

To set up the application, follow these steps:

    Clone this repository to your local machine.
    Navigate to the project directory and install the dependencies using the following command:

npm install

    Create a config.js file in the src folder and add the following code:

javascript

export const API_KEY = 'YOUR_API_KEY_HERE';

    Replace YOUR_API_KEY_HERE with your ChatGPT API key.
    Run the application using the following command:

npm run dev

    Open http://localhost:5173 to view the application in the browser.

Features

This application has the following features:

    A chat interface that allows users to send and receive messages from ChatGPT.
    The ability to send messages to ChatGPT by typing them into the input field and pressing enter.
    The ability to receive messages from ChatGPT and display them in the chat window.
    A typing indicator that shows when ChatGPT is typing a response.

Usage

To use the application, simply type a message into the input field and press enter. ChatGPT will respond with an appropriate message.
Credits

This application uses the following open-source libraries:

    React.js - A JavaScript library for building user interfaces.
    @chatscope/chat-ui-kit-react - A UI kit for building chat applications in React.
    @chatscope/chat-ui-kit-styles - A CSS library that provides styles for the chat UI kit.
    Vite.js - A build tool that provides fast and efficient building of JavaScript applications.
