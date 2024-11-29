# **Threads**

Threads is a modern, full-stack application designed to provide a seamless social media-like experience. Built with Next.js, Clerk for authentication, and Tailwind CSS for styling, it offers a scalable, user-friendly platform for creating, sharing, and interacting with content.

---

## **Features**

- **User Authentication**: Secure and easy-to-use authentication powered by Clerk.
- **Responsive Design**: Fully responsive interface built with Tailwind CSS.
- **Dynamic Content**: Real-time updates and smooth navigation using Next.js.
- **API Integration**: Extensible API support for integrating additional services.
- **Clean Codebase**: Structured and maintainable architecture for developers.

---

## **Technologies Used**

- **Frontend**:

  - [React](https://reactjs.org/)
  - [Next.js](https://nextjs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)

- **Backend**:

  - [Next.js API Routes](https://nextjs.org/docs/api-routes/introduction)

- **Authentication**:

  - [Clerk](https://clerk.dev/)

- **Linting & Formatting**:
  - [ESLint](https://eslint.org/)
  - [Prettier](https://prettier.io/)

---

## **Installation**

To set up this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Anish358/threads.git
   cd threads

   ```

2. **Install dependencies**:

   ```bash
   npm install

   ```

3. **Configure environment variables**:

   ```bash
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   NEXT_CLERK_WEBHOOK_SECRET=
   MONGODB_URL=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   UPLOADTHING_SECRET=
   UPLOADTHING_APP_ID=

   ```

4. **Run the development server:**:
   ```bash
   npm run dev
   ```

**Open http://localhost:3000 to view it in the browser.**
