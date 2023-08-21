
# AI-Companion | A Web Application/ SaaS

This project is an example of software as a service / web application build using NextJs. Each part of this project is sample code to demonstrate the following: 


 Features

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Clerk Authentication (Email, Google, 9+ Social Logins)
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Image Generation Tool (Open AI)
- Conversation Generation Tool (Open AI / Replicate)
- Page loading state
- Stripe monthly subscription
- Free tier with API limiting
- How to write POST, DELETE, and GET routes in route handlers (app/api)
- How to fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)
- How to handle relations between Server and Child components!
- How to reuse layouts
- Folder structure in Next 13 App Router


## Prerequisites
`Node Version 20.x.x & above`
## Cloning the repository
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file


`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=`
`CLERK_SECRET_KEY= `
`NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in `
` NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up`
`NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard `
`NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard `

`OPENAI_API_KEY= `
` REPLICATE_API_TOKEN=`
`PINECONE_API_KEY= `
`PINECONE_ENVIRONMENT= `
` PINECONE_INDEX=`
`UPSTASH_REDIS_REST_URL= `
` UPSTASH_REDIS_REST_TOKEN=`
`NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME= `
`DATABASE_URL= `
`STRIPE_API_KEY= `
`STRIPE_WEBHOOK_SECRET= `
`NEXT_PUBLIC_APP_URL="http://localhost:3000" `





## Setup Prisma
Add MySQL Database (I used Locally)

` npx prisma db push`

seed categories:

`node scripts/seed.ts`



## Start the App

`npm run dev   `
## How to use this project

Since this is an example project , I'd encourage you to clone this repo and add your .env file and use it as a starter boilerplate.
