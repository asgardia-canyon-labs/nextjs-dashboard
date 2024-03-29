## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.


## Organization Structure

- `/app`: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- `/app/lib`: Contains functions used in your application, such as reusable utility functions and data fetching functions.
- `/app/ui`: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- `/public`: Contains all the static assets for your application, such as images.
- `/scripts`: Contains a seeding script that you'll use to populate your database in a later chapter.
- Config Files:
  - `next.config.js`

## Notes

- Database and User Supabase (Vercel at first then this since I can deploy in AWScd)
- Global Styling `/app/ui/global.css`
- https://console.prisma.io/clubdzr7o01r7xi0tgubpxzvt/overview
- https://nextjs.org/learn/dashboard-app/css-styling#tailwind
- Metrics
  - https://web.dev/cls/
- Note: unstable_noStore is an experimental API and may change in the future. If you prefer to use a stable API in your own projects, you can also use the Segment Config Option export const dynamic = "force-dynamic".
  -  https://nextjs.org/learn/dashboard-app/static-and-dynamic-rendering
- Complex Streaming stuff: https://nextjs.org/learn/dashboard-app/streaming
  - https://nextjs.org/learn/dashboard-app/streaming#grouping-components -- how to group load
- This is Search: https://nextjs.org/learn/dashboard-app/adding-search-and-pagination
- Entries are a good way to handle more complex forms: https://developer.mozilla.org/en-US/docs/Web/API/FormData/entries
- Security: https://nextjs.org/blog/security-nextjs-server-components-actions
- TODO
  - https://nextjs.org/learn/dashboard-app/improving-accessibility
