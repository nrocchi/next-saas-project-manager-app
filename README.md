# Next Saas Project Manager Application

Next.js application for Saas Project Manager using Next.js 14, Server Actions, React, Tailwind, Unsplash, Stripe, Prisma & MySQL.

## Features

- Organizations & Workspaces
- Boards creation, rename, delete and limit for every organization
- Projects creation, rename, delete, drag & drop reorder and copy
- Tasks creation, rename, delete, drag & drop reorder and copy
- Stripe subscription for each organization to unlock unlimited boards
- Stripe webhooks
- Landing page
- Unsplash API for random beautiful cover images
- MySQL + Prisma
- Clerk Authentication
- Shadcn UI & TailwindCSS

## Installation

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/nrocchi/next-saas-project-manager-app.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_WEBHOOK_SECRET=
```

### Setup Prisma

Add MySQL Database

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

## Contributors

The original author is [Nicolas Rocchi](https://github.com/nrocchi).
