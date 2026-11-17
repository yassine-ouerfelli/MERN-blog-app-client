# MERN Blog — Client

React front end of a full-stack blogging platform. Users can sign up, confirm their email, log in (email/password or Google), write and edit posts, and save posts to their favourites.

**Back end:** [MERN-blog-app-server](https://github.com/yassine-ouerfelli/MERN-blog-app-server)

## Features
- Registration with email confirmation
- Login with email/password or Google sign-in
- Forgot-password flow with a reset link sent by email
- Create, read and edit blog posts
- Save posts to a personal favourites list
- Global user state with Redux

## Tech stack
React · Redux · React Router · Axios · Material UI · Tailwind CSS · Bootstrap

## Getting started
```bash
git clone https://github.com/yassine-ouerfelli/MERN-blog-app-client.git
cd MERN-blog-app-client
npm install
```
Create a `.env` file with your Google OAuth client ID:
```
REACT_APP_GOOGLE_ID=your-google-client-id
```
Then start the dev server (the API must be running too):
```bash
npm start
```
The app runs on http://localhost:3000.
