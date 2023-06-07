# Emojer

Twitter-inspired full-stack app, letting you express yourself (only!) with emojis. Built in Typescript with tRPC API for full-stack type-safety. Also includes GitHub sign-in (Clerk Auth).

Showcases my ability to build a full-stack app which is completely type-safe end-to-end, and using a modern framework / tech.

Tech used: React, Next.js, TypeScript, tRPC, Tailwind CSS, Prisma, MySQL, PlanetScale, Clerk Auth.

## How to run

1. Install dependencies by running 

```bash
npm install
```

2. Set up an account, with Clerk, PlanetScale, and Upstash. Create a new project / app with each of these services, and get relevant details required for env variables below.

3. Set up environment variables by creating .env file in root directory, and putting in the following variables

```bash
DATABASE_URL='your.planetscale.mysql.connection.url'
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY='your.clerk.application.publishable.key'
CLERK_SECRET_KEY='your.clerk.application.secret.key'
UPSTASH_REDIS_REST_URL="your.upstash.redis.rest.url"
UPSTASH_REDIS_REST_TOKEN="your.upstash.redis.rest.token"
```

4. Run in dev, by running the below command, and open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


```bash
npm run dev
```

## Deploy on Vercel

The easiest way to deploy the app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
