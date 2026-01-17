# 🚌 Bus Manager Pro (Cloud)

A serverless, mobile-first web application designed for transport business owners to manage student fees, track operational expenses, and calculate monthly profits in real-time.

**Live Demo:** [https://busmanager-939c2.web.app](https://busmanager-939c2.web.app)

## 🚀 Key Features
* **Cloud Sync:** Real-time data synchronization across devices using **Google Firestore**.
* **Secure Authentication:** User isolation via **Firebase Auth** (Google & Email/Password).
* **Financial Dashboard:** Automatic calculation of monthly revenue, pending dues, and net profit.
* **Student Management:** Track status (Active, Paused, Left) and historic payment records.
* **Mobile-First UI:** Responsive design built with **Tailwind CSS** for easy use on the go.
* **Automated Deployment:** Fully automated CI/CD pipeline using **GitHub Actions**.

## 🛠️ Tech Stack
* **Frontend:** HTML5, Alpine.js (Reactive State), Tailwind CSS.
* **Backend / Database:** Firebase Firestore (NoSQL).
* **Authentication:** Firebase Auth.
* **Hosting & DevOps:** Firebase Hosting, GitHub Actions (CI/CD).

## 🏃‍♂️ How to Run Locally
1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/shreyanshrp/BusManager.git](https://github.com/shreyanshrp/BusManager.git)
    ```
2.  **Open `index.html`:**
    You can run it directly using Live Server (VS Code) or `python -m http.server`.

## 🔒 Security
* Implements strict **Firestore Security Rules** to ensure users can only read/write their own data.
* Billing logic and write operations are validated client-side and secured via Firebase rules.

---
*Developed by Shreyansh Pampaniya*