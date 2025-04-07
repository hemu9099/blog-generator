# AI-Powered Blog Generator Platform

A modern, full-stack web application for generating and managing blog content using AI. Built with React, Supabase, and Cohere AI.

![Project Preview](https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?auto=format&fit=crop&q=80&w=2400)

## Features

- 🤖 AI-powered content generation using Cohere AI
- 📝 Rich text editing and preview
- 📊 Advanced analytics dashboard
- 📅 Post scheduling system
- 👥 User authentication and profile management
- 🔒 Secure data handling with Row Level Security
- 📱 Responsive design with beautiful UI
- ⚡ Real-time updates using Supabase subscriptions

## Live Demo

[View Live Demo](https://your-deployed-app-url.netlify.app)

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Supabase (PostgreSQL, Authentication, Real-time subscriptions)
- **AI Integration**: Cohere AI
- **3D Graphics**: Three.js with React Three Fiber
- **State Management**: Zustand
- **Styling**: Tailwind CSS with custom animations
- **Icons**: Lucide React

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-actual-username/blog-generator.git
   cd blog-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   VITE_COHERE_API_KEY=your_cohere_api_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── 3d/            # Three.js components
│   └── ...
├── pages/             # Page components
├── store/             # Zustand store configurations
├── hooks/             # Custom React hooks
├── lib/               # Utility functions and configurations
├── types/             # TypeScript type definitions
└── main.tsx          # Application entry point
```

## Database Schema

### Tables

- `profiles`: User profiles and roles
- `posts`: Blog posts with scheduling and analytics
- `post_views`: View tracking for analytics
- `post_interactions`: User interactions with posts

## Features in Detail

### AI Content Generation
- Topic-based blog post generation
- SEO keyword suggestions
- Content structure optimization
- Smart content editing

### Analytics Dashboard
- View count tracking
- Reading time analytics
- User engagement metrics
- Performance insights

### Post Management
- Draft saving
- Post scheduling
- Content preview
- Real-time updates

### User System
- Email authentication
- Profile management
- Role-based access control
- Secure data policies

## Security

- Row Level Security (RLS) policies for all tables
- Secure authentication flow
- Environment variable protection
- Data validation and sanitization

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Contact

Your Full Name - [@your_twitter_handle](https://twitter.com/your_twitter_handle)

Project Link: [https://github.com/your-actual-username/blog-generator](https://github.com/your-actual-username/blog-generator)

## Screenshots

### Dashboard
![Dashboard](https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&q=80&w=2400)

### Content Generator
![Content Generator](https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?auto=format&fit=crop&q=80&w=2400)

### Analytics
![Analytics](https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&q=80&w=2400)
