# Zoom Meeting Q&A Report Getter

This is a sample app for a specific Zoom use case.

On the meeting.ended webhook event, get the meeting Q&A report and show the host's email address.

scopes:
- user:read:admin
- report:read:admin

events:
- meeting.ended

### Setup

First install nodejs 18 LTS on your machine.


```bash
# clone the repo
git clone https://github.com/Will4950/zoom-QA-report.git

# Navigate into the cloned project directory
cd zoom-QA-report

# edit .env
nano .env

# Install required dependencies
npm install 

# Start the app
npm start

```

App is listening on localhost:3000
