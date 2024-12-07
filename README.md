This repository demonstrates a common issue encountered when using nested routes in React Router v6 with a catch-all route ('*'). The problem arises when the catch-all route is placed before more specific nested routes, causing it to incorrectly intercept all navigation requests, even those intended for nested paths.  The solution involves re-ordering the routes to prioritize specific routes over the catch-all route.