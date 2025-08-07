# Next.js Music School Website

A modern and visually appealing music school website built with Next.js, TypeScript, and Tailwind CSS. This project showcases a range of interactive UI components to create an engaging user experience.

## Features

-   **Modern Tech Stack**: Built with the latest features of Next.js 14 and the App Router.
-   **Interactive UI**: Leverages Aceternity UI for stunning, animated components like background beams, 3D cards, and infinite moving cards.
-   **Responsive Design**: Fully responsive layout that looks great on all devices, from desktops to mobile phones.
-   **Component-Based Architecture**: Clean and maintainable code with a well-organized component structure.
-   **Static Data**: Course information is managed through a simple JSON file (`src/data/music_courses.json`), making it easy to update content.

## Pages

-   **Home**: A beautiful landing page featuring:
    -   A hero section with a call-to-action.
    -   A list of featured courses.
    -   A "Why Choose Us" section with sticky scrolling.
    -   Student testimonials in a moving card carousel.
    -   Upcoming webinars.
    -   A showcase of instructors with animated tooltips.
-   **All Courses**: A page displaying all available music courses with 3D card effects.
-   **Contact Us**: A simple and elegant contact form with animated background beams.

## Tech Stack

-   Next.js - The React Framework for the Web.
-   React - A JavaScript library for building user interfaces.
-   TypeScript - Typed JavaScript for robust applications.
-   Tailwind CSS - A utility-first CSS framework.
-   Aceternity UI - A collection of copy-paste UI components for React & Next.js.
-   Framer Motion - For animations.

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
