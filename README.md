# MeetMentor - AI Meeting Communication Advisor

MeetMentor is an innovative AI-powered platform designed to help professionals enhance their meeting communication skills through personalized guidance and real-time feedback.

## 🌟 Features

- **Intelligent Chat Interface**: Clean, intuitive design with real-time AI responses
- **Speech-to-Text Support**: Easily practice verbal communication skills
- **Custom-Trained AI**: Specialized Gemini Pro integration for meeting scenarios
- **Secure Authentication**: Protected user sessions via Clerk
- **Chat Management**: Organized conversation history with automatic title generation
- **Responsive Design**: Seamless experience across desktop and mobile devices

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **UI Components**: shadcn/ui
- **Authentication**: Clerk
- **Database**: MongoDB
- **AI Integration**: Google Gemini Pro API
- **State Management**: React Hooks
- **Styling**: Tailwind CSS

## 📦 Project Structure

```
meetmentor/
│   ├── app/              # Next.js app router pages
│   ├── components/       # React components
│   ├── lib/             # Utility functions and APIs
│   ├── hooks/           # Custom React hooks
│   └── types/           # TypeScript definitions
```

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/meetmentor.git
cd meetmentor
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `.env` file in the root directory:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
MONGODB_URI=your_mongodb_uri
GEMINI_API_KEY=your_gemini_api_key
```

4. **Run the development server**
```bash
npm run dev
```

Visit `http://localhost:3000` to see the application.

## 🔑 Environment Variables

- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Clerk authentication public key
- `CLERK_SECRET_KEY`: Clerk authentication secret key
- `MONGODB_URI`: MongoDB connection string
- `GEMINI_API_KEY`: Google Gemini Pro API key

## 📱 Features in Development

- Advanced search functionality
- Chat categorization
- Export capabilities
- Team collaboration features
- Analytics dashboard

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

Your Name - [Mohiuddin](https://mohiuddin200.vercel.app/)

Project Link: [GitHub](https://github.com/Mohiuddin-64bit)