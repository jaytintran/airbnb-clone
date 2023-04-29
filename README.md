This is a full-stack Airbnb clone that I built using Next.js, React.js, TailwindCSS, Prisma, MongoDB, and NextAuth. The goal of this project was to learn and practice using Next.js, a popular framework for building React-based web applications.

## **Technologies Used**

This project was built using the following technologies:

- **Next.js**: A popular framework for building React-based web applications.
- **React.js**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A utility-first CSS framework for quickly styling web applications.
- **Prisma**: A database ORM that simplifies working with databases.
- **MongoDB**: A popular NoSQL database used to store and manage data.
- **NextAuth**: A simple and easy-to-use library for authentication in Next.js applications.
- **Axios**: A popular library for making HTTP requests from web applications.
- **Mapbox**: A platform for building custom maps and location-based applications.
- **date-fns**: A lightweight JavaScript library for working with dates and times.
- **Packages**: next/router, react-icons, eslint, autoprefixer, postcss

These technologies were chosen for their ease of use, flexibility, and popularity within the web development community. Together, they allowed me to build a full-stack Airbnb clone that is functional, responsive, and visually appealing.

## **Features**

This full-stack Airbnb clone includes the following features:

- **User Authentication**: Users can create accounts, log in, and log out of the application using NextAuth.
- **Search Listings**: Users can search for listings by location, date, and number of guests.
- **View Listings**: Users can view detailed information about individual listings, including photos, amenities, and reviews.
- **Bookings**: Users can book a listing for a specific date range and number of guests, and view their upcoming and past bookings.
- **Create Listings**: Users with host accounts can create new listings by providing details such as title, description, photos, and pricing.
- **Edit Listings**: Hosts can edit their existing listings, including updating details, adding or removing photos, and changing pricing.
- **Map View**: Users can view all listings on a map, making it easier to find listings in specific locations.
- **Responsive Design**: The application is designed to work well on both desktop and mobile devices, with a responsive layout and optimized images.

These features were implemented using a combination of Next.js, React.js, TailwindCSS, Prisma, MongoDB, and NextAuth, and provide a complete and functional user experience.

## **Learning Journey**

Building this project was a great learning experience for me. I had some experience with React.js and TailwindCSS before starting this project, but I was new to Next.js, Prisma, MongoDB, and NextAuth.

I started by learning the basics of Next.js, including its file-based routing system, server-side rendering, and static site generation capabilities. I found the Next.js documentation to be very helpful, and I also followed some online tutorials to learn more about the framework.

Next, I learned about Prisma, a database ORM that simplifies working with databases. I used Prisma to connect to a MongoDB database and define my data models.

After setting up the database, I used TailwindCSS to style the frontend of the application. I found TailwindCSS to be a powerful and flexible CSS framework that allowed me to easily create responsive and visually appealing designs.

Finally, I implemented user authentication using NextAuth, a simple and easy-to-use library for authentication in Next.js applications. I also added some additional features to the application, such as the ability to search for listings and make bookings.

### Steps

1. Environment setup
2. Navbar UI
3. Auth UI
4. Register functionality, MongoDB, Prisma setup
5. Login functionality
6. Social Login (Google and Github)
7. Categories UI
8. Listing creation step 1 (Category selection)
9. Listing creation step 2 (Location selection, Map component, Country autocomplete)
10. Listing creation step 3 (Counter components)
11. Listing creation step 4 (Image upload, Cloudinary CDN)
12. Listing creation step 5 (Description and Price, Listing creation POST route)
13. Fetching listings with server components (Listing card component, direct server action)
14. Favoriting functionality
15. Individual Listing View
16. Listing reservation component
17. Reservation functionality (routes, logic)
18. Trips screen (Loading trips with server component)
19. Reservations screen (Loading guest reservations with server component)
20. Favorites screen (Loading favorites with server component)
21. Properties screen (Loading your listings with server component)
22. Filters modal (Assigning various filters, add advanced querying logic to getListings, add loading and error pages)
23. Vercel deploy & wrap up

## **What I've Learned**

Building this full-stack Airbnb clone using Next.js, React.js, TailwindCSS, Prisma, MongoDB, and NextAuth has been an incredibly valuable learning experience. Here are some of the key things I've learned:

- **Server-side rendering with Next.js**: Next.js provides powerful server-side rendering capabilities out of the box, allowing for faster page loads and improved SEO.
- **Managing state with React.js**: React.js provides a simple and effective way to manage state in web applications, making it easier to build dynamic and interactive user interfaces.
- **CSS styling with TailwindCSS**: TailwindCSS provides a convenient way to style web applications using pre-defined classes, and its utility-first approach makes it easy to quickly style components without writing custom CSS.
- **Working with databases using Prisma**: Prisma provides a modern ORM for working with databases, simplifying the process of querying and updating data.
- **Building authentication using NextAuth**: NextAuth provides a straightforward way to add authentication to Next.js applications, with support for a wide range of authentication providers.
- **Deploying applications using Vercel**: Vercel provides a simple and powerful platform for deploying Next.js applications, with easy integration with other tools such as GitHub and MongoDB Atlas.

Overall, building this Airbnb clone has been an excellent opportunity to learn and practice a variety of web development skills, and I'm excited to continue building and learning with these technologies.

## **Project Structure**

The project is structured as follows:

- **`/app`**: Contains the Next.js pages that make up the application.
- **`/components`**: Contains reusable React components used throughout the application.
- **`/lib`**: Contains utility functions and constants used throughout the application.
- **`/public`**: Contains static assets used in the application, such as images and fonts.
- **`/styles`**: Contains global styles and TailwindCSS configuration.

## **Getting Started**

To run this project on your local machine, follow these steps:

1. Clone the repository: **`git clone https://github.com/your-username/nextjs-airbnb-clone.git`**
2. Install dependencies: **`npm install`**
3. Create a **`.env.local`** file in the project root and add the following environment variables:

   ```
   makefileCopy code
   MONGODB_URI=<your-mongodb-uri>
   NEXTAUTH_URL=http://localhost:3000

   ```

4. Start the development server: **`npm run dev`**
5. Open the application in your browser at **`http://localhost:3000`**

## **Conclusion**

Building this full-stack Airbnb clone was a challenging but rewarding experience. I learned a lot about Next.js, React.js, TailwindCSS, Prisma, MongoDB, and NextAuth, and I'm excited to continue exploring these technologies in future projects.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
