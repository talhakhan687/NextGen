# NextGen

A full-stack online course platform where students can purchase and study courses, and admins can manage courses, lessons, and sales.

## Features

- Sign-up and sign-in with Clerk
- Admin panel to create and edit courses, sections, and lessons
- Drag-and-drop reordering of sections and lessons
- Secure payments and checkout with Stripe
- Access control for purchased courses
- User purchase history
- Product and sales management for admins

## Tech Stack

- **Next.js** (App Router) and **TypeScript**
- **Clerk**: Authentication
- **Drizzle ORM**: Database management
- **PostgreSQL**: Database
- **Stripe**: Payments
- **Tailwind CSS** and **shadcn/ui**: Styling and UI components

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/talhakhan687/NextGen.git
   cd NextGen
```
2. Install dependencies:
```bash
   npm install
```
3. Create a `.env` file and add the required keys (Clerk, Stripe, and database URL)
4. Set up the database:
```bash
   npx drizzle-kit push
```
5. Start the development server:
```bash
   npm run dev
```
6. Open `http://localhost:3000` in your browser

## Author

Abu Talha Khan