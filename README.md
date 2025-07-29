# 🌟 LumaMind - AI-Powered Mental Health Companion

> **"Let your light return"** ✨

LumaMind is a comprehensive AI-powered mental health and wellness app designed to understand the silence, celebrate the little wins, and hold users gently when no one else does.

## 🚀 Features

### 🧠 **AI-Driven Mood Detection**
- **Sentiment Analysis**: NLP analysis of journal entries for emotional tone
- **Mood Patterns**: Visual mood graphs showing trends over time
- **AI Insights**: Personalized recommendations based on emotional patterns
- **Progress Tracking**: Streak tracking and mood statistics

### 🤖 **AI Therapist (24/7 Companion)**
- **CBT-Based Responses**: Cognitive Behavioral Therapy techniques
- **Emotional Validation**: Compassionate, non-judgmental support
- **Quick Prompts**: Pre-written prompts for common concerns
- **Therapeutic Techniques**: Grounding exercises and coping strategies

### 📝 **Creative Journaling**
- **Multi-Modal Entries**: Text, voice, and drawing support
- **AI Sentiment Analysis**: Real-time emotional insights
- **Mood-Based Themes**: Color themes that match your emotional state
- **Privacy-First**: All data stored locally on your device

### 🧩 **Brain-Boosting Games**
- **Memory Match**: Card matching game to improve memory
- **Focus Builder**: Color-targeting game for concentration
- **Reaction Time**: Speed and reflex training
- **Progress Analytics**: Track improvement over time

### 🫂 **Emergency Support**
- **Crisis Hotlines**: Direct access to 988, Crisis Text Line, 911
- **Grounding Exercises**: 5-4-3-2-1, Deep Breathing, Body Scan
- **Safety Planning**: Step-by-step crisis intervention
- **Coping Statements**: Encouraging reminders and affirmations

### 🎨 **Beautiful UI/UX**
- **Calming Design**: Indigo/purple color scheme
- **Dark/Light Mode**: Automatic theme switching
- **Accessibility**: Mental health-focused design principles
- **Smooth Animations**: Non-triggering, gentle interactions

## 🛠️ Tech Stack

- **Frontend**: React Native with Expo
- **Navigation**: Expo Router (file-based routing)
- **State Management**: React Context API
- **Storage**: AsyncStorage for local data persistence
- **Charts**: react-native-chart-kit for mood analytics
- **Styling**: Custom StyleSheet with dynamic theming
- **Icons**: Expo Vector Icons (Ionicons)

## 📱 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- Expo Go app (for mobile testing)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/lumamind.git
   cd lumamind
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Run on your device**
   - Scan the QR code with Expo Go (Android)
   - Scan the QR code with Camera app (iOS)
   - Press 'w' for web version
   - Press 'a' for Android simulator
   - Press 'i' for iOS simulator

## 🎯 Demo Walkthrough

### 1. **Onboarding Experience**
- Welcome screens introducing features
- Name input for personalization
- Privacy-focused setup

### 2. **Home Dashboard**
- Personalized greeting based on time of day
- Current mood display with emoji
- Quick action buttons (Check In, Journal, Talk)
- Mood statistics and AI insights
- Feature grid with navigation

### 3. **Mood Tracker**
- 5 mood options with emojis (Happy, Calm, Neutral, Sad, Anxious)
- Intensity slider (1-10 scale)
- Optional notes with AI sentiment analysis
- 7-day mood trend chart
- Progress statistics

### 4. **AI Therapist**
- Welcome message and therapeutic responses
- Keyword-based AI responses (anxiety, stress, gratitude, etc.)
- Quick prompt buttons for common concerns
- Simulated typing indicator
- Chat interface with timestamps

### 5. **Creative Journal**
- Title and content input fields
- Mood selection for entries
- Voice recording and drawing placeholders
- AI sentiment analysis with emotions and suggestions
- Previous entries with insights

### 6. **Brain Games**
- Memory Match: 16-card matching game
- Focus Builder: Color-targeting game
- Reaction Time: Tap-when-green game
- Score tracking and best scores
- Game statistics

### 7. **Emergency Support**
- Direct call buttons for crisis hotlines
- Interactive deep breathing exercise
- Grounding exercise list
- Coping statements and affirmations
- Safety planning guidance

## 🔧 Project Structure

```
lumamind/
├── app/                    # Expo Router pages
│   ├── (tabs)/            # Tab navigation screens
│   │   ├── index.tsx      # Home dashboard
│   │   ├── mood-tracker.tsx
│   │   ├── ai-therapist.tsx
│   │   ├── journal.tsx
│   │   └── games.tsx
│   ├── emergency.tsx      # Emergency support
│   ├── onboarding.tsx     # Onboarding flow
│   └── _layout.tsx        # Root layout
├── context/               # React Context providers
│   ├── AuthContext.tsx    # User authentication
│   ├── MoodContext.tsx    # Mood data management
│   └── ThemeContext.tsx   # Theme management
├── components/            # Reusable components
├── assets/               # Images, fonts, etc.
└── package.json          # Dependencies and scripts
```

## 🎨 Design Philosophy

LumaMind is built with mental health accessibility in mind:

- **Calming Colors**: Indigo and purple palette for tranquility
- **Gentle Interactions**: Smooth, non-triggering animations
- **Privacy-First**: Local data storage, no account required
- **Inclusive Design**: Accessible to users with various needs
- **Crisis-Aware**: Emergency resources always accessible

## 🔒 Privacy & Security

- **Local Storage**: All data stored on device using AsyncStorage
- **No Server Data**: No user data sent to external servers
- **Optional Sharing**: Users control what they share
- **Crisis Resources**: Direct access to professional help

## 🚀 Future Enhancements

- [ ] Real AI integration (OpenAI, HuggingFace)
- [ ] Voice-to-text journaling
- [ ] Drawing canvas for emotional expression
- [ ] Community support pods
- [ ] Personalized daily healing plans
- [ ] AI-powered motivational podcasts
- [ ] Mirror coaching with camera
- [ ] Progress garden gamification
- [ ] Offline mode enhancements
- [ ] Push notifications for check-ins

## 🤝 Contributing

We welcome contributions! Please read our contributing guidelines and code of conduct.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Crisis Resources

If you or someone you know is in crisis:

- **National Suicide Prevention Lifeline**: 988
- **Crisis Text Line**: Text HOME to 741741
- **Emergency Services**: 911

**Remember**: This app is a supportive tool, not a replacement for professional mental health care.

## 🙏 Acknowledgments

- Built with love for mental health awareness
- Inspired by the need for accessible mental health support
- Thanks to the React Native and Expo communities
- Special thanks to all mental health advocates

---

**Let your light return with LumaMind! ✨💙**

*"An app that understands the silence, celebrates the little wins, and holds you gently when no one else does."*
