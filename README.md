# Mini Social

Mini Social is a modern, lightweight social networking app that lets you connect, share, and interact in real time. Built with a clean interface and powered by Supabase, it offers essential social features in a distraction-free environment.

## Features
- User authentication (sign up, sign in, logout)
- Create, like, and comment on posts
- Real-time updating feed
- Responsive and mobile-friendly design
- Powered by Supabase for backend and database

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/oshockley/SocialFeedBackend.git
   cd SocialFeedBackend
   ```
2. **Open `social.html` in your browser.**

   > No build step required! All logic is in the HTML file and uses Supabase for backend services.

## Configuration
- Update the Supabase URL and API key in `social.html` if you fork or deploy your own backend.
- Ensure your Supabase project has the following tables:
  - `profiles` (user profiles)
  - `posts` (user posts)
  - `likes` (post likes)
  - `comments` (post comments)

## Screenshots
![Mini Social Screenshot](screenshot.png)

## License
MIT

---

*Mini Social – Connect, share, and enjoy a simple social experience!*