# SentiChat
A real-time chat application with sentiment analysis. Sentiment analysis is used to detect the mood of a person based on the phrases and words used in their message.

## Technologies

1. **Next.js** - Framework for building SSR React applications.
2. **React** - A Javascript DOM rendering framework using component based architecture.
3. **Sentiment** - A module that uses AFINN-165 wordlist to perform analysis on text.
4. **Pusher** - Technology for building apps with realtime needs (eg. push notifications).

## Prerequisites

1. **Node & npm**
2. **Pusher Application** - [Pusher Dashboard](https://dashboard.pusher.com/)

## Setup

1. **Clone repo**
2. **Install dependencies** from new directory of the repo.

```sh
npm install
```

3. **Create a .env file with your pusher creds** in the root  of the directory.

```ini

PUSHER_APP_ID=YOUR_APP_ID
PUSHER_APP_KEY=YOUR_APP_KEY
PUSHER_APP_SECRET=YOUR_APP_SECRET
PUSHER_APP_CLUSTER=YOUR_APP_CLUSTER
```

4. **Start the app on port 3000**

```sh
npm run dev
```


# pusher-nextjs
