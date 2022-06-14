# 8200-node-app
Node.js basic application useful for demos and examples

&nbsp;

## General Information

The application show a basic web page
![Welcome-Page](https://github.com/bynet-devops-training/8200-node-app/blob/main/images/Image1.png?raw=true)
The application have a basic function to determine if a number is prime or not
![Welcome-Page](https://github.com/bynet-devops-training/8200-node-app/blob/main/images/Image2.png?raw=true)

The folder “spec” contains the application tests which are run using the jasmine-node module
![Welcome-Page](https://github.com/bynet-devops-training/8200-node-app/blob/main/images/Image3.png?raw=true)

The application Dockerfile is very simple, use node as a base image, copy the application files, download the application dependencies and run the application in the port 3000
![Welcome-Page](https://github.com/bynet-devops-training/blob/main/images/Image4.png?raw=true)

## Build

Install Dependencies:
```
npm install
```

Run Tests:
```
npm test
```

create zip file
```
npm run build
```

Start the Application:
```
npm start
```
