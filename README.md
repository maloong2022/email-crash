# Send Email By Mailgun, Node and React

![Send Email](img/app.jpg)

## You Will Learn

* React: Components, Props, Events, Hooks, Axios
* Node & Express: Web API, Http Body Parser

## Requires

1. nodejs
2. Axios
3. mailgun-js
4. react
5. express
6. dotenv
7. react-toastnotify

## Run Locally
### Clone repo

```bash
git clone git@github.com:maloong2022/send-email.git
cd send-email
```

### Replace .env file's Attribute

* create account on [Mailgun](http://mailgun.com)
* enter domain and api key in the env file

### Run Backend

```bash
cd send-email/backend
node server.js
```

### Run Frontend

```bash
cd send-email
npm install
npm start
```

### Test

* Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
* Enter email, subject and message and click send button
* Check your inbox

