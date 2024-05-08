# learn-nextjs

## The main goal

The goal of this project is learn how to use javascript as a backend.
See the differences from the perspective of knowing PHP.
The framework used will be Nextjs.
The way to learn all the knowledge will be through following the documentation of this framework, which I consider to be very complete.

### Milestones

1. Getting started. Create the skeleton of nextjs. Get familiar with the folder structure. Run the development server. Usage of CSS, fonts and images.
Src folder. App router. Tailwindcss. 

3. Layouts and pages. Creation of new pages and layouts. Learn how the navigation works.
Automatic navigation between pages. Folder structure matters.

4. Database. Setting up a database. Fetching and mutating data. Learn how to create a CRUD.
Vercel configuration. Manual queries. API route structure. Use Prisma as ORM.

5. Static and dynamic rendering. Learn the usage of optimizing the application using cache.
Static rendering for landing pages. Dynamic rendering for real time data or user specific.
By default nextjs tries to catch static content. Use `noStore` to define dynamic content.
This part only explains how to use cache (static and dynamic) problem: Blocks entire page waiting for requests.

6. Streaming. Learn what is streaming. Loading skeletons.
Loading.tsx and Suspense. Whole page skeleton vs components skeletons.

7. Search and pagination. Typical usage of tables with information.
Use query params.

8. Handling errors. try/catch methods that can fail.
Try catch way and error404 pages.

9. Authentication. Add a login system with authorization roles.
Use next-auth package.
