# Next.js Inconsistent Runtime Error During Navigation

This repository demonstrates a bug in a Next.js application where an unhandled runtime error occurs inconsistently when navigating between pages. The error does not appear to be related to a specific action, route, or component. It's random and difficult to debug.

## Bug Description

The Next.js application consists of two pages: a home page and an about page.  Navigating between these pages using the built-in `Link` component and `useRouter` results in an intermittent runtime error. The error is not consistent and can occur after multiple successful navigations.

## How to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate between the home page and the about page multiple times.
5. Observe that an unhandled runtime error might occur at some point.