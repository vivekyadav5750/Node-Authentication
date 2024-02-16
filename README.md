# Node.js Authentication Project

This project is a Node.js application that provides authentication functionality, including sign up, sign in, sign out, password reset, and Google login/signup.

## Live Site
Visit the live site [here](https://node-authentication-gpu4.onrender.com/user/signout)

## Features

- **Sign up with Email**: Users can create an account by providing their email and password.
- **Sign In**: Users can sign in with their email and password.
- **Sign Out**: Users can sign out of their accounts.
- **Reset Password**: Users can reset their passwords after signing in.
- **Encrypted Passwords**: Passwords stored in the database are encrypted for security.
- **Google Login/Signup**: Users can sign in or sign up using their Google accounts.[here](https://console.cloud.google.com/apis/credentials/oauthclient/536056079130-v11aanfp4imnsmf22pi2779hm1ouh25a.apps.googleusercontent.com?project=nodejs-authentication-414411)
- **Forgot Password**: Users can reset their passwords via email.
- **Password Strength Validation**: Notifications are displayed for unmatching passwords during sign up and incorrect passwords during sign in.
- **reCAPTCHA Integration**: Extra points for enabling reCAPTCHA on both sign up and log in pages. [here](https://www.google.com/recaptcha/admin/site/695485478/settings)

## Folder
  ```csharp
node-authentication/
│
├── config/                  # Configuration files
│   └── mongodb.js           # MongoDB configuration
│
├── src/                     # Source code
│   ├── controllers/         # Controller logic
│   ├── models/              # Database models
│   ├── routes/              # Route definitions
│   ├── views/               # EJS views
│   └── app.js               # Express application setup
│
├── public/                  # Static assets
│
├── package.json             # NPM package configuration
├── README.md                # Project README file
└── .gitignore               # Git ignore configuration
```

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/node-authentication.git
  
2. Navigate to the project directory:
   ```bash
   cd node-authentication
    ```
3. Install dependencies:
   ```bash
   npm install

4. Start the server:
   ```bash
   npm start
- `Open your web browser and visit http://localhost:3000 to access the application.`

## Dependencies

- Express.js
- MongoDB
- Passport.js
- bcrypt
- express-session
- express-ejs-layouts
- dotenv
- nodemailer

## Credits

This project was created by [Vivek Yadav](https://github.com/vivekyadav5750)

Feel free to contribute by submitting issues or pull requests!






  
