# 🤖 Messenger Bot Framework

A powerful and modular **Facebook Messenger Bot Framework** built with **Node.js**.  
This project includes a command system, event handlers, database support, uptime system, and dashboard-ready controllers.

---

## ✨ Features

- Modular command & event system  
- Auto uptime system  
- MongoDB & SQLite database support  
- User / Thread / Global data controller  
- Reply, Reaction & Event handlers  
- Easy configuration & customization  
- Dashboard-ready API structure  

---

## 📂 Project Structure

You said:

Ata dekhe amk github er readmd likhe de

ChatGPT said:
ঠিক আছে 👍
তোমার দেওয়া fork.zip প্রজেক্টটা দেখে নিচে GitHub README.md রেডি করে দিলাম। এটা সরাসরি কপি করে README.md ফাইলে বসাতে পারো।

🤖 Messenger Bot Framework (Fork Version)
একটি শক্তিশালী ও মডুলার Facebook Messenger Bot Framework, যা Node.js ব্যবহার করে তৈরি।
এই প্রজেক্টে command system, event handler, database support (MongoDB / SQLite), uptime system এবং dashboard-ready controller অন্তর্ভুক্ত আছে।

✨ Features
🔹 Modular command & event system

🔹 Auto Uptime system

🔹 MongoDB & SQLite database support

🔹 User / Thread / Global data controller

🔹 Reply, Reaction ও Event handler

🔹 Easy configuration & customization

🔹 Dashboard-ready API structure

📂 Project Structure
.
├── Main.js
├── account.txt
├── configCommands.json
├── includes/
│   ├── autoUptime.js
│   ├── custom.js
│   ├── connectDB/
│   │   ├── connectMongoDB.js
│   │   └── connectSqlite.js
│   ├── controller/
│   │   ├── dashBoardData.js
│   │   ├── globalData.js
│   │   ├── threadsData.js
│   │   ├── usersData.js
│   │   └── index.js
│   ├── handler/
│   │   ├── CheckData.js
│   │   ├── onEvent.js
│   │   ├── onReaction.js
│   │   └── onReply.js
│   └── utils/
│       └── ...
└── package.json
⚙️ Requirements
Node.js v16+

npm বা yarn

Facebook App & Page Access Token

(Optional) MongoDB Atlas / Local MongoDB

🚀 Installation
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
🔑 Account Setup
account.txt ফাইলে তোমার Facebook cookie / appState বসাও।

c_user=xxxx;
xs=xxxx;
⚠️ সতর্কতা: নিজের cookie কখনো পাবলিক করো না।

🗄️ Database Configuration
MongoDB ব্যবহার করতে চাইলে
includes/connectDB/connectMongoDB.js
SQLite ব্যবহার করতে চাইলে
includes/connectDB/connectSqlite.js
যেটা দরকার না সেটি disable করতে পারো।

▶️ Run the Bot
npm start
অথবা

node Main.js
🧠 Command System
Command config থাকে: configCommands.json

Handler গুলো:

onReply.js

onReaction.js

onEvent.js

নতুন command বানাতে চাইলে:

command ফাইল তৈরি করো

handler এ register করো

configCommands.json এ যুক্ত করো

📊 Dashboard Support
এই প্রজেক্টে dashboard এর জন্য আলাদা controller রয়েছে:

dashBoardData.js

usersData.js

threadsData.js

globalData.js

এগুলো API বা Web Dashboard এর সাথে সহজে connect করা যাবে।

🛠 Customization
Custom logic লিখতে পারো:

includes/custom.js
Auto uptime system:

includes/autoUptime.js
❗ Common Issues
Bot login না হলে → account.txt চেক করো

Database error → DB config চেক করো

Event কাজ না করলে → handler ফাইল চেক করো

📜 License
This project is for educational purposes only.
Any misuse is strictly discouraged.

❤️ Credits
Original Framework Author

Fork & Customization by You

Powered by Node.js

যদি চাও আমি এটাকে:

🔥 আরও Professional English README

🇧🇩 Pure Bangla README

🧾 Commands list সহ README

🌐 Dashboard + API documentation

