# Ziroh Labs Google SSO Sign In

This Repository consists of the code and installation procedure for the ziroh labs google sso project.

## Table of Contents

- [Ziroh Labs Google SSO Sign In](#ziroh-labs-google-sso-sign-in)
  - [Table of Contents](#table-of-contents)
  - [Install and Use](#install-and-use)
  - [Configuration](#configuration)
  - [Note](#note)

## Install and Use

Start by cloning this repository

then use [npm](https://www.npmjs.com/) to

```
# Install dependencies
$ npm i
# Fill .env file as given in the further procedures
# ...
# start development
$ npm start
# ...
```

## Configuration

Configure the keys with your client id in `.env` file.

```
REACT_APP_CLIENT_ID=<Enter you client id here as a string>
```

## Note

- The above mentioned client id is the one that is generated in google cloud console in the Auth0 credentials. For further assitance, use this [video](https://www.youtube.com/watch?v=TKnnrGU9MFw).
- While creating the Auth0 credentials, please add all the gmail Ids which you use for testing login in the test user box.
