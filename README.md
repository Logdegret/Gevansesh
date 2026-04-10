# Geven — Sesh with Excellence

A Gevan Sesh idea generator powered by Gemini AI.

## What is a Gevan Sesh?

Sneakily borrowing and hiding Gevan's personal items without him noticing — harmless, funny, and creative. Nothing is ever damaged or permanently taken. The goal is maximum confusion and comedy.

## Setup

1. Open `index.html` in the `<script>` block and find this line near the top:

   ```js
   const API_KEY = 'your_gemini_api_key_here';
   ```

2. Replace the value with your own Gemini API key.
   Get a free key at: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

3. Open `index.html` directly in a browser — no server needed.

## Deploying to Vercel

1. Push this repo to GitHub.
2. Import the repo in [Vercel](https://vercel.com).
3. Deploy — Vercel will serve the static `index.html` automatically.

## Security Note

> **The API key is embedded directly in `index.html` and will be visible to anyone who views the page source.**
>
> This project is intended for local or school use only. Do not deploy publicly with a key you want to keep private. If you need to protect the key, you'd need a backend proxy (e.g. a Vercel serverless function) that holds the key server-side and forwards requests to Gemini.

## Usage

1. Pick a **target category** (Backpack, Supplies, Snacks, Seat, or Anything).
2. Set the **excellence level** with the slider (Casual → Intermediate → Legendary).
3. Hit **Generate Sesh Ideas**.
4. Receive 3 AI-crafted sesh ideas with difficulty, confusion, and excellence ratings.
