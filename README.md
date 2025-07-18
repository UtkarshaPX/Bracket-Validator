# 🔗 Bracket Validator Visualizer

A beautiful, interactive web application that visualizes the stack-based algorithm for validating bracket sequences. Perfect for learning data structures and algorithms with real-time animations and step-by-step execution.

## ✨ Features

### 🎯 Core Functionality
- **Real-time Validation**: Instantly validate bracket sequences with visual feedback
- **Stack Visualization**: Watch the stack grow and shrink with animated elements
- **Step-by-step Execution**: See each operation as it happens
- **Pause/Resume Control**: Pause validation at any point and resume seamlessly
- **Speed Control**: Adjust animation speed from very slow to very fast
- **Progress Tracking**: Visual progress bar and operation counter

### 🎨 User Interface
- **Modern Glass Design**: Beautiful glassmorphism UI with gradient backgrounds
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, animations, and smooth transitions
- **Color-coded Brackets**: Different colors for different bracket types
- **Real-time Highlighting**: Current character and stack operations highlighted

### 🛠️ Developer Features
- **Algorithm Explanation**: Built-in educational content about the stack algorithm
- **Performance Metrics**: Processing time and operation count tracking
- **Error Handling**: Detailed error messages and validation feedback
- **Quick Insert**: One-click bracket pair insertion
- **Example Loader**: Pre-built test cases for quick testing

## 🚀 Demo

### Valid Expression Example
\`\`\`
Input: {[()]}[({})]
Result: ✅ Valid - All brackets properly matched
\`\`\`

### Invalid Expression Example
\`\`\`
Input: {[}]
Result: ❌ Invalid - Mismatched brackets detected
\`\`\`

## 📋 Algorithm Overview

The application implements the classic **Stack-based Bracket Validation Algorithm**:

1. **Initialize** an empty stack
2. **Iterate** through each character in the input
3. **Push** opening brackets `(`, `[`, `{` onto the stack
4. **Pop and Match** closing brackets `)`, `]`, `}` with stack top
5. **Validate** that stack is empty at the end

### Complexity Analysis
- **Time Complexity**: O(n) - Single pass through input
- **Space Complexity**: O(n) - Stack storage in worst case
- **Data Structure**: Stack (LIFO - Last In, First Out)

## 🎮 How to Use

### Basic Usage
1. **Enter Expression**: Type or paste your bracket sequence in the input field
2. **Start Validation**: Click "🚀 Validate & Visualize"
3. **Watch Animation**: Observe the step-by-step validation process
4. **View Results**: Check the final validation result and statistics

### Advanced Controls
- **⏸️ Pause**: Pause validation at any step
- **▶️ Resume**: Continue from where you paused
- **⏹️ Stop**: Completely stop the current validation
- **🗑️ Clear**: Reset everything and start fresh
- **💡 Load Example**: Try pre-built test cases

### Speed Control
Adjust the animation speed using the slider:
- **Very Slow** (2000ms delay) - Perfect for learning
- **Slow** (1500ms delay) - Detailed observation
- **Normal** (1000ms delay) - Balanced speed
- **Fast** (500ms delay) - Quick validation
- **Very Fast** (250ms delay) - Rapid testing

## 🛠️ Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start validating brackets immediately!

### Option 2: Clone Repository
\`\`\`bash
git clone https://github.com/UtkarshaPX/bracket-validator-visualizer.git
cd bracket-validator-visualizer
\`\`\`

### Option 3: GitHub Pages
Simply open the file in your browser - no server required!

## 🎓 Educational Value

Perfect for:
- **Computer Science Students** learning data structures
- **Coding Interview Preparation** - common algorithm question
- **Algorithm Visualization** - understanding stack operations
- **Teaching Tool** - demonstrate LIFO principle
- **Self-Learning** - interactive algorithm exploration

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern styling with animations
- **JavaScript (ES6+)**: Interactive functionality and algorithms
- **Tailwind CSS**: Utility-first CSS framework
- **Custom Animations**: Smooth transitions and effects

### Key Components
\`\`\`javascript
// Core validation function
async function visualizeValidation(expression)

// Stack operations with animation
function updateStackDisplay()

// Pause/Resume functionality
function togglePauseResume()

// Real-time expression highlighting
function displayExpression(expression, currentIndex, highlightType)
\`\`\`

## 🏆 Use Cases

### Educational
- **Classroom Demonstrations**: Visual teaching aid for stack concepts
- **Homework Helper**: Understand bracket validation algorithms
- **Coding Bootcamps**: Interactive learning tool

### Professional
- **Interview Preparation**: Practice common algorithm questions
- **Code Review**: Validate bracket sequences in code
- **Debugging**: Identify bracket mismatches quickly

### Personal
- **Learning**: Understand data structures visually
- **Testing**: Validate complex nested expressions
- **Fun**: Enjoy the satisfying animations!

## 📞 Support

If you found this project helpful, please:
- ⭐ Star this repository
- 🐛 Report bugs via GitHub Issues
- 💡 Suggest features and improvements
- 🔄 Share with others who might find it useful

---
