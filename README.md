# Luvnexa

A full-stack social networking platform MVP for the web and Android. This repository contains the web app, backend API, and mobile app scaffold.

## Features implemented

- Secure user registration and login
- User profiles and avatars
- Follow/unfollow and discovery
- Post creation with media support
- Like and comment systems
- Messaging and notifications
- Admin dashboard and analytics summary
- Android app setup for future APK/Play Store release

## Project structure

- `web/` – React + Vite frontend
- `backend/` – Express + Prisma API
- `mobile/` – React Native / Expo app
- `docs/` – deployment and setup guides

## Quick start

```bash
npm install
cp .env.example .env
cp backend/.env.example backend/.env
cp web/.env.example web/.env
npm run dev
```

## Deployment notes

This repository includes the code and configuration for a free-tier deployment flow:

- Frontend on Vercel
- Backend/API on Render
- PostgreSQL on Supabase
- Media storage via Firebase or Cloudinary

You must provide your own external accounts and credentials for deployment. No secret keys are included in the repository.

## Important status

This repository is the implementation scaffold and deployment-ready codebase, but actual deployment requires:

- a GitHub repository connection to Vercel/Render
- a PostgreSQL database provider
- your own environment secrets in `.env` files
- optional payment for Android Play Store registration ($25 one-time)

No user data, passwords, or private keys are stored in this codebase.
