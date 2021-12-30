## node-stripe-app
Simple node application to buy items and pay using bank card through stripe api. This node.js app teaches you how to intergrate stripe payements:


# What is Stripe?
The Stripe API allows developers to access the functionality of Stripe. ... Stripe is a service that allows users to accept payments online, specifically developers. With the Stripe application, users can keep track of payments, search past payments, create recurring charges, and keep track of customers.

# Requirements
Node 8
Git
Code editor (VS Code)

# Common setup
Clone the repo and install the dependencies.

git clone https://github.com/KawemeKowa/node-stripe-app.git 

cd node-stripe-app

npm install

#Steps for read-only access

To start the express server, run the following

npm run start:dev
Open http://localhost:3000 and take a look around.

# Steps For Stripe
Go to the stripe dashboard and create an account https://stripe.com/
You will be provided with a secret key and a public key.

# Step 6: 
Create a .env file in the root and inject your credentials so it looks like this.

STRIPE_SECRET_KEY = 'your_secret_key'
STRIPE_PUBLIC_KEY = 'your_public_key'
#Step 7: To start the express server, run the following
node server.js
