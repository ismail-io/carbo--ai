# Carbon Track AI 🌱

A web application for tracking and analyzing carbon footprints using AI technology.

## Features

- 📊 Carbon footprint tracking and analysis
- 🤖 AI-powered receipt analysis using Google Gemini
- 📸 Image processing with OCR
- 🗺️ Route planning with carbon emission calculations
- 📧 Email notifications for events
- 📈 Dashboard with environmental news and statistics

## Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Shadcn UI Components
- Leaflet for maps

**Backend:**
- Node.js
- Express.js
- MongoDB
- JWT Authentication

**APIs:**
- Google Gemini AI
- News API
- EmailJS
- Pinata (IPFS)

## Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Setup

1. Clone the repository:
```bash
git clone https://github.com/ismail-io/carbo--ai.git
cd carbo--ai
```

2. Install server dependencies:
```bash
cd server
npm install
```

3. Install client dependencies:
```bash
cd ../client
npm install
```

4. Configure environment variables:

Create a `.env` file in the `server` directory:
```
JWT_SECRET=your_jwt_secret
JWT_REFRESH_SECRET=your_refresh_secret
GEMINI_API_KEY=your_gemini_api_key
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

5. Update API keys in client files:
- News API in `client/src/assets/Dashboard.js`
- Gemini API in `client/src/assets/ImageProcess.js`
- EmailJS in `client/src/assets/EmailSender.js`
- Pinata API in `client/src/assets/ImageProcess.js`

## Running the Application

1. Start the backend server:
```bash
cd server
node app.js
```

2. Start the frontend:
```bash
cd client
npm start
```

3. Open your browser and navigate to `http://localhost:3000`

## Usage

1. Register a new account or login
2. Upload receipts to analyze carbon footprint
3. View your carbon tracking dashboard
4. Plan eco-friendly routes
5. Track your environmental impact over time

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License

## Contact

For questions or support, please open an issue on GitHub.
