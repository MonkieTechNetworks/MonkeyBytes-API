# 📜 MonkeyBytes-API

![MonkeyBytes-API Banner](https://cdn.discordapp.com/banners/1051503632677359686/0d039ec11c1709a1c1987bfbcaad6e7c.png?size=1024&format=webp&quality=lossless&width=0&height=256)

Welcome, noble traveler, to the realm of MonkeyBytes-API, maintained by palidintheonly. Herein lies your gateway to the latest decrees and features. Our server stands as a bastion of knowledge, ensuring a steadfast and secure experience for all who seek its counsel.

## 🌟 Latest Updates
- Added new features to enhance user experience
- Improved server stability and performance
- Updated documentation for better clarity
- Enhanced security measures

---

## ⚙️ Features
- **Express Server**: Secure, fast, and reliable Node.js & Express backend.
- **Helmet Integration**: Provides essential security headers out of the box.
- **Winston Logging**: Detailed logging for seamless debugging and analytics.
- **Random Cat Images**: Fetch adorable cat images from The Cat API on demand. 🐱
- **Reddit RSS Fetching**: Fetch and post the newest Reddit posts to Discord webhooks automatically. 🔄
- **Updates System**: Fetch the latest updates from `updates.json` and display them on the root endpoint.

---

## 🚀 Getting Started

1. **Clone the Repository**  
   `$ git clone https://github.com/<your-username>/MonkeyBytes-API.git`

2. **Install Dependencies**  
   `$ cd MonkeyBytes-API && npm install`

3. **Configure Environment**  
   - Update the **Discord Webhook URLs** and **RSS URLs** in the code to match your setup.
   - Adjust **PORT** or other constants as needed.

4. **Run the Server**  
   `$ npm start`  
   The API will be accessible at [http://localhost:21560](http://localhost:21560) by default.

---

## 🎉 Usage

- **Root Endpoint (`/`)**  
  Displays a welcome page with the latest updates, server uptime, and UK time.

- **Testing Endpoint (`/testing`)**  
  Returns two random cat images, a random cat fact, a randomly generated bot name, and a robohash avatar URL.

- **Reddit RSS to Discord**  
  Automatically fetches new posts from configured subreddits every 5 minutes and sends them to Discord webhooks.

---

## 🤝 Contributing

We welcome all manner of contributions, be they big or small!  
1. Fork this repository  
2. Create a feature branch  
3. Commit and push your changes  
4. Open a pull request, explaining your noble contribution

---

## 📜 License & Acknowledgments

© 2025 **MonkeyBytes-API** by **palidintheonly**. All rights reserved.

May your code compile swiftly, and your logs be ever in your favor!  
**Huzzah!**
