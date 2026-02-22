# StudyMind AI - Vercel Deployment Guide

## Files in this folder:
- `index.html` - Main app (works on all phones)
- `api/ai.js` - Backend AI API route (keeps your key secret)
- `vercel.json` - Vercel config

## Steps to Deploy:

### Step 1 - Create GitHub Account
Go to github.com and sign up (free)

### Step 2 - Create New Repository
1. Click "New" button on GitHub
2. Name it: studymind-ai
3. Set to Public
4. Click "Create repository"

### Step 3 - Upload Files to GitHub
1. Click "uploading an existing file"
2. Upload ALL files from this folder:
   - index.html
   - vercel.json
   - api/ai.js (create api folder first)
3. Click "Commit changes"

### Step 4 - Deploy on Vercel
1. Go to vercel.com
2. Sign up with GitHub account
3. Click "New Project"
4. Select your studymind-ai repository
5. Click "Deploy"

### Step 5 - Add Your Groq API Key (IMPORTANT!)
1. In Vercel dashboard, go to your project
2. Click "Settings" tab
3. Click "Environment Variables"
4. Add:
   - Name: GROQ_API_KEY
   - Value: (paste your Groq API key here)
5. Click "Save"
6. Go to "Deployments" tab and click "Redeploy"

### Step 6 - Share with Everyone!
Your app will be live at:
   https://studymind-ai.vercel.app

Anyone can open it on iPhone or Android!

## To install as app on phone (no app store needed):
- iPhone: Open in Safari -> Share button -> "Add to Home Screen"
- Android: Open in Chrome -> 3 dots menu -> "Add to Home Screen"
