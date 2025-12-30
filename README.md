# Samachar 📰  
## News Aggregation Web Application

Samachar is a full-stack MERN web application that provides users with the latest news in a clean, responsive, and modern interface. The platform aggregates news articles from multiple sources and categorizes them into topics such as Politics, Sports, Technology, and Entertainment.

## 🚀 Tech Stack
- MongoDB  
- Express.js  
- React.js  
- Node.js  
- News API  

## 🌟 Features
- Real-time news fetching from multiple sources  
- Category-wise news filtering (Politics, Sports, Technology, Entertainment)  
- Responsive and modern user interface  
- RESTful backend APIs using Express.js  
- Scalable MERN stack architecture  

## 📂 Project Structure
```
pre/
├── client/          # React frontend
├── server/          # Node.js & Express backend
├── package.json
└── README.md
```

## ⚙️ Installation & Setup
### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or cloud)
- News API key

### Steps
```bash
git clone https://github.com/dvdgamer2003/pre.git
cd pre

cd server
npm install

cd ../client
npm install
```

## 🔑 Environment Variables
Create a `.env` file inside the `server` directory:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
NEWS_API_KEY=your_news_api_key
```

## ▶️ Run the Application
```bash
# Start backend
cd server
npm start

# Start frontend
cd ../client
npm start
```

## 🎯 Future Enhancements
- User authentication  
- Article bookmarking  
- Search functionality  
- Dark mode  
- Personalized news recommendations  

## 👨‍💻 Developer
**Divyesh A Ravane**  
GitHub: https://github.com/dvdgamer2003  

## 📄 License
MIT License
