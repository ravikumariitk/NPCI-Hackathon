# NPCI Hackathon
## Anonymous Digital Payment System for Privacy-Preserving Transactions

This project contains two separate servers:
- **NPCI-server**
- **Payment-Server**

Each server needs to be started individually using `node server.js`.

## Table of Contents
- [NPCI Hackathon](#npci-hackathon)
  - [Anonymous Digital Payment System for Privacy-Preserving Transactions](#anonymous-digital-payment-system-for-privacy-preserving-transactions)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Servers](#running-the-servers)
  - [Technologies Used](#technologies-used)

## Prerequisites
Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v12 or later)
- npm (v6 or later)

## Installation

1. Clone the repository to your local machine.

```bash
git clone <repository-url>
```

2. Navigate to the directories of the individual servers (NPCI-server and Payment-Server) and install dependencies.
```bash

# Navigate to NPCI-server
cd NPCI-server
npm install

# Navigate to Payment-Server
cd Payment-Server
npm install

```
## Running the Servers
After installing the necessary dependencies, follow these steps to run the servers.

1. Starting NPCI-server
Navigate to the NPCI-server directory.
Start the server using Node.js:
```bash
cd NPCI-server
node server.js
```
The NPCI-server should now be running on the specified port (default is 80).

2. Starting Payment-Server
Navigate to the Payment-Server directory.
Start the server using Node.js:
```bash
cd Payment-Server
node server.js
```
The Payment-Server should now be running on the specified port (default is 8000).
## Technologies Used
Node.js: Server-side JavaScript runtime.
Express.js: Web application framework.
EJS: Templating engine for rendering views.
