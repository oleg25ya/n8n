# n8n Railway Deploy

Deploy n8n automation platform to Railway using Docker.

## Usage

1. Fork this repository or upload to GitHub.
2. Connect to Railway (https://railway.app).
3. Add the following environment variables:
   - N8N_BASIC_AUTH_ACTIVE=true
   - N8N_BASIC_AUTH_USER=admin
   - N8N_BASIC_AUTH_PASSWORD=yourpassword
   - WEBHOOK_URL=https://your-subdomain.up.railway.app
   - N8N_HOST=0.0.0.0
   - N8N_PORT=5678

4. Click "Deploy".
