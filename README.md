# Node.js OpenWhisk Webui - Query Console

The Webui demonstrates a simple, reusable Node.js web application based on the Express framework that interacts with OpenWhisk APIs and provides an interface to list and Invoke actions,Packages and API gateway routes. The app extensively uses JavaScript client library(npm package) for the OpenWhisk platform.

OpenWhisk is a serverless platform that lets developers quickly and easily build feature-rich apps that automatically trigger responses to events.

## Prerequisites
1. Bluemix account.
2. OpenWhisk CLI
3. Cloudfoundry or Bluemix CLI

## Run the app locally

- [Install Node.js][]
- Clone the repo
```
git clone https://github.com/VidyasagarMSC/openwhisk-nodejs-webui.git
```
- cd into the app directory
- Run `npm install` to install the app's dependencies
- Open manifest.yml file and provide a unique name,host.
- Create a newfile and save it as .env in the root of the folder.Add the below
  values to .env file and save

``` 
 OpenWhisk_HOST = "openwhisk.ng.bluemix.net" 
 OpenWhisk_AuthKey=" "

```
<br>For OpenWhisk auth key, follow the instructions by clicking "Download Open CLI" button on [this page](https://console.ng.bluemix.net/openwhisk/)
- Run `npm start` to start the app
- Access the running app in a browser at http://localhost:6007

[Install Node.js]: https://nodejs.org/en/download/
