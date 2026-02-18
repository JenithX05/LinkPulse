# LinkPulse - URL Shortener

A modern, feature-rich URL shortener application built with React, Tailwind CSS, Supabase, and Shadcn UI.

![LinkPulse Logo](public/logo.png)

## ✨ Features

- **URL Shortening**: Convert long URLs into short, shareable links
- **Analytics Dashboard**: Track clicks, geographic location, and device statistics
- **QR Code Generation**: Generate QR codes for shortened URLs
- **User Authentication**: Secure login and signup functionality
- **Responsive Design**: Beautiful UI that works on all devices
- **Real-time Stats**: Monitor link performance with live analytics

## 🛠️ Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS, Shadcn UI
- **Backend**: Supabase (Database & Auth)
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Form Validation**: Yup
- **QR Codes**: React QR Code Logo

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Supabase account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/JenithX05/LinkPulse.git
   cd LinkPulse
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory and add your Supabase credentials:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Set up Supabase database**
   
   - Create a new project in [Supabase](https://supabase.com)
   - Run the SQL migration provided in the project
   - Set up authentication providers

5. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. **Open your browser**
   
   Navigate to `http://localhost:5173`

## 📁 Project Structure

```
LinkPulse/
├── public/                 # Static assets
├── src/
│   ├── components/        # Reusable UI components
│   │   └── ui/           # Shadcn UI components
│   ├── db/               # Database API functions
│   ├── hooks/            # Custom React hooks
│   ├── layouts/          # Layout components
│   ├── lib/              # Utility functions
│   └── pages/            # Page components
├── .env                  # Environment variables
├── package.json          # Project dependencies
└── README.md            # This file
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌐 Live Demo

Check out the live application: [LinkPulse Demo](https://your-demo-url.com)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web technologies
- Inspired by the need for simple, effective URL management
- Thanks to all contributors and the open-source community

---

**Made with ❤️ by [Your Name]**