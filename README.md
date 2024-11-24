
# Sukoon  

Sukoon is a comprehensive mental health application built using the MERN stack, designed to support users in managing their mental well-being. With an emphasis on privacy and personalization, Sukoon offers a range of features that empower users to track their mental health, seek advice, and connect with others in a secure and meaningful way.

## Key Features  

### Cookie Session Login  
- Provides secure user authentication using cookie sessions to maintain login states across sessions.  
- Unauthorized users are restricted from accessing certain pages, ensuring data privacy and protection.

### Mood Tracker  
- Enables users to log and monitor their daily mood.  
- Creates a historical record to track mental health trends over time.  

### AI Therapist  
- Chat with an AI-powered therapist to discuss your emotions and receive instant, supportive responses.  
- Powered by the Gemini API for advanced natural language processing.  

### Mood Quiz  
- Take a personalized quiz to better understand your current mood.  
- Responses are analyzed using the Gemini API, generating a tailored feedback report with insights into your emotional state.  

### Anonymous Sharing  
- Share your thoughts and feelings anonymously with the community.  
- Fosters an environment of free expression without revealing personal identities.

### CRUD Functionality  
- Full Create, Read, Update, and Delete operations for user profiles and content management.  
- Enables seamless handling of user data and shared posts.

## Technologies Used  

- **MongoDB**: Database for storing user data, mood logs, and anonymous posts.  
- **Express.js**: Backend framework to manage API requests and server-side operations.  
- **React**: Frontend library for building a responsive and dynamic user interface.  
- **Node.js**: Runtime environment to execute JavaScript on the server side.  
- **HTML, CSS, JavaScript**: Core technologies for creating an engaging frontend experience.  
- **RapidAPI**: Integrated to utilize the Gemini API for AI-based features.  
- **Gemini API**: Powers the natural language processing capabilities of the AI therapist and mood quiz feedback system.

## Why Sukoon?  

Sukoon offers a safe space for users to prioritize their mental health with tools that combine cutting-edge technology and thoughtful design. From tracking your daily mood to receiving AI-driven therapeutic advice, Sukoon ensures that mental well-being is accessible, secure, and supportive for everyone.

---
### Getting Started  
To run this project locally, follow the steps below:

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/sukoon.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd sukoon
   ```

3. Install dependencies for the server and client:  
   ```bash
   npm install
   cd client && npm install
   ```

4. Create a `.env` file in the root directory and configure the following variables:  
   - `MONGO_URI`  
   - `SESSION_SECRET`  
   - `GEMINI_API_KEY`  

5. Start the development server:  
   ```bash
   npm run dev
   ```

6. Access the application in your browser at `http://localhost:3000`.

---

### Contributing  
Contributions are welcome! Please fork the repository and submit a pull request for any changes.  

---

### License  
This project is licensed under the [MIT License](LICENSE).  

---
**Made with ❤️ for mental health.**
