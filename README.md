**InstaCloneX Read Me**

**Introduction:**
InstaCloneX is a web application that emulates the core features of Instagram, allowing users to sign up, log in, post photos, follow other users, like and comment on posts, and explore content from other users. It is built using HTML, CSS, JavaScript, and the MERN (MongoDB, Express.js, React.js, Node.js) stack.

**Features:**
1. **User Authentication:** Users can sign up with a unique username and password, and log in securely to access their account.
2. **Posting Photos:** Users can upload photos with captions to share with their followers and the wider community.
3. **Following Users:** Users can follow other users to see their posts in their feed.
4. **Liking and Commenting:** Users can engage with posts by liking them and leaving comments.
5. **Explore Page:** Users can explore content from other users even if they are not following them.
6. **Responsive Design:** The application is designed to be responsive, ensuring a seamless experience across various devices and screen sizes.

**Technologies Used:**
- **Frontend:** HTML, CSS, JavaScript, React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

**Setup Instructions:**
1. **Clone the Repository:** Clone the InstaCloneX repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/InstaCloneX.git
   ```
2. **Install Dependencies:** Navigate to the project directory and install the dependencies for both the frontend and backend:
   ```
   cd InstaCloneX
   cd frontend
   npm install
   cd ../backend
   npm install
   ```
3. **Set Up MongoDB:** Install MongoDB on your system if you haven't already and make sure it's running.
4. **Configure Environment Variables:** Create a `.env` file in the `backend` directory and set the following environment variables:
   ```
   PORT=3001
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```
5. **Start the Application:** In separate terminal windows, start the frontend and backend servers:
   ```
   cd InstaCloneX/frontend
   npm start
   ```
   ```
   cd InstaCloneX/backend
   npm start
   ```
6. **Access the Application:** Open your web browser and navigate to `http://localhost:3000` to access InstaCloneX.

**Contributing:**
Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

**License:**
This project is licensed under the MIT License. See the `LICENSE` file for more information.

**Acknowledgements:**
- This project was inspired by the functionalities of Instagram.
- Special thanks to the developers of the MERN stack for providing the tools and frameworks necessary to build this application.
