# Social 🚀

A modern, full-stack social media application built with Next.js 14, featuring real-time interactions, user authentication, and a beautiful responsive design.


## ✨ Features

- 🔐 **User Authentication** - Secure login/signup with Clerk
- 👥 **User Profiles** - Customizable user profiles and avatars
- 📝 **Posts & Content** - Create, edit, and delete posts
- 💬 **Real-time Interactions** - Like, comment, and share functionality
- 🖼️ **File Uploads** - Image and media uploads with UploadThing
- 🌙 **Dark/Light Mode** - Theme switching with next-themes
- 📱 **Responsive Design** - Mobile-first approach with Tailwind CSS
- 🎨 **Modern UI** - Beautiful components built with Radix UI
- 🗄️ **Database** - Prisma ORM with robust data modeling
- ⚡ **Performance** - Built with Next.js 14 App Router

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, CSS Modules
- **UI Components**: Radix UI, Lucide React Icons
- **Authentication**: Clerk
- **Database**: Prisma ORM
- **File Uploads**: UploadThing
- **State Management**: React Hooks
- **Notifications**: React Hot Toast
- **Theming**: next-themes

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Database (PostgreSQL, MySQL, or SQLite)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd socially
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   
   # Database
   DATABASE_URL="your_database_connection_string"
   
   # UploadThing
   UPLOADTHING_SECRET=your_uploadthing_secret
   UPLOADTHING_APP_ID=your_uploadthing_app_id
   ```

4. **Database Setup**
   ```bash
   # Generate Prisma client
   npx prisma generate
   
   # Run database migrations
   npx prisma db push
   ```

5. **Start Development Server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
socially/
├── src/
│   ├── app/                 # Next.js App Router pages
│   ├── components/          # Reusable UI components
│   ├── actions/             # Server actions
│   ├── lib/                 # Utility functions and configurations
│   └── middleware.ts        # Next.js middleware
├── prisma/                  # Database schema and migrations
├── public/                  # Static assets
├── components.json          # UI components configuration
├── tailwind.config.ts       # Tailwind CSS configuration
└── package.json            # Dependencies and scripts
```

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run postinstall` - Generate Prisma client

## 🔧 Configuration

### Tailwind CSS
The project uses Tailwind CSS with custom animations and responsive design utilities.

### Prisma
Database schema is defined in `prisma/schema.prisma`. Run `npx prisma studio` to open the database GUI.

### Clerk Authentication
Set up your Clerk application and configure the environment variables for authentication.

### UploadThing
Configure file uploads by setting up your UploadThing account and environment variables.

## 🚀 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Set environment variables in Vercel dashboard
4. Deploy!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework
- [Clerk](https://clerk.com/) - Authentication
- [Prisma](https://www.prisma.io/) - Database ORM
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Radix UI](https://www.radix-ui.com/) - UI components
- [UploadThing](https://uploadthing.com/) - File uploads


**Happy coding! 🎉**
