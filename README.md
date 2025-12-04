# IntervYou

IntervYou is an advanced AI-powered interview platform designed to streamline the recruitment process. It bridges the gap between students and recruiters by offering a comprehensive ecosystem for document verification, interview scheduling, and AI-proctored testing with emotion analysis.

## 🚀 Key Features

### 👨‍💼 Admin Panel
The Admin Dashboard is the command center of the platform, allowing administrators to:
-   **Verify Documents**: Review and approve/reject documents uploaded by students to ensure eligibility.
-   **Manage Bookings**: Oversee interview schedules and approve/reject booking requests.
-   **Review Results**: Access detailed test submissions and finalize results.
-   **User Management**: Maintain the integrity of the platform by managing user access.

### 👨‍🎓 Student Workflow
Students have a structured path to success:
1.  **Document Upload**: Students must upload necessary documents (e.g., resumes, certificates) to prove eligibility.
2.  **Verification**: Once documents are approved by the Admin, students gain access to schedule tests.
3.  **Interview Scheduling**: Students can book interview slots based on their availability and test topics.
4.  **AI-Proctored Tests**: Take secure, real-time proctored exams.

### 🧠 AI Proctoring & Emotion Analysis
Our state-of-the-art proctoring system ensures integrity and provides deep insights:
-   **Real-time Emotion Detection**: The system captures and analyzes student expressions during the test to gauge confidence, stress, and focus.
-   **Detailed Reports**: After the test, students receive an **Emotion-Based Feedback Report** generated from their expressions and answers, offering unique insights into their performance beyond just scores.
-   **Secure Testing**: Monitoring for tab switching and other suspicious activities.

## 📸 Screenshots

### Landing Page
![Landing Page](screenshots/landing_page.png)

### Login Page
![Login Page](screenshots/login_page.png)

### Register Page
![Register Page](screenshots/register_page.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)

*(Note: Admin Dashboard and Emotion Report screenshots can be added here)*

## 🛠️ Tech Stack

-   **Frontend**: React.js, Vite, TailwindCSS, Bootstrap
-   **Backend**: Node.js, Express.js
-   **Database**: MongoDB
-   **AI/ML**: Face-api.js (for emotion detection), TensorFlow.js
-   **Real-time**: Socket.io

## 🏁 Getting Started

### Prerequisites
-   Node.js
-   MongoDB

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/neeraj1978/Intervyou.git
    cd Intervyou
    ```

2.  **Install Dependencies**:
    ```bash
    # Install backend dependencies
    npm install

    # Install frontend dependencies
    npm run client:install
    ```

3.  **Environment Setup**:
    -   Create a `.env` file in the root directory.
    -   Add your MongoDB URI and other configs:
        ```env
        MONGODB_URI=your_mongodb_connection_string
        PORT=5001
        JWT_SECRET=your_secret_key
        ```

### Running the Application

1.  **Start the Development Server**:
    ```bash
    npm run dev
    ```
    This command concurrently starts both the backend (port 5001) and frontend (port 5173).

2.  **Access the App**:
    -   Frontend: [http://localhost:5173](http://localhost:5173)
    -   Backend: [http://localhost:5001](http://localhost:5001)

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
