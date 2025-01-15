
###  Challenge: Web3 Frontend Developer Task

#### Objective:
Build a **Next.js application** similar to [Termix.ai](https://app.termix.ai) that provides Web3 features like cryptocurrency swaps, data insights, and AI-powered interactions, ensuring a clean and modular implementation.

---

### Features and Detailed Requirements

#### 1. **User Authentication with Privy**
   - **Details**:
     - Integrate **Privy** to manage user authentication via wallets or email.
     - Display user profile information after successful login.
     - Provide logout functionality to securely end sessions.

#### 2. **AI-Powered Chat Interface**
   - **Details**:
     - Build a real-time **AI chatbot** using **ChatGPT API**.
     - Capabilities include:
       - Responding to general queries.
       - Cryptocurrency-related questions (e.g., "What is the price of BTC?").
       - Guiding users on swap operations (e.g., "How do I swap ETH for USD?").
     - Maintain a scrollable chat history with timestamps.
   - **Advanced Features** (Optional):
     - Support slash commands (e.g., `/price BTC`, `/swap ETH USD 1`).
     - Error messages for invalid commands.

#### 3. **Cryptocurrency Insights**
   - **Details**:
     - Fetch and display real-time data using the **CoinGecko API**:
       - Current price of BTC and ETH.
       - 7-day or 30-day price charts (using Chart.js or Recharts).
     - Display a user-friendly interface for cryptocurrency insights.
   - **UI Expectations**:
     - A dedicated dashboard or section for crypto prices and charts.

#### 4. **Real Swap Execution**
   - **Details**:
     - Integrate the **Enso API** to enable real token swaps.
     - User inputs:
       - Source token (dropdown or text input).
       - Target token (dropdown or text input).
       - Amount to swap.
     - Workflow:
       - Validate the user’s wallet balance before executing the swap.
       - Fetch real-time exchange rates from the Enso API.
       - Allow users to confirm the swap, then execute it via the API.
       - Display transaction status and success/failure notifications.
   - **UI Expectations**:
     - A clean modal or dedicated page for swap operations.
     - Display a summary before execution (e.g., "You are swapping 1 ETH for X USD").
     - Show wallet balances for selected tokens.

#### 5. **User-Friendly Dashboard**
   - **Details**:
     - Combine all features into a cohesive, intuitive dashboard.
     - Include:
       - Cryptocurrency price and chart widgets.
       - AI chatbox.
       - Swap section.
     - Provide clear navigation for all functionalities.

#### 6. **Frontend Design**
   - **Details**:
     - Take inspiration from Termix.ai’s minimal and modern UI.
     - Use **TailwindCSS** or **Material-UI** for a clean design.
     - Ensure responsive design for mobile and desktop users.
     - Consistent theming across all components.

#### 7. **Code Quality and Modularity**
   - **Details**:
     - Maintain a clean and modular codebase:
       - Separate API calls into a dedicated services folder.
       - Use custom hooks (e.g., `useFetchCryptoData`, `useEnsoSwap`).
       - Reusable components for UI elements.
     - Implement **TypeScript** for better type safety and maintainability.
     - Document code with comments where necessary.

---

### Evaluation Criteria

1. **Functionality**:
   - Does the application cover all core features (login, chat, swap, price display)?
   - Is the swap functionality seamless and reliable?

2. **Design**:
   - Is the UI user-friendly and similar to Termix.ai’s clean design principles?
   - Does it provide a good user experience on both desktop and mobile?

3. **Code Quality**:
   - Is the code modular, reusable, and well-documented?
   - Are best practices followed for API integration and state management?

4. **API Integration**:
   - Are APIs correctly integrated with proper error handling?
   - Do all features rely on real-time data where applicable?

---

### Submission Instructions

1. **GitHub Repository**:
   - Include the project in a public or private GitHub repository.
   - Add a **README** with:
     - Project setup and running instructions.
     - Feature overview and implementation details.

2. **Demo Deployment**:
   - Deploy the application (e.g., Vercel, Netlify).
   - Provide a live demo link with test credentials (if required).

---

### Bonus Points

- **Theming**: Support light and dark modes.
- **Localization**: Multi-language support for the interface.
- **Analytics**: Add simple user activity logging (e.g., swaps, queries).
- **Tooltips**: Help users understand swap operations and commands.

---

This challenge ensures a comprehensive test of your Web3 and AI integration skills while maintaining clean architecture and a focus on user experience. Good luck! 🚀
