Paypal SDK Transaction Server Environment

This is the backend server for Devilfish Diving, a dive charter website. It provides endpoints for handling PayPal transactions and integrates with the Devilfish Diving client.
Here is the client repo. https://github.com/nate-paradiso/devilfish-diving-client

Getting Started
To get started with the Devilfish Diving server, follow these steps:

Installation
Clone this repository to your local machine:


git clone https://github.com/nate-paradiso/devilfish-diving-server.git
Navigate into the project directory:


cd devilfish-diving-server
Install dependencies using npm:

npm install
Configuration
Before running the server, you'll need to set up your environment variables. Create a .env file in the root directory of the project and add the following variables:

PAYPAL_CLIENT_ID: Your PayPal client ID.
PAYPAL_CLIENT_SECRET: Your PayPal client secret.

Running the Server
Start the server using the following command:

npm start
The server will be accessible at http://localhost:8888.

Testing PayPal Transactions
Important: This server is configured to work with the PayPal sandbox environment for testing purposes. Make sure to set SANDBOX_MODE to true in your .env file to use the sandbox environment.

Usage
Once the server is running, it will handle incoming requests from the Devilfish Diving client to initiate and capture PayPal transactions. Make sure the client is configured to send requests to the correct endpoint.

Contributing
Contributions to the Devilfish Diving server are welcome! If you'd like to contribute, please follow these guidelines:

