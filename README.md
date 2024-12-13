# Chat Application

This repository contains the source code for a web-based chat application. The application allows users to send messages, toggle between light and dark themes, and view chatbot-generated responses. User chats are stored in local storage for persistence.

## Features

- **Real-time Chat:** Users can send messages and receive chatbot responses.
- **Light/Dark Mode:** Toggle between light and dark themes.
- **Suggestions:** Quick responses using predefined suggestions.
- **Local Storage Support:** Chats are saved locally for future sessions.
- **Copy Messages:** Easily copy messages to the clipboard.
- **Clear Chat:** Delete all chats with a single click.

## Technology Stack

- **HTML5, CSS3, JavaScript:** For building the user interface and functionality.
- **Fetch API:** For making HTTP requests to the chatbot API.
- **LocalStorage:** For persisting chat data and theme preferences.

## Prerequisites

Ensure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Edge).

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chat-application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-application
   ```

3. Open `index.html` in your web browser.

## Usage

### Sending Messages

1. Type your message in the input field and press **Enter** or click the send button.
2. The chatbot will respond with an animated typing effect.

### Using Suggestions

1. Click on a predefined suggestion to send it as a message.

### Toggle Theme

1. Click the theme button to switch between light and dark modes.

### Delete Chats

1. Click the delete button to clear all messages. Confirm the action in the dialog box.

### Copy Messages

1. Click the copy icon next to a message to copy it to the clipboard.

## File Structure

```
├── index.html      # Main HTML file
├── style.css       # Styles for the application
├── script.js       # Main JavaScript file
├── images/         # Contains avatars and icons
└── README.md       # Project documentation
```

## API Integration

The chatbot uses the Gemini API for generating responses. Update the `API_Key` variable in `script.js` with your API key.

```javascript
const API_Key = "your-api-key";
```

### API Endpoint

```
https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=YOUR_API_KEY
```

## Contributing

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add feature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Create a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Google Gemini API](https://cloud.google.com/generative-language) for powering chatbot responses.
- All contributors for improving and maintaining this project.
