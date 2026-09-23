CARELOOP — Netlify frontend + Render backend

This package is configured for Netlify. The static frontend is served from /public and sends API/OCR requests to:
https://careloop-ai-b4nu.onrender.com/api

Deploy options:
1. Create a Netlify site from the GitHub repository containing this project.
2. Build command: leave blank.
3. Publish directory: public
4. Or use netlify.toml, which already sets publish = "public".

Important: the Node/Express server is NOT hosted by Netlify. Keep the existing Render Web Service running for OCR, tasks and assistant API functionality.

Use fictional/demo medical records only. OCR is an extraction aid and must be human-verified.
