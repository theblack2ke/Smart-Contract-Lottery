## 🎟️ Raffle Smart Contract

This smart contract implements a decentralized raffle (lottery) system where participants can enter by sending a fixed entry fee. At the end of the raffle period or when specific conditions are met, a random winner is selected, and the entire prize pool is transferred to the winner.

### Key Features
- **Fair Entry**: Participants join the raffle by sending the required Ether entry fee.
- **Random Winner Selection**: Utilizes Chainlink VRF for tamper-proof randomness, ensuring fairness in winner selection.
- **Automated Execution**: A winner is picked either manually or automatically (depending on the configuration).
- **Secure Prize Distribution**: The prize pool is securely sent to the winner's wallet.

### How It Works
1. Users enter the raffle by calling the `enterRaffle()` function and paying the entry fee.
2. The contract tracks all participants during the raffle period.
3. A random winner is selected using Chainlink VRF (or another secure random generator).
4. The winner is awarded the total prize pool, minus any applicable fees.

### Requirements
- **Chainlink VRF**: Ensures randomness.
- **Ether Entry Fee**: Fixed amount set during contract deployment.
- **Admin Role**: (Optional) For managing the raffle.

### Why This Contract?
This contract ensures fairness, transparency, and security, making it ideal for decentralized raffles.

---

### Thank You! 🙏
Thank you for checking out this project! I hope you find it useful and inspiring.

Feel free to connect with me:
- **X (Twitter)**: [@theblack_2ke](https://x.com/theblack_2ke)

---

Let me know if there’s anything else you’d like to add! 😊

