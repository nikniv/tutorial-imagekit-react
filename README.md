# ImageKit React SDK Tutorial

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Installation

### Setup the frontend app

Install packages:

```bash
npm install
```

Run the app:

```bash
npm start
```
To run the upload component you also will have set up a backend server. See below.

## Setting the enviroment variable

Create a .env file by renaming the `sample.env` file in the project root directory.

Fill in the required parameters according to your ImageKit account credentials.

## Setting up the sample backend server

There is a sample server present in the `/server` directory.

It takes the `private key` from .env file, so create a .env file by renaming the sample.env in `/server` and paste your authentication credentials into it.

Install packages:

```bash
cd server
npm install
```
To run this server:

```
npm run server
```
