### Web3 Frontend Developer Challenge

#### Objective:
Develop a **Next.js application** that showcases your Web3 and AI development skills by creating a chat-based app. The app will include user authentication, AI chatbot functionality, cryptocurrency data integration, and a modular codebase.

---

### Features and Detailed Requirements

#### 1. **User Authentication with Privy**
   - **Feature**: Implement a secure login mechanism using **Privy** for user authentication.
   - **Details**:
     - Allow users to log in with their wallet or email.
     - After successful login, display the user's profile (e.g., username, email, or wallet address).
     - Provide a logout button to end the session securely.
   - **UI Expectations**:
     - A clean and simple login page.
     - A profile display component after login.

---

#### 2. **Chat Interface**
   - **Feature**: A real-time chat interface with basic AI chatbot capabilities.
   - **Details**:
     - Users can type questions or commands in a chatbox.
     - Display chatbot responses in real-time.
     - Integrate with **ChatGPT API** to provide intelligent responses for user queries.
   - **Commands**:
     - "What is the current price of BTC?"
     - "Show me the BTC chart."
     - "I want to swap ETH to USD."
   - **UI Expectations**:
     - Chat bubbles for user input and AI responses.
     - Scrollable chat history.

---

#### 3. **Cryptocurrency Data Integration**
   - **Feature**: Fetch and display real-time cryptocurrency data using the **CoinGecko API**.
   - **Details**:
     - **BTC Price**: Show the live price of Bitcoin (BTC) when the user requests it.
     - **BTC Chart**: Render a graphical price trend for Bitcoin (e.g., using a charting library like Chart.js or Recharts).
     - **Swap Simulation**: Accept user commands for swapping, e.g., "I want to swap 1 ETH to USD," and:
       - Fetch the latest ETH price.
       - Calculate the equivalent USD value.
       - Display the calculated swap amount (simulation only; no actual transaction required).
   - **UI Expectations**:
     - A clear display of BTC price and chart.
     - A simple modal or response box for swap results.

---

#### 4. **AI Chatbot Integration**
   - **Feature**: Use **OpenAI GPT-4** (or equivalent) for chatbot functionality.
   - **Details**:
     - Respond to cryptocurrency-related queries intelligently.
     - Understand commands like:
       - "What is the current price of BTC?"
       - "How much USD can I get for 2 ETH?"
       - "Show me the BTC chart."
     - If the query is not related to crypto, provide a generic response (e.g., "I'm here to assist with cryptocurrency-related queries.").
   - **UI Expectations**:
     - Smooth integration with the chat interface.
     - Appropriate error handling for invalid queries.

---

#### 5. **Frontend Design**
   - **Feature**: Create a responsive and intuitive user interface.
   - **Details**:
     - Use a modular approach to design UI components.
     - Components to include:
       - **Login Page**: For Privy authentication.
       - **Chat Interface**: For user interactions with the AI chatbot.
       - **BTC Price Display**: A widget showing the live BTC price.
       - **BTC Chart**: A chart component for price trends.
       - **Swap Calculator**: A modal or section for swap simulation results.
   - **UI Expectations**:
     - Responsive design for mobile and desktop views.
     - Use a modern UI library (e.g., TailwindCSS, Material-UI) for styling.

---

#### 6. **Code Quality**
   - **Feature**: Ensure clean, modular, and maintainable code.
   - **Details**:
     - Separate code into reusable components, hooks, and services:
       - **Components**: UI elements like LoginForm, ChatBox, BTCPriceWidget, etc.
       - **Hooks**: Custom hooks for fetching data (e.g., `useFetchCryptoPrice`).
       - **Services**: API integration logic for CoinGecko and OpenAI APIs.
     - Use TypeScript for type safety.
     - Add comments and documentation where necessary.

---

### Bonus Features (Optional)
- **Theming**: Allow users to toggle between light and dark mode.
- **Localization**: Support multiple languages for the interface.
- **Wallet Integration**: Provide a button for connecting a crypto wallet (e.g., MetaMask) and display wallet details.

---

### Evaluation Criteria

1. **Functionality**:
   - Does the app meet all requirements (login, chat, BTC price/chart, AI responses, swap simulation)?
   - Are all features implemented and working as intended?

2. **Code Quality**:
   - Is the code modular, reusable, and well-documented?
   - Are best practices followed (e.g., error handling, clean architecture)?

3. **UI/UX Design**:
   - Is the interface clean, intuitive, and responsive?
   - Does the design provide a smooth user experience?

4. **API Integration**:
   - Are APIs correctly integrated with proper error handling?
   - Does the app provide accurate data from CoinGecko and ChatGPT?

---

### Submission Instructions
- **GitHub Repository**:
  - Upload the complete project code to GitHub.
  - Include a **README** with:
    - Setup instructions.
    - Description of features and approach.
- **Demo**:
  - Provide a live demo link (e.g., Vercel, Netlify).
  - Ensure the demo is functional and accessible.

Good luck with the challenge!
