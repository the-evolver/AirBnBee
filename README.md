
# Welcome to the AirBnBee Repository!

This repository contains a Full Stack Airbnb Clone with Next.js 13 App. The project is developed by Atul Kumar and the project's website can be found below . The purpose of this project is for personal learning.

Website : https://atul-bnb-bee.vercel.app/

AirBnBee is an innovative and buzzing project that aims to provide a unique and delightful accommodation experience for travelers. Inspired by the vibrant world of bees, AirBnBee offers a platform where hosts can showcase their properties, and guests can find their perfect hive away from home.

Key Features:

Beeautiful User Interface: The project boasts a visually appealing and intuitive user interface, designed to create a seamless browsing experience for both hosts and guests.
Honeycomb Authentication: AirBnBee incorporates a secure authentication system, allowing users to register, log in, and manage their profiles with ease.
Buzzworthy Listings: Hosts can create and manage their property listings, providing detailed information about the accommodations, amenities, and pricing.
Search Pollenation: The project includes an advanced search functionality, empowering guests to discover their ideal hive based on location, dates, guest capacity, and other preferences.
Nectar of Bookings: Guests can explore the available properties, view property details, and make bookings effortlessly, ensuring a seamless and secure transaction process.
Hive Messaging: AirBnBee facilitates smooth communication between hosts and guests, enabling them to exchange messages, clarify details, and make arrangements conveniently.
Hive Reviews: Guests can provide feedback and leave reviews about their stay, promoting transparency and assisting future travelers in making informed decisions.
Beeutiful Maps: The project integrates interactive maps to provide users with a visual representation of property locations, making it easier to choose the perfect hive.

By leveraging technologies such as React, Next.js, Tailwind CSS, Prisma, MongoDB, and NextAuth, AirBnBee aims to create a buzzing and immersive experience for all users, ensuring a memorable and sweet journey in the world of accommodations.

## Features

- Tailwind design for a modern and visually appealing UI
- Tailwind animations and effects to enhance user experience
- Full responsiveness to ensure a seamless experience across different devices
- Credential authentication for secure user login
- Google authentication for easy login using Google accounts
- GitHub authentication for easy login using GitHub accounts
- Image upload functionality using the Cloudinary CDN
- Client-side form validation and handling using react-hook-form
- Server-side error handling using react-toast
- Calendars with react-date-range for date selection
- Page loading state to provide visual feedback to users during data loading
- Page empty state to handle scenarios where no data is available
- Booking and reservation system for managing property reservations
- Guest reservation cancellation for flexibility in managing bookings
- Owner reservation cancellation for property owners to manage their listings
- Creation and deletion of properties to enable users to add and remove listings
- Pricing calculation to provide accurate cost estimation for reservations
- Advanced search algorithm with filtering options based on category, date range, map location, number of guests, rooms, and bathrooms
- Favorites system for users to save and manage their favorite properties
- Shareable URL filters to easily share search results with others
- POST and DELETE route handling in route handlers (app/api)
- Fetching data in server-side React components by directly accessing the database (WITHOUT API)
- Handling files like error.tsx and loading.tsx, which are new Next 13 templating files for unified loading and error handling
- Handling relations between server and child components

## Installation

To run this project locally, please follow the instructions below:

### Cloning the repository

Clone the repository to your local machine:

```
git clone https://github.com/the-evolver/AirBnBee
```

### Install packages

Navigate to the project directory and install the required packages:

```
cd [project directory]
npm install
```

### Setup Cloudinary

1. Sign up for a Cloudinary account (or equivalent service) and obtain your API credentials.
2. Open the `ImageUpload.tsx` file and locate the following line:
   ```
   const uploadPreset = "Name of upload preset that you need to create";
   ```
   Replace `"Name of upload preset that you need to create"` with the actual name of the upload preset you created in your Cloudinary account.

### Setup MongoDB (or equivalent)

Ensure you have MongoDB (or an equivalent database) set up and running. Obtain the connection URL or connection string.

### Setup Google Cloud Console

1. Sign up for a Google Cloud Console account (or equivalent service) and create a new project.
2. Obtain the `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET` for your project.

### Setup .env file

Create a `.env` file in the project root directory and add the following environment variables:

```
DATABASE_URL=your_database_connection_url
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GITHUB_ID=your_github_id
GITHUB_SECRET=your_github_secret
NEXTAUTH_SECRET=your_nextauth_secret
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
```

Replace `your_database_connection_url`, `your_google_client_id`, `your_google_client_secret`, `your_github_id`, `your_github_secret`, `your_nextauth_secret`, and `your_cloudinary_cloud_name` with the actual values specific to your setup.

### Setup Prisma

Push the database changes using Prisma:

```
npx prisma db push
```

### Start the app

Start the development server:

```
npm run dev
```

Ensure that the app is running successfully and you can access it in your browser.

If you encounter any issues during the installation or have further questions, feel free to reach out for assistance.

## Usage

To use this project, follow these steps:

1. Ensure you have completed the installation steps mentioned above.

2. Start the development server:

   ```
   npm run dev
   ```

3. Access the application in your preferred web browser by navigating to `http://localhost:3000`.

4. Explore the different features of the Full Stack Airbnb Clone with Next.js 13 App. You can:

   - Browse and search for properties using advanced filters.
   - View property details, including images, pricing, and amenities.
   - Sign up or log in using your credentials or Google/GitHub accounts.
   - Create and manage your property listings.
   - Make reservations for properties and manage your bookings.
   - Favorite properties to save them for future reference.
   - Share search results with others using shareable URL filters.

5. Interact with the application's UI and functionalities based on your specific needs and goals. Make use of the various features mentioned in the project description.

6. Experiment with different scenarios, such as creating, editing, or deleting properties, making reservations, and testing the authentication mechanisms.

7. Feel free to customize and modify the project code to suit your requirements. Explore the different files and components to understand the project structure and make enhancements as needed.

Enjoy using the Full Stack Airbnb Clone with Next.js 13 App!

## Contact

If you have any questions or suggestions regarding this project or encounter any issues specific to your environment (Mac or otherwise), feel free to reach out to me .

Website: https://the-evolver.github.io/
GitHub: https://github.com/the-evolver

Please note that this project was developed on a macOS environment, and if you encounter any errors or compatibility issues on a different environment, you may need to make suitable changes or adaptations based on your specific setup.

If you need any assistance or have further inquiries, I will be happy to assist you.
