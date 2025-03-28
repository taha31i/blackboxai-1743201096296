# QuickHabit - Micro-Habit Tracking App

QuickHabit is a modern web application designed to help busy professionals build lasting habits through micro-actions. The app focuses on habits that take 5 minutes or less and integrates with users' work calendars to suggest optimal times for habit completion.

## Features

- **User Authentication**
  - Email/Password login
  - Google OAuth integration
  - Apple OAuth integration
  - Secure session management

- **Dashboard**
  - Clean, intuitive interface
  - Daily/weekly habit tracking
  - Progress visualization
  - Streak tracking
  - Dark mode support

- **Calendar Integration**
  - Google Calendar sync
  - Smart time slot suggestions
  - AI-driven reminders
  - Free time detection

- **Habit Management**
  - Pre-set micro-habits library
  - Custom habit creation
  - Flexible scheduling options
  - Progress tracking

- **Responsive Design**
  - Mobile-first approach
  - Dark mode support
  - Accessible interface

## Tech Stack

- **Frontend**
  - Next.js (React)
  - Tailwind CSS
  - Next-Auth
  - React Query
  - Zustand (State Management)

- **Authentication**
  - NextAuth.js
  - Google OAuth
  - Apple OAuth
  - Email Authentication

- **Calendar Integration**
  - Google Calendar API
  - Microsoft Graph API (Outlook)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quickhabit.git
   cd quickhabit
   ```

2. Install dependencies:
   ```bash
   cd frontend
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.local.example` to `.env.local`
   - Fill in your OAuth credentials and other environment variables

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

Create a `.env.local` file with the following variables:

```env
# Authentication
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key-here

# Google OAuth
GOOGLE_ID=your-google-client-id
GOOGLE_SECRET=your-google-client-secret

# Apple OAuth
APPLE_ID=your-apple-client-id
APPLE_SECRET=your-apple-client-secret

# Email Provider
EMAIL_SERVER_HOST=smtp.example.com
EMAIL_SERVER_PORT=587
EMAIL_SERVER_USER=your-email-user
EMAIL_SERVER_PASSWORD=your-email-password
EMAIL_FROM=noreply@example.com
```

## Project Structure

```
quickhabit/
├── frontend/
│   ├── components/        # Reusable React components
│   ├── pages/            # Next.js pages and API routes
│   ├── store/            # Zustand store configurations
│   ├── styles/           # Global styles and Tailwind config
│   └── public/           # Static assets
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.