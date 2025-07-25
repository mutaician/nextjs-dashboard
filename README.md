## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Chapter 9
Suspense allows you to defer rendering parts of your application until a condition is met 

### Chapter 10

1. Created a database in the same region as your application code to reduce latency between your server and database.
2. Fetched data on the server with React Server Components. This allows you to keep expensive data fetches and logic on the server, reduces the client-side JavaScript bundle, and prevents your database secrets from being exposed to the client.
3. Used SQL to only fetch the data you needed, reducing the amount of data transferred for each request and the amount of JavaScript needed to transform the data in-memory.
4. Parallelize data fetching with JavaScript - where it made sense to do so.
5. Implemented Streaming to prevent slow data requests from blocking your whole page, and to allow the user to start interacting with the UI without waiting for everything to load.
6. Move data fetching down to the components that need it, thus isolating which parts of your routes should be dynamic.

### Chapter 11
Debouncing is a programming practice that limits the rate at which a function can fire. In our case, you only want to query the database when the user has stopped typing.

You've handled search and pagination with URL search parameters instead of client state.
You've fetched data on the server.
You're using the useRouter router hook for smoother, client-side transitions.

### Chapter 12
React Server Actions allow you to run asynchronous code directly on the server. They eliminate the need to create API endpoints to mutate your data. Instead, you write asynchronous functions that execute on the server and can be invoked from your Client or Server Components.

useing server actions to mutate data 
using revalidatepath api to revalidate nextjs cache and redirect to redirect user to new page

### Chapter 13

error handling using error.tsx and not-found.tsx
custom not-found 

### Chapter 14

Improving accesibility
using eslint: pnpm lint
using **useActionState** to show more custom error messages in forms
more error management 


Here are some resources to continue exploring Next.js:

- [Next.js Documentation](https://nextjs.org/docs)
- [Next.js Repository](https://github.com/vercel/next.js)
- [Vercel YouTube](https://www.youtube.com/@VercelHQ/videos)
- [Vercel Reddit](https://www.reddit.com/r/vercel/)

- [Next.js Templates](https://vercel.com/templates/next.js) :
  - [Admin Dashboard Template](https://vercel.com/templates/next.js/admin-dashboard-tailwind-postgres-react-nextjs)
  - [Next.js Commerce](https://vercel.com/templates/next.js/nextjs-commerce)
  - [Blog Starter Kit](https://vercel.com/templates/next.js/blog-starter-kit)
  - [AI Chatbot](https://vercel.com/templates/next.js/nextjs-ai-chatbot)
  - [Image Gallery Starter](https://vercel.com/templates/next.js/image-gallery-starter)
