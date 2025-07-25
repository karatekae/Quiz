# Quiz Funnel Web Application

A comprehensive quiz funnel platform built with React, TypeScript, and Supabase. Create engaging interactive quizzes to capture leads and gather valuable insights from your audience.

## 🚀 Features

### Core Functionality
- **Interactive Quiz Builder**: Drag-and-drop interface for creating quizzes
- **Multiple Question Types**: Single choice, multiple choice, text input, email, phone
- **Lead Capture System**: Configurable data collection with validation
- **Real-time Analytics**: Track completion rates, popular answers, and user behavior
- **Mobile-First Design**: Responsive interface optimized for all devices

### Advanced Features
- **Progress Tracking**: Visual progress indicators and completion tracking
- **User Experience**: Smooth animations, micro-interactions, and accessibility features
- **Data Security**: GDPR-compliant data handling with row-level security
- **Performance Optimized**: Fast loading, efficient state management
- **Admin Dashboard**: Comprehensive quiz management and analytics interface

## 🛠 Tech Stack

### Frontend
- **React 18** with TypeScript for type safety
- **Tailwind CSS** for responsive, modern styling
- **React Router** for client-side routing
- **React Hook Form** with Zod validation
- **Lucide React** for icons

### Backend & Database
- **Supabase** for database, authentication, and real-time features
- **PostgreSQL** with row-level security
- **Real-time subscriptions** for live data updates

### Development Tools
- **Vite** for fast development and building
- **TypeScript** for type safety
- **ESLint** for code quality
- **PostCSS** for CSS processing

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd quiz-funnel-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Fill in your Supabase credentials:
   ```env
   VITE_SUPABASE_URL=your_supabase_project_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Set up Supabase database**
   
   Click the "Connect to Supabase" button in the top right of the application to set up your database schema automatically.

5. **Start the development server**
   ```bash
   npm run dev
   ```

## 🗄️ Database Schema

The application uses the following main tables:

### `quizzes`
- Quiz metadata, questions, and settings
- Row-level security enabled
- JSON fields for flexible question storage

### `quiz_responses`
- User submissions and answers
- Completion tracking and timing
- User information storage

### `quiz_analytics`
- Event tracking for user behavior
- Performance metrics
- Drop-off analysis

## 🎯 Usage

### Creating a Quiz

1. **Navigate to Admin Dashboard**
   - Go to `/admin` to access the quiz management interface

2. **Create New Quiz**
   - Click "Create Quiz" to start the quiz builder
   - Follow the step-by-step process:
     - Basic Info: Title and description
     - Questions: Add and configure questions
     - Settings: Lead capture and behavior settings
     - Preview: Review before publishing

3. **Configure Questions**
   - Choose from multiple question types
   - Set validation rules and requirements
   - Reorder questions with drag-and-drop

4. **Set Up Lead Capture**
   - Configure which information to collect
   - Set required vs optional fields
   - Customize thank you messages

5. **Publish and Share**
   - Activate the quiz to make it live
   - Share the quiz URL or embed code
   - Monitor analytics in real-time

### Taking a Quiz

1. **Access Quiz**
   - Visit the quiz URL: `/quiz/{quiz-id}`
   - Mobile-optimized interface loads automatically

2. **Complete Questions**
   - Progress through questions with navigation
   - Real-time validation and error handling
   - Save progress automatically

3. **Submit Information**
   - Provide contact details if required
   - Review and submit responses
   - View personalized thank you page

## 📊 Analytics & Insights

### Available Metrics
- **Completion Rates**: Track how many users finish the quiz
- **Popular Answers**: See which options are selected most
- **Time Analytics**: Monitor completion times and engagement
- **Drop-off Points**: Identify where users abandon the quiz
- **User Behavior**: Detailed event tracking and user journeys

### Viewing Analytics
1. Go to the Admin Dashboard
2. Select a quiz and click "Analytics"
3. View real-time metrics and insights
4. Export data for further analysis

## 🔒 Security & Privacy

### Data Protection
- **Row-Level Security**: Database-level access controls
- **Input Validation**: Comprehensive sanitization and validation
- **GDPR Compliance**: Privacy controls and data retention policies
- **Secure Transmission**: HTTPS and encrypted data transfer

### Privacy Features
- User consent management
- Data anonymization options
- Configurable data retention
- Privacy policy integration

## 🎨 Customization

### Styling
- Tailwind CSS for easy customization
- CSS custom properties for theming
- Responsive breakpoints for all devices
- Dark mode support (configurable)

### Branding
- Custom color schemes
- Logo and brand integration
- Customizable thank you pages
- White-label options

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to Netlify
1. Connect your repository to Netlify
2. Set environment variables in Netlify dashboard
3. Deploy automatically on push to main branch

### Environment Variables for Production
```env
VITE_SUPABASE_URL=your_production_supabase_url
VITE_SUPABASE_ANON_KEY=your_production_anon_key
```

## 🧪 Testing

### Running Tests
```bash
npm run test
```

### Test Coverage
- Unit tests for utilities and validation
- Integration tests for API functions
- Component testing with React Testing Library
- End-to-end testing with Playwright

## 📈 Performance

### Optimization Features
- Code splitting and lazy loading
- Image optimization and compression
- Efficient state management
- Minimal bundle size
- Fast loading times

### Monitoring
- Performance tracking built-in
- Error boundary implementation
- Analytics for user experience
- Real-time performance metrics

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests for new functionality
5. Submit a pull request

### Development Guidelines
- Follow TypeScript best practices
- Use semantic commit messages
- Maintain test coverage above 80%
- Follow the existing code style

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

### Getting Help
- Check the documentation in `/docs`
- Search existing issues on GitHub
- Create a new issue for bugs or feature requests
- Join our community Discord for discussions

### Common Issues
- **Supabase Connection**: Ensure environment variables are set correctly
- **Build Errors**: Clear node_modules and reinstall dependencies
- **Styling Issues**: Check Tailwind CSS configuration

## 🔄 Updates

### Version History
- **v1.0.0**: Initial release with core functionality
- **v1.1.0**: Added advanced analytics and mobile optimization
- **v1.2.0**: Enhanced security and GDPR compliance features

### Roadmap
- [ ] Advanced question types (rating scales, file uploads)
- [ ] Integration with popular marketing tools
- [ ] A/B testing capabilities
- [ ] Advanced reporting and dashboards
- [ ] Multi-language support

---

Built with ❤️ using React, TypeScript, and Supabase.#   Q u i z  
 