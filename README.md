# Render uptime ping

Public, secret-free helper repository. A scheduled GitHub Actions workflow
pings the Render health endpoint every 5 minutes so a free web service does
not spin down after 15 minutes of inactivity.

- Target: `https://iptv-cloud.onrender.com/healthz`
- No credentials, tokens, or private data are stored here.
- Disable the workflow or delete this repository if the service is moved to a
  paid plan or another host.
