# Project Overview: AI-Powered Career Assistant

## Tech Stack
- **Frontend Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI Integration**: Vercel AI SDK
- **Authentication**: Firebase
- **Database**: Firebase Firestore
- **File Storage**: Firebase Storage
- **Additional Features**: 
  - Anthropic AI integration
  - OpenAI integration
  - Deepgram SDK for voice processing
  - Replicate for AI model deployment

## Project Structure

```
template-2/
├── src/
│   ├── app/              # Next.js App Router pages and API routes
│   │   ├── api/         # API endpoints for chat and Tavily integration
│   │   └── page.tsx     # Main application page
│   ├── components/      # Reusable React components
│   └── lib/            # Utility functions and configurations
│       ├── firebase/   # Firebase configuration and utilities
│       ├── contexts/   # React contexts (e.g., AuthContext)
│       └── hooks/      # Custom React hooks
├── public/             # Static assets
└── paths/              # Feature path definitions and documentation
```

## Core Features

1. **AI-Powered Search and Assistance**
   - Integration with multiple AI providers (Anthropic, OpenAI)
   - Tavily integration for enhanced search capabilities
   - Streaming responses for real-time interaction

2. **Authentication System**
   - Firebase-based authentication
   - Google Sign-In integration
   - Protected routes and user sessions

3. **File Management**
   - Image upload capabilities
   - Firebase Storage integration
   - Support for various file types (PNG, JPG, GIF)

4. **User Interface**
   - Modern, responsive design using Tailwind CSS
   - Loading states and animations
   - Error handling and user feedback
   - Suggestion system for better user experience

## Key Components

1. **Main Application (page.tsx)**
   - Career assistance interface
   - Real-time chat functionality
   - Search results display
   - Source attribution and linking
   - Thinking process visualization

2. **Authentication (AuthContext)**
   - User state management
   - Login/logout functionality
   - Session persistence

3. **Firebase Integration**
   - Document management (CRUD operations)
   - File upload functionality
   - Real-time data synchronization

4. **API Routes**
   - Chat endpoint with streaming support
   - Tavily search integration
   - Edge runtime optimization

## Development Features

1. **Type Safety**
   - Comprehensive TypeScript integration
   - Interface definitions for data structures
   - Strong typing for API responses

2. **Performance Optimization**
   - Edge runtime for API routes
   - Dynamic imports
   - Responsive image handling
   - Efficient state management

3. **Developer Experience**
   - ESLint configuration
   - PostCSS processing
   - Development server with hot reload
   - Type checking and linting

## Deployment

The application is configured for deployment on Vercel with:
- Edge runtime support
- Environment variable management
- API route optimization
- Static asset handling

## Security Considerations

1. **Authentication**
   - Secure Firebase configuration
   - Protected API routes
   - Session management

2. **Data Protection**
   - Secure file upload handling
   - API key protection
   - Environment variable security

3. **Error Handling**
   - Graceful error recovery
   - User-friendly error messages
   - Logging and monitoring

## Future Development Paths

The project includes documentation for potential feature expansions:
1. Voice Notes Integration
2. Social Media Features
3. AI Image Generation

Each path has its own requirements and implementation guidelines in the `paths/` directory.
