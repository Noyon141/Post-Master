# Post Master

Post Master is a **Next.js** application designed to streamline and enhance your content management and delivery workflows. This project leverages modern web technologies and follows best practices for performance and scalability.

---

## 🚀 Features

- **Server-Side Rendering (SSR)** and **Static Site Generation (SSG)** for optimal performance.
- **Authentication** using OAuth and email-based providers.
- **Environment-based configurations** for seamless deployment.
- **Customizable UI** with Tailwind CSS.
- **Database Integration** with Prisma.

---

# Ensure the following environment variables are set in your .env file

# Base URL for authentication

NEXTAUTH_URL=https://yourdomain.com

# Secret key for authentication

AUTH_SECRET=your-secret-key

# Google OAuth Client ID & Client Secret

AUTH_GOOGLE_ID=your-google-client-id  
AUTH_GOOGLE_SECRET=your-google-client-secret

# Connection string for the database

DATABASE_URL=postgresql://user:pass@host/db
