# fSociety Blog

A modern, responsive blog website built with Next.js 15, TypeScript, and Tailwind CSS.
## 🚀 Features

- **Modern Design**: Dark theme with orange/red gradient accents
- **Responsive Layout**: Mobile-first design that works on all devices
- **Blog System**: Complete blog with categories, featured posts, and pagination
- **User Authentication**: Login and signup pages (UI only)
- **Performance Optimized**: Fast loading with Next.js optimizations

## 📁 Project Structure

```
├── app/
│   ├── (frontend)/          # Public pages
│   │   ├── page.tsx         # Home page
│   │   ├── blog/            # Blog pages
│   │   ├── about-us/        # About page
│   │   ├── contact/         # Contact page
│   │   └── categories/      # Categories page
│   ├── (User)/              # User pages
│   │   ├── login/           # Login page
│   │   ├── signup/          # Signup page
│   │   └── dashboard/       # Dashboard page
│   ├── globals.css          # Global styles
│   └── layout.tsx           # Root layout
├── Components/               # Reusable components
│   ├── Navbar.tsx           # Navigation bar
│   ├── Footer.tsx           # Footer component
│   └── UserNav.tsx          # User navigation
├── public/                  # Static assets
│   ├── favicon.ico
│   ├── preview.png
│   └── wallpaperflare.com_wallpaper.jpg
└── package.json
```

## 🛠️ Technologies Used

- **Next.js 15** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Framer Motion** - Animations
- **mongoose** - schemas and models
- **Database** -mongodb
- 
## 🚀 Getting Started

## 📱 Pages

### Public Pages
- **Home** (`/`) - Featured posts and latest articles
- **Blog** (`/blog`) - All blog posts with category filtering
- **About** (`/about-us`) - About page
- **Contact** (`/contact`) - Contact page
- **Categories** (`/categories`) - Category listing

### User Pages
- **Login** (`/login`) - User login form
- **Signup** (`/signup`) - User registration form
- **Dashboard** (`/dashboard`) - User dashboard

## 🎨 Design Features

### Color Scheme
- **Primary**: Orange (#f97316) to Red (#ef4444) gradient
- **Background**: Dark gray (#111827) to black
- **Text**: White and light gray
- **Accents**: Orange highlights and borders

### Typography
- **Headings**: Bold, large sizes with gradient text
- **Body**: Clean, readable font
- **Responsive**: Scales appropriately on all devices

### Components
- **Cards**: Rounded corners with subtle shadows
- **Buttons**: Gradient backgrounds with hover effects
- **Forms**: Clean input fields with focus states
- **Navigation**: Responsive menu with smooth transitions

### Styling
- Global styles: `app/globals.css`
- Component styles: Inline Tailwind classes
- Color scheme: Update Tailwind config or CSS variables
- 
### Build for Production
### deployed on vercel

## 🚧 Future Enhancements

- [ ] Comment system
- [ ] SEO optimization
- [ ] Email newsletter
- [ ] Social sharing


## 📞 Support

If you have any questions or need help, please open an issue on GitHub.

---

**Happy coding! 🚀**
