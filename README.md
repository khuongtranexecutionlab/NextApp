This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started


Research SSG, SSR, CSR and ISR. In what cases do we use those methods?

```bash

SSG (Static Site Generation):
  SSG is suitable for content-heavy websites or blogs where content changes infrequently.
  Its also great for sites with a large number of pages that dont require real-time data.

SSR (Server-Side Rendering):
    SSR is ideal for applications with frequently changing content or personalized user experiences.
    Its a good choice when SEO is important, as search engines can index the server-rendered content.


CSR (Client-Side Rendering):
    CSR is suitable for highly interactive web applications where real-time data updates are crucial.
    It can improve user experience by providing faster navigation within the app once the initial load is complete.

ISR (Incremental Static Regeneration):
    ISR is a good choice for websites with dynamic content that doesnt change frequently but still requires updates. 
    Its often used for e-commerce product pages or news articles. You can set a revalidation interval to keep the content up-to-date.

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
