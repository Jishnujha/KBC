# KBC Live Audience Poll

## Deploy to Render

1. Put these files in a GitHub repository and push them.
2. In Render, create a **Web Service** from that repository.
3. Use build command `npm install` and start command `npm start`.
4. After deployment, open the Render URL (not the local HTML file). The quiz uses that same URL for its QR codes and live Socket.IO connection.

When the host uses the Audience Poll lifeline, a QR code opens a unique 30-second voting room. Votes are in memory, so use one Render instance; restarting the service clears current polls.
