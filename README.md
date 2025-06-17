# Subdomain Deployer

A Next.js app to let users create subdomains that deploy the Interstellar repo to Vercel.

## Setup

1. **Clone this repo**
2. **Install dependencies:**
   npm install
3. **Set up environment variables:**
   - Copy `.env.example` to `.env.local` and fill in your Vercel token (and team ID if needed).
4. **Deploy to Vercel:**
   - Push to GitHub and import the repo in Vercel.
   - Set the environment variables in the Vercel dashboard.
   - Make sure your domain (e.g., `sub-gules.vercel.app`) is added to your Vercel project
