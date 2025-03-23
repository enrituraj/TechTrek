# **TechTrek – Your Personalized Tech Reading Tracker** 🚀

TechTrek is a habit-building platform designed to help users stay consistent with reading tech blogs. It allows users to **log in, explore tech blogs, track progress, maintain streaks, and even add their own resources**. With a streak system and insightful analytics, TechTrek makes learning engaging and structured.  

---

## 🌟 **Features**

### **🔐 User Authentication**
- Sign up/Login using **Google or Email/Password** (Firebase Authentication).

### **📜 Tech Blog Directory**
- Browse a list of **top tech companies** with their **logos**.
- Click on a company to visit its **official blog**.
- Add **custom blog links** for personalized learning.

### **📆 Daily Reading Challenge**
- A **daily task reminder** (_"Read one blog today!"_) on the dashboard.
- Check off completed days and add **personal notes** on what you learned.

### **📊 Dynamic Reading Status**
- Track your reading progress with a **status dropdown**:
  - ✅ **Completed**
  - 📖 **Reading**
  - ❌ **Not Completed**

### **🔥 Streak System & Progress Tracking**
- Maintain a **reading streak** like Snapchat to stay motivated.
- **Streak resets** if a day is missed.
- Earn **visual rewards** (🔥 streak counter).

### **📈 Weekly, Monthly & Yearly Insights**
- View **detailed analytics** of your reading habits:
  - **Weekly progress** 📅
  - **Monthly stats** 📊
  - **Yearly achievements** 🎯
- See what you read **each day** and track your knowledge growth.

### **☁️ Firebase Integration**
- **Firestore Database** stores logs, notes, custom resources, and streak data.
- **Cloud Functions** handle automated tasks like streak resets and reminders.

---

## 🚀 **Tech Stack**

| Technology    | Purpose |
|--------------|---------|
| **React.js** | Frontend framework |
| **Tailwind CSS** | UI styling |
| **Firebase Authentication** | User authentication |
| **Firestore Database** | Storing user data |
| **Netlify Hosting** | Deployment |
| **Cloud Functions** | Automated tasks |

---

## 🎯 **How to Run the Project**

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/enrituraj/TechTrek.git
cd TechTrek
```

### **2️⃣ Install Dependencies**
```bash
npm install
```

### **3️⃣ Set Up Firebase**
- Create a **Firebase Project**.
- Enable **Authentication (Google, Email/Password)**.
- Set up **Firestore Database**.
- Add your **Firebase Config** in `.env`:
```env
VITE_FIREBASE_API_KEY=your-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
VITE_FIREBASE_APP_ID=your-app-id
```

### **4️⃣ Start the Development Server**
```bash
npm run dev
```
> The app will be live at `http://localhost:5173/`

---

## 🎨 **Screenshots**

| Dashboard | Streak Tracker | Progress Analytics |
|-----------|---------------|--------------------|
| ![Dashboard](https://via.placeholder.com/300) | ![Streak Tracker](https://via.placeholder.com/300) | ![Progress Analytics](https://via.placeholder.com/300) |

---

## 🛠 **Future Enhancements**
- 📌 **Dark Mode Support**
- 🎯 **Gamification Features (Badges & Rewards)**
- 📅 **Calendar View for Reading Progress**
- 🔔 **Push Notifications for Daily Reminders**

---

## 🤝 **Contributing**
1. **Fork** the repository.
2. **Create** a new branch: `git checkout -b feature-branch`
3. **Commit** your changes: `git commit -m 'Added a new feature'`
4. **Push** to the branch: `git push origin feature-branch`
5. **Submit a Pull Request** 🎉

---

## 📜 **License**
This project is licensed under the **MIT License**. Feel free to use and modify it as you like!

---

## 📬 **Contact**
For any questions or suggestions, reach out via:
- 📧 Email: `rn26rituraj@gmail.com`
- 🔗 Website: [View My Portfolio](https://enrituraj.in)
- 🔗 LinkedIn: [View My LinkedIn](https://linkedin.com/in/enrituraj)

---

### 🎉 **Start your tech learning journey with TechTrek today!** 🚀
