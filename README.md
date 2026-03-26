# 🧠 FinZen AI - Personal Financial Advisor

**AI-Powered Financial Analytics & Advisor for Gen-Z**

FinZen AI is a comprehensive Streamlit-based web application that provides intelligent financial analysis, predictive insights, and AI-powered advisory services. Built specifically for Gen-Z users, it combines transaction analysis, goal planning, predictive analytics, and voice-enabled AI conversations.

##  Features

###  Financial Dashboard
- **12-Month Transaction Overview**: Visual analysis of income, expenses, and savings patterns
- **Interactive Charts**: Plotly-powered visualizations for spending categories and trends
- **Key Metrics**: Savings rate, expense breakdown, and financial health indicators
- **Multi-language Support**: English, Hindi, and Marathi

###  Transaction Analysis
- **Deep Spending Insights**: Category-wise expense analysis with trend identification
- **Monthly Comparisons**: Track spending patterns across different months
- **Expense Optimization**: Identify areas for potential savings
- **Visual Analytics**: Heatmaps and bar charts for comprehensive analysis

###  Predictive Analytics
- **AI-Powered Forecasts**: Machine learning predictions for future expenses
- **Trend Analysis**: Identify spending patterns and predict next month's costs
- **Risk Assessment**: Financial risk evaluation based on spending behavior
- **Scenario Planning**: What-if analysis for different financial situations

###  Goal Planner
- **Financial Goal Setting**: Set and track multiple financial targets
- **Progress Tracking**: Visual progress indicators for each goal
- **Milestone Management**: Break down large goals into achievable milestones
- **Savings Calculator**: Calculate required monthly savings for goals

###  What-If Simulator
- **Scenario Analysis**: Test different financial scenarios and their impacts
- **Income Changes**: Simulate effects of salary changes or bonuses
- **Expense Modifications**: Test impact of reducing specific expenses
- **Goal Achievement**: Calculate time to achieve goals under different conditions

###  AI Financial Advisor (with Voice Features)
- **Conversational AI**: Natural language financial advice and guidance
- **Voice Input**: Speak your financial questions using browser's speech recognition
- **Voice Output**: Listen to AI responses with text-to-speech functionality
- **Quick Prompts**: Pre-built questions for common financial queries
- **Multi-language Chat**: Support for English, Hindi, and Marathi conversations

##  Voice Features

### Voice Input (Speech Recognition)
- **Browser-Native**: Uses Web Speech API (Chrome/Edge recommended)
- **Multi-language**: Supports English, Hindi, and Marathi speech input
- **Real-time Processing**: Instant conversion of speech to text
- **No Additional Setup**: Works directly in the browser

### Voice Output (Text-to-Speech)
- **AI Response Playback**: Click "🔊 Speak" button to hear AI advisor responses
- **Natural Voice**: High-quality speech synthesis with appropriate language voices
- **Rate Control**: Optimized speech rate for clear understanding
- **Browser Compatible**: Works in Chrome, Edge, Safari (limited Firefox support)

##  Installation & Setup

### Prerequisites
- Python 3.8 or higher
- Modern web browser (Chrome/Edge recommended for voice features)

### Dependencies
```bash
pip install streamlit pandas numpy plotly
```

### Required Python Packages
- `streamlit` - Web application framework
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `plotly` - Interactive visualizations

##  How to Run

1. **Navigate to the project directory**:
   ```bash
   cd path/to/finzen
   ```

2. **Install dependencies** (if not already installed):
   ```bash
   pip install streamlit pandas numpy plotly
   ```

3. **Run the application**:
   ```bash
   streamlit run demo 2.py
   ```

4. **Open your browser** and go to the URL shown (typically `http://localhost:8501`)

##  Usage Guide

### Getting Started
1. **Login**: Use the sample credentials provided on the login page
2. **Navigation**: Use the sidebar to switch between different features
3. **Language**: Select your preferred language (English/Hindi/Marathi)

### Sample Login Credentials
- **User**: arjun.sharma@email.com / arjun123
- **User**: priya.desai@email.com / priya123

### Voice Features Usage
1. **Voice Input**: Go to AI Advisor → Voice Command section → Click "🎙️ Hold to Speak"
2. **Voice Output**: In AI Advisor chat, click the "🔊 Speak" button next to any AI response

##  Project Structure

```
finzen/
├── demo 2.py                 # Main Streamlit application
├── finzen.db            # Database file (if used)
├── README.md            # This file
└── __pycache__/         # Python cache files
```

## Browser Compatibility

### Voice Features
-  **Chrome** - Full support for voice input and output
-  **Microsoft Edge** - Full support for voice input and output
-  **Safari** - Voice output supported, voice input limited
-  **Firefox** - Limited support for voice features

### General Application
-  All modern browsers with JavaScript enabled

##  Technical Details

### Built With
- **Frontend**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly
- **Voice Technology**: Web Speech API (browser-native)
- **Styling**: Custom CSS with Google Fonts

### Key Technologies
- **Streamlit Components**: For voice functionality integration
- **Web Speech API**: Browser-native speech recognition and synthesis
- **Plotly Subplots**: Advanced chart layouts and interactions
- **Session State Management**: Streamlit's built-in state management

##  Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

##  License

This project is licensed under the MIT License - see the LICENSE file for details.

##  Acknowledgments

- Built for Gen-Z financial literacy and empowerment
- Uses open-source libraries and browser-native APIs
- Inspired by the need for accessible financial tools

## Support

For questions or issues:
- Check the voice feature compatibility with your browser
- Ensure all Python dependencies are installed
- Try refreshing the page if voice features don't work

---

**Made with ❤️ for financial wellness and AI-powered insights**
