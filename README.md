📌 Chatbot Web App – Detailed Description

1. Overview: What This Program Does
This program is a single‑page chatbot web application built with React. It allows a user to:
- Type messages into an input box
- Send messages by clicking “Send” or pressing Enter
- Display messages in a chat-style interface (user messages on the right, bot messages on the left)
- Show a loading spinner while waiting for a chatbot response
- Automatically scroll the chat window to the latest message

The app uses:
- React functional components
- React hooks (useState, useRef, useEffect)
- A custom hook for auto‑scrolling
- An external Chatbot API (Chatbot.getResponseAsync)


2. High-Level Structure
The program consists of:
- HTML & CSS for layout and styling
- React components for UI and behavior
- A custom React hook for scrolling logic

Main React Components:
1) App – Root component
2) ChatMessages – Displays the messages list
3) ChatMessage – Displays a single message bubble
4) ChatInput – Handles user input and sending messages
5) useAutoScroll – Custom hook for automatic scrolling