— এগুলোর যেকোনো একটা বানিয়ে দিতে পারি।


You said:
Tui copy peast version de readme.md er ami cooy kore seikhne peast korbo

ChatGPT said:
নিচে একদম copy-paste ready README.md দিচ্ছি।
তুই সরাসরি কপি করে GitHub এ README.md ফাইলে পেস্ট করলেই হবে ✅

# 🤖 Messenger Bot Framework (Fork Version)

A powerful and modular **Facebook Messenger Bot Framework** built with **Node.js**.  
This project includes a command system, event handlers, database support, uptime system, and dashboard-ready controllers.

---

## ✨ Features

- Modular command & event system  
- Auto uptime system  
- MongoDB & SQLite database support  
- User / Thread / Global data controller  
- Reply, Reaction & Event handlers  
- Easy configuration & customization  
- Dashboard-ready API structure  

---

## 📂 Project Structure

.
├── Main.js
├── account.txt
├── configCommands.json
├── includes/
│ ├── autoUptime.js
│ ├── custom.js
│ ├── connectDB/
│ │ ├── connectMongoDB.js
│ │ └── connectSqlite.js
│ ├── controller/
│ │ ├── dashBoardData.js
│ │ ├── globalData.js
│ │ ├── threadsData.js
│ │ ├── usersData.js
│ │ └── index.js
│ ├── handler/
│ │ ├── CheckData.js
│ │ ├── onEvent.js
│ │ ├── onReaction.js
│ │ └── onReply.js
│ └── utils/
│ └── ...
└── package.json


---

## ⚙️ Requirements

- Node.js v16+
- npm or yarn
- Facebook account cookie / appState
- (Optional) MongoDB Atlas or Local MongoDB

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install




You said:

Ata dekhe amk github er readmd likhe de

ChatGPT said:
ঠিক আছে 👍
তোমার দেওয়া fork.zip প্রজেক্টটা দেখে নিচে GitHub README.md রেডি করে দিলাম। এটা সরাসরি কপি করে README.md ফাইলে বসাতে পারো।

🤖 Messenger Bot Framework (Fork Version)
একটি শক্তিশালী ও মডুলার Facebook Messenger Bot Framework, যা Node.js ব্যবহার করে তৈরি।
এই প্রজেক্টে command system, event handler, database support (MongoDB / SQLite), uptime system এবং dashboard-ready controller অন্তর্ভুক্ত আছে।

✨ Features
🔹 Modular command & event system

🔹 Auto Uptime system

🔹 MongoDB & SQLite database support

🔹 User / Thread / Global data controller

🔹 Reply, Reaction ও Event handler

🔹 Easy configuration & customization

🔹 Dashboard-ready API structure

📂 Project Structure
.
├── Main.js
├── account.txt
├── configCommands.json
├── includes/
│   ├── autoUptime.js
│   ├── custom.js
│   ├── connectDB/
│   │   ├── connectMongoDB.js
│   │   └── connectSqlite.js
│   ├── controller/
│   │   ├── dashBoardData.js
│   │   ├── globalData.js
│   │   ├── threadsData.js
│   │   ├── usersData.js
│   │   └── index.js
│   ├── handler/
│   │   ├── CheckData.js
│   │   ├── onEvent.js
│   │   ├── onReaction.js
│   │   └── onReply.js
│   └── utils/
│       └── ...
└── package.json
⚙️ Requirements
Node.js v16+

npm বা yarn

Facebook App & Page Access Token

(Optional) MongoDB Atlas / Local MongoDB

🚀 Installation
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
🔑 Account Setup
account.txt ফাইলে তোমার Facebook cookie / appState বসাও।

c_user=xxxx;
xs=xxxx;
⚠️ সতর্কতা: নিজের cookie কখনো পাবলিক করো না।

🗄️ Database Configuration
MongoDB ব্যবহার করতে চাইলে
includes/connectDB/connectMongoDB.js
SQLite ব্যবহার করতে চাইলে
includes/connectDB/connectSqlite.js
যেটা দরকার না সেটি disable করতে পারো।

▶️ Run the Bot
npm start
অথবা

