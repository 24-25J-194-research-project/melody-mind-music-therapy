# Melody Mind - An Interactive Music Therapy Solution for Dementia Patients
## Student No - IT21244698

Melody Mind is a digital solution designed to enhance music therapy sessions for dementia patients, helping mitigate symptoms such as depression, anxiety, and mood changes. Traditional music therapy provides significant benefits, but active participation can amplify its impact. This project focuses on creating an interactive music therapy system that keeps patients engaged and attentive during sessions.



This repository contains the source code, model implementations, and documentation necessary to develop and deploy the interactive therapy system. It aims to make music therapy more engaging and impactful for dementia patients.


## The solution includes:

- A therapy session player to deliver tailored music therapy.
- A clap detection system powered by a CNN model to recognize patient interactions (claps), fostering active engagement.

## Technologies:
- Frontend: Built with Flutter for a seamless and user-friendly experience.
- Backend: Python with a Convolutional Neural Network (CNN) for clap detection.


## Run Locally

Clone the project

```bash
  git clone https://github.com/24-25J-194-research-project/melody-mind-music-therapy.git
```

Go to the project directory

```bash
  cd melody mind music therapy
```

Install dependencies

```bash
  npm install
```

Database migrations
```bash
  npx knex migrate:latest
```

Create a .env file in the root directory and add the following environment variables:
```bash
  PORT=
  NODE_ENV=
  NODE_PROD=
  DB_HOST=
  DB_PORT=
  DB_USER=
  DB_PASSWORD=
  DB_NAME=
```
Start the server

```bash
  npm run dev
```


