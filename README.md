<div align="center">
    <h3 align="center">Money Map</h3>
   <div align="center">
    Your ultimate personal finance companion. MoneyMap helps you track your income, expenses, and savings effortlessly. With an intuitive interface and powerful features, you can visualize your financial journey, set budgeting goals, and make informed decisions to stay on top of your finances. Whether you're planning for a big purchase or simply want to manage daily expenses, MoneyMap guides you every step of the way. Navigate your financial future with confidence and ease.
    </div>
</div>

## 🚀 Feature

## ⚙️ Tech Stack

- Next.js
- Clerk
- Shadcn-UI
- Prisma ORM
- PostgreSQL
- Zod

## Setup .env file

```js
NEXT_PUBLIC_BASE_URL=<your_server>

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<get_from_clerk>
CLERK_SECRET_KEY=<get_from_clerk>
NEXT_PUBLIC_CLERK_SIGN_IN_URL="/sign-in"
NEXT_PUBLIC_CLERK_SIGN_UP_URL="/sign-up"
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL="/"
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL="/wizard"

POSTGRES_URL=<get_from_vercel>
POSTGRES_PRISMA_URL=<get_from_vercel>
POSTGRES_URL_NO_SSL=<get_from_vercel>
POSTGRES_URL_NON_POOLING=<get_from_vercel>
POSTGRES_USER=<get_from_vercel>
POSTGRES_HOST=<get_from_vercel>
POSTGRES_PASSWORD=<get_from_vercel>
POSTGRES_DATABASE=<get_from_vercel>
```

### Install dependencies

```shell
npm install
```

### Start the app

```shell
npm run dev
```

### Run migration

```shell
npx prisma studio
```

## ❤️ Credits

## 🤖 Author

_M Hendri Febriansyah_

