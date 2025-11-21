# 💰 Expense Tracker

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Speech_Recognition-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Speech Recognition"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License"/>
</p>

<p align="center">
  <b>A smart expense tracker with voice recognition — manage your budget without typing! 🎙️</b>
</p>

<p align="center">
  <a href="#-installation">📦 Installation</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-how-it-works">🎯 How It Works</a> •
  <a href="#-tech-stack">🛠️ Tech Stack</a>
</p>

---

## 📋 Table of Contents

- [Problem Statement](#-problem-statement)
- [Solution](#-solution)
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Tech Stack](#-tech-stack)
- [Tools Used](#-tools-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Future Scope](#-future-scope)
- [Contributing](#-contributing)
- [License](#-license)

---

## ❓ Problem Statement

Managing personal finances is essential but often neglected due to:

- ⌨️ **Tedious Data Entry** — Manually typing every expense is time-consuming and boring
- 📱 **On-the-Go Challenges** — Hard to log expenses quickly when you're busy
- 🗂️ **Disorganized Records** — Expenses scattered without proper categorization
- 📊 **No Clear Overview** — Difficult to understand spending patterns
- 🎯 **Budget Tracking** — Hard to know if you're staying within budget
- 😓 **Inconsistent Logging** — People give up tracking due to the effort required

---

## 💡 Solution

It is a voice-powered expense tracker that makes budget management effortless. Simply speak your income or expense, and the app does the rest — no typing required!

### ✨ Why ?

| Benefit | Description |
|---------|-------------|
| 🎙️ **Voice Input** | Add expenses by speaking — no typing needed! |
| ⚡ **Quick Entry** | Log transactions in seconds |
| 🗂️ **Auto Categorization** | Expenses are automatically categorized |
| 📊 **Clear Overview** | See your income vs expenses at a glance |
| 🗑️ **Easy Management** | Delete and organize transactions effortlessly |
| 💸 **Budget Friendly** | Track where your money goes |

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎙️ **Speech Recognition** | Add income/expenses using your voice |
| ➕ **Add Income** | Record money coming in |
| ➖ **Add Expenses** | Track money going out |
| 🗂️ **Categorization** | Organize transactions by category |
| 🗑️ **Delete Transactions** | Remove entries easily |
| 📊 **Balance Overview** | See total income, expenses, and balance |
| 💾 **Persistent Storage** | Data saved locally |
| 📱 **Responsive Design** | Works on all devices |

---

## 🎯 How It Works

### Voice Commands

Simply speak naturally to add transactions:

```
🎙️ "Add income of 5000 rupees from salary"
🎙️ "Add expense of 200 rupees for food"
🎙️ "Spent 500 on shopping"
🎙️ "Received 1000 from freelance work"
```

### Workflow

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  🎙️ Speak       │────▶│  🧠 Speech      │────▶│  📝 Transaction │
│  Your Input     │     │  Recognition    │     │  Created        │
└─────────────────┘     └─────────────────┘     └────────┬────────┘
                                                         │
                                                         ▼
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│  📊 View        │◀────│  🗂️ Auto        │◀────│  💾 Saved to    │
│  Dashboard      │     │  Categorized    │     │  Storage        │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) | User Interface |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Programming Language |
| ![Web Speech API](https://img.shields.io/badge/Web_Speech_API-4285F4?style=flat&logo=google&logoColor=white) | Speech Recognition |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling |

---

## 🔧 Tools Used

| Tool | Purpose |
|------|---------|
| ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) | Version Control |
| ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white) | IDE |
| ![npm](https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white) | Package Manager |
| ![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat&logo=google-chrome&logoColor=white) | Testing (Speech API) |

---

## 📦 Installation

### Prerequisites

- Node.js 14+
- npm
- Modern browser with Speech Recognition support (Chrome recommended)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/armaan-arora/expense-tracker.git

# 2. Navigate to project directory
cd expense-tracker

# 3. Install dependencies
npm install

# 4. Start the application
npm start
```

### 🌐 Access the App

Open your browser and navigate to:

```
http://localhost:3000
```

---

## 🚀 Usage

### Adding Transactions with Voice

1. **Click the microphone button** 🎙️
2. **Speak your transaction** — e.g., "Add expense of 500 for groceries"
3. **Transaction is automatically added** ✅

### Manual Entry

1. Select **Income** or **Expense**
2. Enter the **amount**
3. Choose a **category**
4. Add a **description** (optional)
5. Click **Add** ➕

### Managing Transactions

- 👁️ **View** — See all transactions in the list
- 🗑️ **Delete** — Click the delete button to remove
- 📊 **Track** — Monitor your balance in real-time

### Example Voice Commands

| Command | Result |
|---------|--------|
| "Add income 50000 salary" | ➕ Income: ₹50,000 (Salary) |
| "Add expense 2000 for food" | ➖ Expense: ₹2,000 (Food) |
| "Spent 500 on transport" | ➖ Expense: ₹500 (Transport) |
| "Received 10000 from freelance" | ➕ Income: ₹10,000 (Freelance) |

---

## 📊 Categories

### Income Categories
| Category | Icon |
|----------|------|
| 💼 Salary | Regular employment income |
| 💻 Freelance | Contract/gig work |
| 📈 Investments | Returns from investments |
| 🎁 Gifts | Money received as gifts |
| 💰 Other | Miscellaneous income |

### Expense Categories
| Category | Icon |
|----------|------|
| 🍔 Food | Groceries, dining out |
| 🚗 Transport | Fuel, public transport |
| 🏠 Housing | Rent, utilities |
| 🛍️ Shopping | Clothes, electronics |
| 🎬 Entertainment | Movies, subscriptions |
| 💊 Health | Medical expenses |
| 📚 Education | Books, courses |
| 💳 Bills | Phone, internet, etc. |

---

## 📁 Project Structure

```
expense-tracker/
├── 📂 public/
│   ├── index.html
│   └── favicon.ico
├── 📂 src/
│   ├── 📂 components/
│   │   ├── Balance.jsx           # Balance display
│   │   ├── IncomeExpenses.jsx    # Income/Expense summary
│   │   ├── TransactionList.jsx   # List of transactions
│   │   ├── AddTransaction.jsx    # Add transaction form
│   │   └── VoiceInput.jsx        # Speech recognition
│   ├── 📂 context/
│   │   └── GlobalState.js        # App state management
│   ├── 📂 utils/
│   │   └── speechRecognition.js  # Voice processing
│   ├── App.js                    # Main component
│   ├── App.css                   # Styles
│   └── index.js                  # Entry point
├── 📄 package.json
└── 📄 README.md
```

---

## 🔮 Future Scope

| Feature | Description | Priority |
|---------|-------------|----------|
| 📊 **Charts & Graphs** | Visual spending analytics | High |
| 🌙 **Dark Mode** | Toggle between themes | High |
| 💾 **Cloud Sync** | Backup data to cloud | High |
| 🔐 **User Authentication** | Personal accounts | Medium |
| 📅 **Monthly Reports** | Spending summaries | Medium |
| 🎯 **Budget Goals** | Set and track budgets | Medium |
| 🔔 **Spending Alerts** | Notifications when over budget | Medium |
| 📱 **Mobile App** | React Native version | Low |
| 🌍 **Multi-Currency** | Support different currencies | Low |
| 📤 **Export Data** | Download as CSV/PDF | Future |

---

## ⚠️ Browser Support

Speech Recognition works best in:

| Browser | Support |
|---------|---------|
| ![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=flat&logo=google-chrome&logoColor=white) | ✅ Full Support |
| ![Edge](https://img.shields.io/badge/Edge-0078D7?style=flat&logo=microsoft-edge&logoColor=white) | ✅ Full Support |
| ![Safari](https://img.shields.io/badge/Safari-000000?style=flat&logo=safari&logoColor=white) | ⚠️ Partial Support |
| ![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=flat&logo=firefox&logoColor=white) | ❌ Limited Support |

> 💡 **Tip:** Use Google Chrome for the best experience!

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/amazing-feature`)
3. 💾 Commit your changes (`git commit -m 'Add amazing feature'`)
4. 📤 Push to the branch (`git push origin feature/amazing-feature`)
5. 🔃 Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Armaan Arora**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/armaan-arora)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/armaan-singh-29bb54247/)

---

## 🙏 Acknowledgements

- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) — Speech recognition
- [React](https://reactjs.org/) — UI framework

---

<p align="center">
  ⭐ Star this repo if you found it helpful! ⭐
</p>

<p align="center">
  Made with ❤️ by Armaan Arora
</p>

<p align="center">
  <i>Track your expenses with your voice! 💬💰</i>
</p>
