AI-Powered Talent Scouting System for Youth Affairs & Sports
Overview
The AI-Powered Talent Scouting System is an innovative platform that leverages Artificial Intelligence to identify and scout athletic talent. Designed using the MERN stack (MongoDB, Express.js, React.js, and Node.js), this system analyzes videos and data to provide fair, automated, and insightful assessments of athletes' performance, helping identify potential talent across rural and underserved areas.

Key Features
Automated Talent Identification: Analyze athlete performance from uploaded videos using AI models.
Fair AI-Based Assessments: Ensure unbiased and objective evaluations through AI algorithms.
Performance Analytics: Provide detailed statistics and insights on individual and comparative performance.
Inclusion & Accessibility: Focus on identifying talent from rural and underserved communities.
Scalable Recruitment Processes: Streamline talent scouting for efficient and inclusive recruitment.
Tech Stack
Frontend: React.js (UI/UX)
Backend: Node.js and Express.js
Database: MongoDB
AI/ML Models: Integrated for video and performance data analysis
Cloud Services: For video storage, processing, and model deployment (e.g., AWS, Azure, or Google Cloud)
Installation
Follow these steps to set up the project locally:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ai-talent-scouting.git
cd ai-talent-scouting
Install dependencies:

Navigate to the backend directory:
bash
Copy code
cd backend
npm install
Navigate to the frontend directory:
bash
Copy code
cd frontend
npm install
Set up environment variables:

Create a .env file in the backend directory and add:
env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUD_API_KEY=your_cloud_service_api_key
CLOUD_SECRET=your_cloud_service_secret
Run the application:

Start the backend server:
bash
Copy code
cd backend
npm start
Start the frontend server:
bash
Copy code
cd frontend
npm start
Access the application: Open your browser and navigate to http://localhost:3000.

Usage
Athlete Registration: Athletes can create profiles and upload videos of their performances.
AI Assessment: The system processes uploaded videos and provides objective performance analysis.
Scouting Dashboard: Recruiters can access a dashboard with rankings, analytics, and recommendations.
Project Structure
plaintext
Copy code
.
├── backend/          # Node.js and Express.js API
├── frontend/         # React.js application
├── models/           # MongoDB schemas
├── controllers/      # Business logic for backend routes
├── routes/           # API routes
├── utils/            # Helper functions and utilities
└── README.md         # Project documentation
Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-name
Commit changes:
bash
Copy code
git commit -m "Add your message here"
Push to the branch:
bash
Copy code
git push origin feature-name
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.
(https://github.com/user-attachments/assets/33b68487-0bc6-4f89-b640-b857c26abbfd)
Contact
For any inquiries or feedback, please contact:

Name: surbhi
Email: 22bcs16290@cuchd.in


