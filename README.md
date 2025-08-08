# SocialBook

**SocialBook** is a modern social networking platform where users can share content online with friends, follow other users, and engage with posts through likes and comments.  
Built with **Next.js**, **ShadCN UI**, **PostgreSQL**, and **Clerk** for authentication.
<br/>
[Live Link](https://social-book-psi.vercel.app/)

---

## Features

- **User Authentication & Authorization** — Secure sign-up, login, and session management using [Clerk](https://clerk.dev).
- **Post Creation & Sharing** — Share text, images, or videos with your network.
- **Follow System** — Follow and unfollow other users to curate your feed.
- **Likes & Comments** — Interact with posts through likes and threaded comments.
- **Responsive UI** — Styled with [ShadCN UI](https://ui.shadcn.com) for a clean, modern design.
- **Real-time Updates** — Instant feedback on likes and comments (if implemented with WebSockets/SWR).
- **PostgreSQL Database** — Robust and scalable data storage.

---

## Tech Stack

- **Frontend:** [Next.js](https://nextjs.org/) (App Router)
- **UI Components:** [ShadCN UI](https://ui.shadcn.com)
- **Database:** [PostgreSQL](https://www.postgresql.org/)
- **ORM:** [Prisma](https://www.prisma.io/)
- **Auth:** [Clerk](https://clerk.dev)
- **Styling:** Tailwind CSS
- **Deployment:** Vercel

---

## Project Structure

```
socialbook/
├── app/               # Next.js App Router pages & layouts
├── components/        # Reusable UI components
├── lib/               # Utility functions & database config
├── prisma/            # Prisma schema & migrations
├── public/            # Static assets
├── styles/            # Global styles
└── README.md
```

---

## Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/socialbook.git
cd socialbook
```

### 2️⃣ Install dependencies
```bash
npm install
# or
yarn install
```

### 3️⃣ Setup environment variables
Create a `.env` file in the root of your project and add:

```env
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

### 4️⃣ Setup the database
```bash
npx prisma migrate dev
```

### 5️⃣ Run the development server
```bash
npm run dev
```
Your app will be available at **[http://localhost:3000](http://localhost:3000)**

---

## Screenshots
<img width="1890" height="3216" alt="social-book-psi vercel app_ (2)" src="https://github.com/user-attachments/assets/c8e112b9-52cd-477a-8ce7-521169f80e8d" />
<img width="1890" height="1779" alt="social-book-psi vercel app_ (1)" src="https://github.com/user-attachments/assets/36ccc9cf-e6d4-4178-8b04-cbe6246ea6f8" />
<img width="1000" height="1910" alt="social-book-psi vercel app_ (3)" src="https://github.com/user-attachments/assets/1172f013-a162-41b1-8687-6f6610889aef" />

---


##  License
This project is licensed under the **MIT License** — you’re free to use, modify, and distribute it.

---

## Future Enhancements
- Real-time chat feature
- Notifications for likes, comments, and follows
- Media uploads (images/videos)
- Explore page for discovering new content

---

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## Acknowledgements
- [Next.js](https://nextjs.org/)
- [ShadCN UI](https://ui.shadcn.com)
- [PostgreSQL](https://www.postgresql.org/)
- [Clerk](https://clerk.dev)
- [Prisma](https://www.prisma.io/)
