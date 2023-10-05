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

Research getInitialProps, getStaticProps, getServerSideProps. In what cases do we use those methods?

getInitialProps:
    This method can be used in both client-side and server-side rendering (SSR) environments
    Use getInitialProps when you need to fetch data during the server-side rendering process or on the client side for initial page load. It's a versatile method that works for various scenarios, including fetching data from APIs, databases, or any other source.

getStaticProps: 
    This method is used for static site generation (SSG).
    Use getStaticProps when you want to pre-render a page at build time with data that doesn't change frequently. It's suitable for content-heavy websites, blogs, and e-commerce product pages where the content remains mostly static between builds.

getServerSideProps:
    This method is used for server-side rendering (SSR)
    Use getServerSideProps when you need to fetch data for a page on each request, ensuring that the content is always up-to-date and can include user-specific data. This is useful for personalized or frequently changing content.