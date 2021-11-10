# ZD-Debugger

Welcome to the ZD Debugger! This is a project that the Developer Advocacy team started during the first ever community day! 

The goal of the project is to provide you a simple web application to assist with debugging Zendesk App issues you may encounter during development. 

This app provides: 

* A GET/POST/DELETE endpoint for you to test calling external services. This is helpful for debugging secure request issues as you can then see the output after the request leaves the Zendesk Proxy.

* A small JWT server for testing authorized requests.

The techstack:

* ExpressJS
* Prisma(ORM)
* SQLite

We will continue to add more features to this, so stay tuned!

# Getting Started

### Working with the repository locally 

1. Clone the repository to your local
2. `npm install` to install all of the dependencies
3. `npx prisma migrate dev --name init` to set up the SQLite database
4. `npm run dev` to start up the server

### Work with the app hosted on [Glitch](https://glitch.com)
1. Click this [link]() To make your own copy of the project
2. Click "Tools" then "Terminal" and use the command `npx prisma migrate dev --name init` to set up the SQLite database