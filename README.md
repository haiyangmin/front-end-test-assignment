# Frontend Developer Test Task – Hotelier Chatbot Widget

## Overview
This task simulates building a small production-style feature: a **chatbot widget for hoteliers**.

The focus is on:
- Frontend architecture and UI quality
- Vue component design and state handling
- Clean, maintainable, well-structured code
- Basic backend integration and polling logic

You will build:
- A **Vue 3** frontend that renders a chat widget
- A **Node.js** backend that simulates chatbot behavior
  
- ## Functional requirements

### Chat widget (Frontend)
- Floating chat launcher in the **bottom-right corner**
- Clicking the launcher opens a chat window
- Chat window includes:
  - Header with:
    - Title (e.g. "Hotel Assistant")
    - **Expand** button
    - **Close** button
  - Scrollable message list
  - Message input + send button
- Expand button toggles between:
  - Normal size
  - Expanded view (responsive, large screen friendly)
- Close button hides the chat window and shows the launcher again

### Messaging behavior
- User can type a message and send it
- User message appears in the chat
- Bot responds automatically via backend logic
- Different styling for **user** and **bot** messages
- Chat auto-scrolls to the newest message

