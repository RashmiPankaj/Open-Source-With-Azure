# Deploy Node.js app in Azure App Service Linux
---
Azure Web Apps provides a highly scalable, self-patching web hosting service. This quickstart shows how to deploy a Node.js app to Azure Web Apps on Linux OS. You create the web app using the Azure Portal, and you use Git to deploy sample Node.js code to the web app.

## Prerequisites

To complete this quickstart:

* [Install Git](https://git-scm.com/)
* [Install Node.js and NPM](https://nodejs.org/)

In a terminal window, run the following command to clone the sample app repository to your local machine.

```bash
git clone https://github.com/Azure-Samples/nodejs-docs-hello-world
```

You use this terminal window to run all the commands in this quickstart.

Change to the directory that contains the sample code.

```bash
cd nodejs-docs-hello-world
```

## Run the app locally

Run the application locally by opening a terminal window and using the `npm start` script to launch the built in Node.js HTTP server.

```bash
npm start
```

Open a web browser, and navigate to the sample app at `http://localhost:1337`.

You see the **Hello World** message from the sample app displayed in the page.

In your terminal window, press **Ctrl+C** to exit the web server.