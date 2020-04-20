# open-tok-api
Open tok api for video streaming and many more 

# What is Open Tok API?
Opentok is a leading WebRTC platform for embedding live video, voice & messaging into your web & mobile apps. It includes client libraries for web, ios and android.

There are two main components of this API:
```
-The Client Side - javascript
-The Server Side - php or similar languages
```
To get started with opentok API register for developer account and get API credentials for our laravel application. Below is the link to signup for opentok:

Next, we have to create a new laravel project to get started with. If you do not know how to setup laravel project read installation instructions for Settting Laravel Framework.

## Add .env configurations

Let's create two new constants for our open tok api in .env file as shown below:

```
OPENTOK_API_KEY=
OPENTOK_API_SECRET=​
```

Next, we have to install opentok php library through composer. Go to your project root folder and run following command in your terminal window:

```
composer require opentok/opentok​
```

more at https://www.learn2torials.com/a/how-to-setup-opentok-api-with-laravel
