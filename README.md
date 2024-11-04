
# AI Chat Demo App

This is a demo application showcasing AI chat functionality.

## Installation

To set up the app, first install the required dependencies:

```bash
pnpm install  # or use npm install
```

## Environment Variables

Before starting the app, create a `.env.local` file in the root directory with the following environment variables for local:

```env
NEXT_PUBLIC_GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_SECRET=
OPENAI_API_KEY=
```

Fill in the appropriate values for each variable based on your setup.

## Setup Data Directories

Ensure that you have the following directory structure within a `data` folder to store chat and user information:

```
data/
├── chats/
└── users/
```

- `chats/`: This directory will store chat data.
- `users/`: This directory will store user data.

## Run Locally

Once the setup is complete, start the app locally:

```bash
pnpm start  # or use npm start
```

## Usage

This app provides a demo environment for AI-powered chat interactions. Access it in your local environment after starting.

---

Enjoy using the AI Chat Demo App!