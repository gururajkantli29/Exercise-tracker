# FreeCodeCamp Exercise Tracker

## Overview
A REST API project for tracking exercises, part of Free Code Camp's curriculum.

## Project Structure
- `index.js` - Main Express server entry point
- `public/` - Static assets (CSS)
- `views/` - HTML templates

## Tech Stack
- Node.js 20
- Express.js 4.x
- CORS middleware
- dotenv for environment configuration

## Running the Application
The application runs on port 5000 via the "Start application" workflow using `npm start`.

## API Endpoints
- `POST /api/users` - Create a new user
- `POST /api/users/:_id/exercises` - Add exercises for a user
- `GET /api/users/:_id/logs?[from][&to][&limit]` - Get user's exercise log

## Environment Variables
- `PORT` - Server port (default: 5000)
