# Airbnb Like App

This full-stack web booking application embraces the latest web development technologies, including React, TypeScript, Tailwind CSS, Prisma, MongoDB, and NextAuth, to provide a seamless and efficient booking experience.

The frontend is built with React and TypeScript, ensuring a responsive and interactive user interface. Tailwind CSS offers a versatile and customizable styling framework, enhancing the application's visual appeal and user experience.

Prisma acts as the ORM (Object-Relational Mapping) tool, simplifying database interactions and facilitating efficient data management. MongoDB serves as the database, ensuring reliable and scalable storage for booking information.

NextAuth handles authentication and authorization, providing secure user access and session management. Users can sign up, log in, and manage their bookings securely.

This full-stack web booking application enables users to search and book services, manage reservations, and receive notifications. It leverages the power of modern web technologies to deliver a user-friendly and efficient booking platform.

With React, TypeScript, Tailwind CSS, Prisma, MongoDB, and NextAuth working together, this application offers a reliable, scalable, and secure solution for all your booking needs.


## Setup

- Git clone the project
- cd into the project `cd airbnb-like-app`
- Install packages `npm install`

- Setup `.env`

```
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

- Setup Prisma `npx prisma db push`
- Run app `npm run dev`
