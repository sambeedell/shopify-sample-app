# shopify-sample-app

Build: https://shopify.dev/tutorials/build-a-shopify-app-with-node-and-react/

Deploy: https://www.shopify.co.uk/partners/blog/deploy-website

Install: https://www.shopify.co.uk/partners/blog/17056443-how-to-generate-a-shopify-api-token 

# Progress

I have built a sample shopify app by following the first link. It has been successfully authenticated and tested using a development store on my partners.shopify account. This was achieved using ngrok to create a secure tunnel to my localhost. I am currently trying to remove the dependancy on ngrok by deploying the sample app code to a server. The second link covers deployment methods but I have been able to deploy this github repository using Vercel: https://vercel.com/sambeedell/shopify-sample-app 

The issue I am facing now is that the deplyed version of the app does not start on the server.js file but instead directly opens index.js
Furthermore, I have a hidden .env file that contains the app credentials that need to be hosted privately?

To install app on any given store I have created a placeholder website: https://install.storelab.app 
This website takes a store name and redirects to the myshopify.com domain to allow credentials to be shared. 



