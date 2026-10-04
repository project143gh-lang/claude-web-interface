# Claude Web Interface

A web-based interface for interacting with Claude AI. Beautiful, responsive, and easy to deploy with minimal configuration.

## 📸 Screenshot

![Claude Web Interface Repository](./claude-web-interface.png)

**Start chatting:** Open `index.html` in any modern browser.

## Features

### 💬 Chat Experience
- **Real-time messaging**: Send and receive messages from Claude AI
- **Clean interface**: Minimalist design focused on conversation
- **Responsive layout**: Works on mobile, tablet, and desktop
- **Message persistence**: Chat history stored in localStorage

### 🎨 Design Elements
- **Modern typography**: Care-selected fonts for readability
- **Color palette**: Soft, conversation-friendly colors
- **Message bubbles**: Distinct styling for user vs. AI messages
- **Typing indicator**: Animated "Claude is typing" indicator

### ⚙️ Functionality
- **Session management**: Multiple chat sessions
- **Export chat**: Download conversation as text file
- **Clear chat**: Start new conversation
- **Keyboard shortcuts**: Quick navigation and sending

### 📱 Accessibility
- **Keyboard navigation**: Tab through elements, Enter to send
- **Screen reader friendly**: Semantic HTML structure
- **High contrast mode**: Optional for accessibility
- **Focus indicators**: Clear focus states for all interactive elements

## 🚀 Quick Start

```bash
# Option 1: Open directly in browser
open index.html

# Option 2: Serve with static server
npx serve .

# Option 3: Local development
# 1. Open index.html in any modern browser
# 2. No installation required - pure HTML/CSS/JS
```

## 🛠️ Project Structure

```
claude/
├── index.html          # Main chat interface (HTML5 + CSS + JS)
├── index.js            # Client-side logic and API calls
└── styles.css          # Visual styling and responsive design
```

## 📁 File Details

### `index.html`
- HTML5 document structure
- Meta tags for responsiveness
- Link to styles.css and icons
- Chat container and message form
- Embedded CSS for critical styles

### `index.js`
- Fetch API integration with Claude endpoint
- Message rendering logic
- Form handling and submission
- Session management
- LocalStorage for chat history

### `styles.css`
- CSS variables for theming
- Responsive grid system
- Animation keyframes
- Print-friendly styles
- Accessibility improvements

## 🔧 Customization

### Change Claude's Appearance
Edit `styles.css` to:
- Modify color scheme
- Adjust typography
- Change message bubble styles
- Add animations

### Modify Behavior
Edit `index.js` to:
- Change API endpoints
- Add new features
- Modify chat flow
- Add keyboard shortcuts

### Add New Features
- Message formatting
- Image attachment
- File sharing
- Voice input (planned)

## 📜 License

MIT

---

**K.bhalavardt, MIT Student**