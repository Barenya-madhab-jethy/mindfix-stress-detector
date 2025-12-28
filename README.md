MINDFIX - STRESS PATTERN DETECTOR
==================================

A privacy-first, offline web application that helps you track, analyze, and manage stress through daily check-ins and pattern detection.

FEATURES
--------
1. Daily Mental Health Check-in
   - Mood level tracking (1-5 slider)
   - Sleep quality monitoring
   - Study pressure assessment
   - Screen time tracking
   - Stress trigger identification
   - Optional notes field

2. Stress Score Calculator
   - Rule-based stress scoring (0-100)
   - Three stress levels: Calm, Moderate, High
   - Visual stress meter

3. Trend Visualization
   - Line graph showing stress over time
   - Calendar heatmap for monthly overview
   - Customizable time ranges

4. Pattern Detection
   - Identifies stress patterns without AI
   - Detects correlations (e.g., poor sleep → high stress)
   - Finds stress peaks on specific days
   - Identifies continuous high-stress streaks

5. Stress Management Tools
   - Focus & Break Timer (Pomodoro technique)
   - Guided breathing exercise with animation
   - Personalized coping tips based on stress level

6. Weekly Reports & Goals
   - Weekly stress statistics
   - Personal progress goals
   - Reflection journal
   - Smart alerts and notifications

7. Privacy-First Design
   - No login required
   - All data stored locally (LocalStorage)
   - No data sent to servers
   - 100% offline functionality

TECHNOLOGY
----------
- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript (No frameworks)
- LocalStorage for data persistence
- Chart.js for data visualization (CDN)

INSTALLATION & USAGE
--------------------
1. Simply open index.html in any modern web browser
2. No installation or setup required
3. All data is automatically saved to your browser

DATA STORAGE
------------
- Daily check-in entries
- Journal entries
- Application settings
- All data is stored in browser's LocalStorage
- Data can be exported/imported via JSON files

PRIVACY
-------
- No user accounts or login
- No data collection or analytics
- No third-party tracking
- All processing happens locally in your browser
- You control your data - can export or delete anytime

KEY FUNCTIONALITIES
-------------------
1. Daily Check-in Form: Tracks mental health metrics
2. Stress Calculation: Converts inputs to a stress score (0-100)
3. Trend Analysis: Visualizes stress patterns over time
4. Pattern Detection: Identifies stress triggers and correlations
5. Coping Tools: Timer and breathing exercises
6. Progress Tracking: Goals and weekly reports
7. Dark Mode: Reduces eye strain

FILE STRUCTURE
--------------
mindfix/
├── index.html          # Main HTML file
├── style.css           # All styling
├── script.js           # All JavaScript logic
├── README.txt          # This file
└── assets/             # Optional assets folder
    ├── icons/          # Icon files
    └── fonts/          # Custom fonts

HOW STRESS SCORE IS CALCULATED
------------------------------
Based on rule-based scoring:
- Low mood (1-2): +30 points
- Poor sleep: +20 points
- High study pressure: +25 points
- High screen time: +15 points
- Each stress trigger: +10 points

Stress Levels:
- 0-30: Calm (Green)
- 31-60: Moderate (Yellow)
- 61-100: High (Red)

BROWSER COMPATIBILITY
---------------------
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Opera 50+

Any modern browser with JavaScript enabled should work perfectly.

LIMITATIONS
-----------
- Data is browser-specific (won't sync across devices)
- Limited by browser storage capacity (~5-10MB)
- No cloud backup (export data regularly)
- Works offline but initial load requires internet for Chart.js CDN

FUTURE ENHANCEMENTS (POSSIBLE)
------------------------------
- PWA (Progressive Web App) support
- Data export to PDF
- More visualization options
- Additional pattern detection rules
- Customizable stress scoring

CONTRIBUTING
------------
This is a frontend-only project. Feel free to modify and enhance:
1. Fork the project
2. Add new features
3. Improve UI/UX
4. Submit pull requests

LICENSE
-------
Free to use for personal or educational purposes.

CREDITS
-------
- Icons: Font Awesome (CDN)
- Charts: Chart.js (CDN)
- Design: Custom CSS with modern gradients
- Concept: Mental health tracking without AI/ML

SUPPORT
-------
For issues or suggestions:
1. Check browser console for errors
2. Clear browser cache if needed
3. Ensure JavaScript is enabled

Remember: This tool is for self-awareness and should not replace professional mental health advice.
