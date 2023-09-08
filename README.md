# react-worldwise

This project is a technical progression to my vanilla js project mapty (https://rahulsomaliya.github.io/workout-tracker-mapty). It lets a user add places where they've traveled by pin-pointing the location right from the map. Those cities will be updated and maintained in the JSON server I deployed over Vercel (https://react-worldwise-db.vercel.app).

Routing for this project is implemented using React Router - so the app is a big Single Page Application and no page refreshes are faced while navigating from one page to another, react-router's dynamic param functionality is also used for storing state in the URL. For code cleanliness, no prop drilling whatsoever is done in the project, as all states are passed using context API. And I've used CSS modules to make CSS components' specific and not a global mess. Also, I learned to memoize components, and functions using the useMemo hook for components and useCallback hook for simple functions.

TLDR, here's the deployment - https://react-worldwise.vercel.app
