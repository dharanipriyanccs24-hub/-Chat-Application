# Deployment Instructions for Render

## Step 1: Create a Render Account
- Go to [Render.com](https://render.com) and sign up for an account if you haven't already.

## Step 2: New Web Service
- After logging in, click on "New" and select "Web Service".

## Step 3: Connect Your Repository
- Select your GitHub repository from the list. Render will automatically detect your application type.

## Step 4: Configure Settings
- Configure the build command, environment variables, and a few other settings.
  - **Build Command:** `npm install`
  - **Start Command:** `npm start`

## Step 5: Deploy
- Click on the "Create Web Service" button to deploy your application.

## Step 6: Access Your Application
- Once deployed, you can access your application through the URL provided by Render.


# Setup Instructions

## Prerequisites
- Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

## Step 1: Clone the Repository
```bash
# Clone the repository
$ git clone https://github.com/your_username/Chat-Application.git
```

## Step 2: Navigate to the Project Folder
```bash
$ cd Chat-Application
```

## Step 3: Install Dependencies
```bash
$ npm install
```

## Step 4: Run the Application
```bash
$ npm start
```

## Step 5: Access Application
- Open your browser and go to `http://localhost:3000` to access the application.