# online-complaint-system
**🏢 ResolveMate:**
Online Complaint Registration and Management System
ResolveMate is a web application designed to help users easily register, track, and resolve complaints. It connects customers with agents, offering a simple and user-friendly interface for both parties to interact and resolve issues efficiently.

******************************

🚀 Features
👥 Customers/Users:

📝 Register and Login: Users can create accounts to submit and track complaints.

🖊️ Submit Complaints: Customers can enter complaint details such as issue type, description, and location.

📊 Track Complaints: Users can track the status of their complaints in real-time.

💬 Chat with Agents: Users can directly communicate with agents through a chat window for updates and clarifications.
************
👨‍💻 Agents:

📝 Register and Login: Agents can create accounts to view and manage assigned complaints.

🔄 Update Complaint Status: Agents can update the status of complaints (e.g., "In Progress," "Resolved").

💬 Chat with Customers: Agents can chat with customers to resolve complaints.
***********
👑 Admin:


🔑 Admin Login:
Admins can log in to manage the platform.


📝 Assign Complaints: 
Admins can assign complaints to agents.


👀 Monitor Complaints:
Admins can track the status of complaints and ensure timely resolution.


👥 Manage Users & Agents:
Admins can add, update, or delete user and agent accounts.


🛠️ Manage Platform:
Admins can manage the overall platform policies and configurations.

***********

🛠️ Tech Stack


Frontend: React.js, Material UI, Axios


Backend: Node.js, Express.js, MongoDB


Database: MongoDB (using Mongoose for object modeling)


Authentication: JWT (JSON Web Token)


***********

👨‍💻 Team Members
Name
Role
*****
Team Lead - Alluri Partha Saradhi Reddy
*****
Member - BHARGAVA REDDY RAMIREDDY


## 🧠 Core Requirements

| Tool                          | Purpose                                                  | Windows Installation                                                                                                   | Kali / Linux Installation                                                                                                 |
| ----------------------------- | --------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Node.js & npm**            | Runs backend (JS runtime) and manages packages.          | [Download Node.js](https://nodejs.org/en/download/) → install and verify with:<br>`node -v` and `npm -v`              | `sudo apt update && sudo apt install -y nodejs npm`                                                                       |
| **Express.js**               | Web-server framework for Node.js. Handles routes & APIs. | Open CMD → `npm install express`                                                                                       | Open Terminal → `npm install express`                                                                                     |
| **MongoDB Community Server** | NoSQL database for storing users & complaints.           | [Download MongoDB](https://www.mongodb.com/try/download/community)<br>After install → service starts automatically. | `wget -qO - https://www.mongodb.org/static/pgp/server-6.0.asc \| sudo apt-key add -`<br>`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/debian bullseye/mongodb-org/6.0 main" \| sudo tee /etc/apt/sources.list.d/mongodb-org-6.0.list`<br>`sudo apt update && sudo apt install -y mongodb-org`<br>`sudo systemctl start mongod && sudo systemctl enable mongod` |
| **React.js**                 | Builds the frontend (UI).                                | In CMD: `npx create-react-app frontend`                                                                                | In Terminal: `npx create-react-app frontend`                                                                              |
| **Git**                      | Version control / clone repository.                      | [Download Git](https://git-scm.com/downloads)                                                                         | `sudo apt install git -y`                                                                                                 |
| **Code Editor**              | Development environment (VS Code recommended).           | [Download VS Code](https://code.visualstudio.com/download)                                                            | `sudo snap install code --classic`                                                                                        |

***************
📂 How to Run Locally



**Execute the following command to clone the repository:**



git clone:  
       
    git clone https://github.com/saradhi818/online-complaint-system.git

Install Dependencies:

• Navigate into the cloned repository directory:
            
    cd online-complaint-system
• Install the required dependencies by running the following commands:run commends one by one 

    cd frontend

    sudo apt-get install npm

    cd ..
    
    cd backend

     sudo apt-get install npm

**Start the Development Server:**

• To start the development server, execute the following command:run commends one by one 
      
    npm start

    cd..

    cd frontend

    npm start

    
• The online complaint registration and management app will be accessible at 

    http://localhost:3000


**Demo**

     https://drive.google.com/file/d/1zbKIZRzJtSWCwu78moZDaI1xIMyzzsTC/view?usp=drive_link


The user interface of the application looks
Landing Page


![Landing Page](https://github.com/user-attachments/assets/b3302c51-bbf9-42dd-9d7f-0c1ee620e9fd)


Login Page




![Login Page](https://github.com/user-attachments/assets/e60851d4-673b-41da-9c41-41617b91aa63)

Registration Page




![Registration Page](https://github.com/user-attachments/assets/80b15933-bb45-4298-9f85-d91eaa121f3f)

Common Dashboard For Complaint


![Common Dashboard For Complaint](https://github.com/user-attachments/assets/65744e6d-0889-477e-8fdb-9cbe6b776ec7)



Admin Dashboard


![Admin Dashboard](https://github.com/user-attachments/assets/04bd80c4-0199-4de8-bfe4-cc2a3c6a37fd)



Agent Dashboard 





![Agent Dashboard](https://github.com/user-attachments/assets/58be9201-3217-44e1-92d2-758316c8a0ca)















