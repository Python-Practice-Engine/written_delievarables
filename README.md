#Python Practice Engine

###Summary
Python Practice Engine is a learning tool that is meant to teach students Python in an approachable and practical way.

###Instructions on how to run Python Practice Engine locally
1. Make sure you have `Node.JS` and `MySQL` downloaded on your computer
2. Navigate to the back-end folder
   `cd src/back-end`
3. In the root of the back-end folder create a file called `.env`
4. Paste the following in the `.env` file
```
REACT_APP_HOST=db-pythonlearning.c6yi2fa1chsl.ca-central-1.rds.amazonaws.com
REACT_APP_PORT=3306
REACT_APP_USER=admin
REACT_APP_PASSWORD=mcmaster1280
REACT_APP_DATABASE=pythonlearning
```
5. Run `npm install`
6. Run `npm install express`
7. Install `npm i create-react-app`
8. Run `npm start`
9. Navigate to the front-end folder
   cd `src/front-end`
10. Run `npm install`
11. Run `npm start`
12. The application should be running in `localhost:3000` in your browser

###SRS changes
[Updated SRS](https://github.com/Python-Practice-Engine/src/wiki/SRS/_compare/35f504d7d96cf90c4a3f16e474f959cf27529a05...a63dec604865aa9f25c723e4cf88d0e4a207716c?short_path=2a092c9#diff-2a092c918bf9f729e909e3c29a0c2b3cb01e7cda8f6f9e87d973db5dfcff1bd8)