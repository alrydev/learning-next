    ## Routing /pages

    Next.js is a React framework that has a very flexible routing capability. When creating a Next.js application, we can determine the routing using several different approaches, one of which is by creating multiple files inside the `/pages` directory.


    In this approach, every file placed inside the pages directory is automatically turned into a route.
    <br/>In this example, if you create a file `pages/dashboard/index.tsx`


    ├── index.tsx

    └── settings.tsx

    We can access the index.tsx with `/dashboard` route and settings.tsx with `/dashboard.settings.tsx` route in your Next.js application. This is suitable for creating simple Next.js applications that do not require a complex routing structure.
    <br/><br/><br/>




    another example:
    <br/>
    pages/

    ├── index.tsx

    ├── about.tsx

    ├── contact.tsx

    └── ...

    In this example, the index.tsx, about.tsx, and contact.tsx files are automatically turned into routes that can be accessed at `/`, `/about`, and `/contact`, respectively.