node Main.js
🧠 Command System
Command config থাকে: configCommands.json

Handler গুলো:

onReply.js

onReaction.js

onEvent.js

নতুন command বানাতে চাইলে:

command ফাইল তৈরি করো

handler এ register করো

configCommands.json এ যুক্ত করো

📊 Dashboard Support
এই প্রজেক্টে dashboard এর জন্য আলাদা controller রয়েছে:

dashBoardData.js

usersData.js

threadsData.js

globalData.js

এগুলো API বা Web Dashboard এর সাথে সহজে connect করা যাবে।

🛠 Customization
Custom logic লিখতে পারো:

includes/custom.js
Auto uptime system:

includes/autoUptime.js
❗ Common Issues
Bot login না হলে → account.txt চেক করো

Database error → DB config চেক করো

Event কাজ না করলে → handler ফাইল চেক করো

📜 License
This project is for educational purposes only.
Any misuse is strictly discouraged.

❤️ Credits
Original Framework Author

Fork & Customization by You

Powered by Node.js

যদি চাও আমি এটাকে:

🔥 আরও Professional English README

🇧🇩 Pure Bangla README

🧾 Commands list সহ README

🌐 Dashboard + API documentation

— এগুলোর যেকোনো একটা বানিয়ে দিতে পারি।


You said:
Tui copy peast version de readme.md er ami cooy kore seikhne peast korbo

ChatGPT said:
নিচে একদম copy-paste ready README.md দিচ্ছি।
তুই সরাসরি কপি করে GitHub এ README.md ফাইলে পেস্ট করলেই হবে ✅

# 🤖 Messenger Bot Framework (Fork Version)

A powerful and modular **Facebook Messenger Bot Framework** built with **Node.js**.  
This project includes a command system, event handlers, database support, uptime system, and dashboard-ready controllers.

---

## ✨ Features

- Modular command & event system  
- Auto uptime system  
- MongoDB & SQLite database support  
- User / Thread / Global data controller  
- Reply, Reaction & Event handlers  
- Easy configuration & customization  
- Dashboard-ready API structure  

---

## 📂 Project Structure

.
├── Main.js
├── account.txt
├── configCommands.json
├── includes/
│ ├── autoUptime.js
│ ├── custom.js
│ ├── connectDB/
│ │ ├── connectMongoDB.js
│ │ └── connectSqlite.js
│ ├── controller/
│ │ ├── dashBoardData.js
│ │ ├── globalData.js
│ │ ├── threadsData.js
│ │ ├── usersData.js
│ │ └── index.js
│ ├── handler/
│ │ ├── CheckData.js
│ │ ├── onEvent.js
│ │ ├── onReaction.js
│ │ └── onReply.js
│ └── utils/
│ └── ...
└── package.json


---

## ⚙️ Requirements

- Node.js v16+
- npm or yarn
- Facebook account cookie / appState
- (Optional) MongoDB Atlas or Local MongoDB

---

## 🚀 Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


🔑 Account Setup
Put your Facebook cookie or appState inside account.txt

c_user=xxxx;
xs=xxxx;
⚠️ Never share your cookie publicly.

🗄️ Database Configuration
MongoDB
File:

includes/connectDB/connectMongoDB.js
SQLite
File:

includes/connectDB/connectSqlite.js
You can enable or disable any database as needed.

▶️ Run the Bot
npm start
or

node Main.js
🧠 Command System
Command config file: configCommands.json

Handlers:

onReply.js

onReaction.js

onEvent.js

To add a new command:

Create a command file

Register it in handler

Add config in configCommands.json

📊 Dashboard Support
Dashboard-related controllers:

dashBoardData.js

usersData.js

threadsData.js

globalData.js

These can be connected to any web dashboard or API.

🛠 Customization
Custom logic:

includes/custom.js
Auto uptime system:

includes/autoUptime.js
❗ Common Issues
Bot not logging in → Check account.txt

Database error → Check DB configuration

Event not working → Check handler files

📜 License
This project is for educational purposes only.
Any misuse is strictly discouraged.

❤️ Credits
Original Framework Author

Fork & Customization by You

Powered by Node.js
