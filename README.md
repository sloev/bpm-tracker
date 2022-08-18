### Installation

```shell
git clone https://github.com/webmaxru/bpm-counter.git
cd bpm-counter
npm install

# Installing tools for Static Web Apps and Azure Functions
npm install -g @azure/static-web-apps-cli
npm install -g azure-functions-core-tools@3 --unsafe-perm true
```

### Starting local development server

```shell
# Instead of CRA's "npm start" we use SWA CLI's command to start everything at once
swa start http://localhost:3000 --run "npm start" --api-location ./api
```
