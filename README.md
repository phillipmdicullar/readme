# 🌍 Safari Vendors E-Commerce Site 
🛒 Welcome to **Safari Vendors**, your go-to online marketplace for local foods at affordable prices. This project is built using **React** for the frontend and **JSON Server** for mock backend services. The entire application is hosted on **Vercel**, ensuring fast and reliable access allover the internet. 
## 🎨 Preview ![safari-vendors](https://github.com/user-attachments/assets/6b58cade-f043-4b1d-9344-fa8aefbf9d3a)

## 🚀 Live Demo Check out the live version of Safari Vendors here: [**Safari Vendors on Vercel**](https://your-vercel-link) 
## 🛠️ Project Setup 
# System Requirements
- Core i5cpu && above 
- 4Gigabytes of ram and above
- 128Gb storage space and above

### Prerequisites 
- Node.js & npm 
- React 
- JSON Server 

### Installation 1. 
**Clone the repository**: 
- ```bash [git clone https://github.com/philipmdicullar/safari-vendors.git](https://github.com/phillipmdicullar/Phase-2-Group8-SafariVendorsProject)```
- ```cd Phase-2-Group8-SafariVendorsProject ``` 

2. **Install dependencies**: 

- ```npm install ``` 
3. **Run JSON Server**: 

- ```json-server --watch db.json```
The server will be running at `http://localhost:3000`. 
4. **Start the React app**:
- ```npm start ``` 
- Open `http://localhost:3001` to view the app in your browser.
 

## 🖥️ Technologies Used 
- **Frontend**: React, HTML, CSS 
- **Backend**: JSON Server (Mock Data), Node.js 
- **Hosting**: Vercel (Frontend & Backend) 
- **Deployment**: Continuous Integration/Continuous Deployment (CI/CD) with Vercel
## 🌟 Features 
- 🔍 **Search Functionality**: Easily search for your favorite local foods. 
- 🛒 **Add to Cart**: Browse products and add them to your cart. 
- 🛠️ **Dynamic Categories**: Filter products by category to find exactly what you're looking for. 
- 📦 **Checkout**: Seamlessly proceed to checkout and place your orders. 
-  🖌️ **Styling**: The project: is styled with **Tailwind** and **CSS** to ensure a responsive and user-friendly interface. We aim to deliver a delightful user experience with a focus on simplicity and elegance. 

## 🚧 Future Enhancements 
- **User Authentication**: Implement user login and signup features. 
- **Backend Integration**: Replace JSON Server with a real backend. 
- **Product Reviews**: Allow customers to leave reviews and ratings for products.
- ## 👥 Contributing We welcome contributions from the community! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome. 
1. **Fork the repository** 
2. **Create your feature branch** (`git checkout -b feature/YourFeature`) 
3. **Commit your changes** (`git commit -m 'Add SomeFeature'`) 
4. **Push to the branch** (`git push origin feature/YourFeature`) 
5. **Open a Pull Request** 
## 📝 License This project is licensed under the MIT License 
- see the [LICENSE](LICENSE) file for details. 
## ✨ Acknowledgments to our senior dev's 🙉🙉
- Big thanks to **Bethuel Khisa**
- Big thanks to **Norah Kinyamasyo**
- Big thanks to **Terry Solidad**
   <p align="center"> Made with ❤️ by <a href="https://github.com/phillipmdicullar">Philip Emdokolo🤧</a> </p>


# 🚀 Automated Donation Platform

## 📌 Project Five: Automated Donation Platform

### 🛑 Problem Statement
In many sub-Saharan countries, school-going girls lack access to sanitary pads and essential hygiene supplies. A **2016 study by the Ministry of Education** revealed that girls from low-income families miss approximately **20% of school days each year** due to a lack of sanitary towels. 

📊 The data indicated that:
- A **primary school girl (Class 6-8)** could lose up to **18 weeks out of 108 weeks** of learning.
- A **high school girl** could miss nearly **24 weeks out of 144 weeks**.

An organization dedicated to addressing this issue aims not only to provide **sanitary towels** but also to improve access to **clean water** and **sanitation facilities** such as toilets. This effort ensures adherence to **UNICEF's guidelines** for proper menstrual hygiene management.

### 💡 Solution
To support this initiative, the organization seeks to raise funds by encouraging **repeat donations**. The goal is to develop a platform that facilitates **automated recurring donations**, allowing users to contribute regularly. This system will enable donors to **set up monthly or one-time donations** of specified amounts, ensuring sustainable funding for the cause.

---

## 🛠️ Team
- **Full Stack Development:** React (Frontend) & Python Flask (Backend)

## 👥 Users
1. **Charities** 🏥
2. **Donors** 💖
3. **Administrators** 🛡️

---

## 📖 User Stories
### 🏅 Donor
- 🔎 **Browse** a variety of charities to donate to
- 🔑 **Create an account** on the platform
- ❤️ **Select a charity** to support
- 💵 **Donate** to a charity
- 🔄 **Set up automated recurring donations** or **one-time donations**
- 🕵️ **Choose to donate anonymously** or publicly
- ⏰ **Receive monthly reminders** to donate
- 📖 **View impact stories** from beneficiaries
- 💳 **Donate via PayPal, Stripe, or other third-party services**

### 🏥 Charity
- 📌 **Apply for approval** to be listed on the platform
- ⚙️ **Set up and manage charity details** (after approval)
- 👤 **View donations from non-anonymous donors**
- 🏦 **View total donation amounts from anonymous donors**
- 📊 **Track the total donations received**
- 📢 **Create and share stories** of beneficiaries
- 📋 **Maintain records of beneficiaries** and inventory provided to them

### 🛡️ Administrator
- 📩 **Review and process charity applications**
- ✅ **Approve or reject charity applications**
- ❌ **Remove charities** from the platform if necessary

---

## ⚙️ Technical Expectations
- **Backend:** Python Flask 🐍
- **Database:** PostgreSQL 🗄️
- **Wireframes:** Figma (Mobile-friendly), Framer, or Adobe XD 🎨
- **Testing Frameworks:** Jest & Minitest 🧪
- **Frontend:** React.js with Redux Toolkit ⚛️

---

## 💻 System Requirements
To run this project, ensure you have the following installed:
- ✅ **Node.js** (Latest LTS version recommended)
- ✅ **Python 3.8+**
- ✅ **PostgreSQL** (Database Management System)
- ✅ **npm** or **yarn** (For frontend dependencies)
- ✅ **pip** (For backend dependencies)

---

## 🚀 Installation & Setup
### 🔙 Backend (Flask API)
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo/automated-donation-platform.git
   cd automated-donation-platform
   ```
2. **Navigate to the backend directory:**
   ```sh
   cd backend
   ```
3. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
5. **Set up the database:**
   ```sh
   flask db upgrade
   ```
6. **Run the backend server:**
   ```sh
   flask run
   ```

### 🎨 Frontend (React App)
1. **Navigate to the frontend directory:**
   ```sh
   cd frontend
   ```
2. **Install dependencies:**
   ```sh
   npm install  # Or use `yarn install`
   ```
3. **Start the frontend server:**
   ```sh
   npm start  # Or use `yarn start`
   ```

---

## 🤝 Contribution
We welcome contributions to improve this platform. Feel free to **fork** the repository, make changes, and submit **pull requests**. 

## 📜 License
This project is **open-source** and available under the **MIT License**.

---

By automating donations and improving transparency, this platform aims to **enhance charitable giving** and provide **sustainable support** for menstrual hygiene initiatives. 

💡 **Let's build a future where no girl misses school due to a lack of basic hygiene supplies.** 🚀


