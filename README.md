# GCONNECT - Real Time Chat Application 
GCONNECT is chat application built with the power of MERN Stack.

# Tech Stacks : ReactJs | Nodejs | Socket.io | MongoDb

# Register Page
![image](https://github.com/gautamkumar1/GCONNECT-APP/assets/91417015/a58fdab5-5775-456f-8baf-20a89c28b0e8)
# Login Page
![image](https://github.com/gautamkumar1/GCONNECT-APP/assets/91417015/9ef1f12f-1978-4bad-814d-9bd61bae332e)
# Select Profile picture - Avatars are dynamically generated from the Multi-Avatar API.
![image](https://github.com/gautamkumar1/GCONNECT-APP/assets/91417015/8e625fa3-b0a9-4fbf-884d-bd67dec4acba)
# Welcome Page 
![image](https://github.com/gautamkumar1/GCONNECT-APP/assets/91417015/3ac6e3e5-057f-4d59-a976-aa4fe3fc0d29)
# When user1 and user2 join the chat.As we can see user1 and user2 have joined the same room and they are communicating with each other through chat.
![image](https://github.com/gautamkumar1/GCONNECT-APP/assets/91417015/9cf7fa79-8755-4cbd-baa9-1452b6b82b88)



## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/gautamkumar1/GCONNECT-APP.git
cd GCONNECT-APP
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
