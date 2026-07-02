
# 🌐 PolyTone
> **📌 Note:** The complete source code and project files are available in the **`polytone`** branch of this repository. Please switch to the `polytone` branch to view the implementation.

**PolyTone** is an AI-powered multilingual communication platform that enables real-time speech translation while preserving the speaker's tone, emotion, and natural speaking style. Unlike traditional translation tools, PolyTone focuses on making conversations feel authentic rather than robotic.

## ✨ Features

- 🎙️ Real-time speech-to-speech translation
- 🌍 Supports multiple languages
- 😊 Tone and emotion preservation
- 🔊 Natural-sounding translated speech
- ⚡ Low-latency communication
- 🖥️ Simple and intuitive user interface

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Node.js
- Express.js

### AI & Cloud Services
- Amazon Transcribe
- Amazon Translate
- Amazon Polly
- AWS S3
- AWS Lambda *(if applicable)*

## 📂 Project Structure

```
PolyTone/
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── package.json
│
├── README.md
└── .gitignore
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or above)
- npm
- AWS Account
- AWS CLI configured (optional)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/polytone.git
cd polytone
```

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd ../server
npm install
```

Create a `.env` file in the server directory and add your AWS credentials and configuration:

```env
AWS_ACCESS_KEY_ID=YOUR_KEY
AWS_SECRET_ACCESS_KEY=YOUR_SECRET
AWS_REGION=YOUR_REGION
PORT=5000
```

## ▶️ Running the Application

Start the backend:

```bash
cd server
npm start
```

Start the frontend:

```bash
cd client
npm run dev
```

The application should now be running locally.

## 📸 Screenshots

Add screenshots or GIFs here.
<img width="578" height="1314" alt="Screenshot 2026-07-02 220618" src="https://github.com/user-attachments/assets/ee16b977-72ae-4e7c-b850-af7aec2f498d" />

<img width="570" height="1326" alt="Screenshot 2026-07-02 220752" src="https://github.com/user-attachments/assets/6e33aa4c-751a-4d56-8adf-3d29d5acf775" />

<img width="534" height="1318" alt="image" src="https://github.com/user-attachments/assets/2265f844-3b27-4e17-89c0-cca4801b734c" />




```
/screenshots/home.png
/screenshots/translation-demo.gif
```

## 🎯 Future Improvements

- More language support
- Voice cloning
- Conversation history
- Mobile application
- Live meeting integration
- Speaker identification

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.


## 👩‍💻 Author

**Pragya Sharma**

Feel free to connect or contribute to the project!
