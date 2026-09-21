# Sauna P8 🌈♨️ — Render-ready

Social multiplayer pixel-inspired web game built with Node.js, Express and Socket.IO.

## Included
- Nickname login and character customization
- Shared room code
- Realtime multiplayer via Socket.IO
- City zones and Sauna P8 rooms
- Chat bubbles above avatars
- Friendly emotes/interactions
- Mobile controls
- `/health` endpoint for Render
- Binds to `0.0.0.0` and uses Render's `PORT`
- No application-level player cap; actual capacity depends on the server/device

## Deploy to Render

### Option A — GitHub + Render Blueprint
1. Upload the contents of this ZIP to a GitHub repository.
2. In Render, choose **New → Blueprint**.
3. Select that GitHub repository.
4. Render reads `render.yaml` automatically.
5. Confirm the service `sauna-p8`.
6. Wait for **Live**, then tap **Open**.

### Option B — Web Service
Use:
- Runtime: **Node**
- Build Command: `npm install`
- Start Command: `npm start`
- Health Check Path: `/health`

Do not use a Static Site: this game needs a Node server and Socket.IO.

## Local
```bash
npm install
npm start
```
Then open `http://localhost:10000`.

## Safety/design
Interactions are friendly/non-explicit. The dark room is a social room; beds/furniture are decorative/emote surfaces. No drug-sale marketplace or sexual activity system is included.
