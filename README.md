# FF Panel Selling Store

Ready for deployment on Railway.

## Structure
- public/index.html - Customer store
- public/admin.html - Admin dashboard
- server.js - Express server configured for Railway ($PORT)
- Rules.md - Firebase Realtime Database rules

## Configuration
Replace the placeholder Firebase configuration in public/index.html and public/admin.html with your Firebase project credentials.

## Deploying to Railway
1. Upload these files to a GitHub repository.
2. In Railway (railway.com), select "New Project" -> "Deploy from GitHub repo".
3. Select your repository. Railway will detect Node.js and run it automatically!
