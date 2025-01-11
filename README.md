# Voice_Assistant_App_ReactNative 🎤🤖

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Key Features](#features)
  - [File Structure](#file-structure)
  - [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The **Voice Assistant App** built with **React Native** integrates cutting-edge AI technology, including **ChatGPT** for natural language responses and **DALL-E** for AI-generated image creation. This mobile app allows users to interact with a voice assistant that can respond to queries in real-time with AI-generated responses. Additionally, users can request AI-generated images based on text prompts, making the app an interactive and engaging experience.

### The challenge
The goal of this project was to create a voice-enabled mobile assistant app with the following functionalities:
- **Voice Interaction:** Users can speak to the assistant and receive voice responses.
- **Real-time Responses:** AI-powered responses to any queries using ChatGPT.
- **AI Image Generation:** Integration of DALL-E for generating custom images based on user input.
- **Cross-platform Compatibility:** The app works seamlessly on both iOS and Android.

### Features
- **Voice Commands:** Speak to the app and get real-time spoken responses using text-to-speech technology.
- **ChatGPT Integration:** Fetch dynamic responses to user queries using OpenAI’s ChatGPT.
- **DALL-E Integration:** Request AI-generated images based on descriptive prompts (e.g., “Create an image of a sunset over a mountain”).
- **Cross-platform App:** Developed with **React Native** for both iOS and Android platforms.
- **Intuitive User Interface:** A simple and clean interface for smooth interactions.
- **Speech Recognition:** Converts user speech to text to process queries effectively.
- **Real-time Updates:** Both text responses and images are generated dynamically, providing real-time interaction.

### File Structure
```
/root-directory
|-- assets/                       # Images, icons, and other static assets
|-- components/                   # React Native components (voice input, image display)
|-- services/                     # API calls and logic (ChatGPT, DALL-E integration)
|-- App.js                         # Main app file to configure routes and navigation
|-- package.json                  # Project dependencies and configuration
|-- README.md                     # Project description and instructions
|-- android/                      # Android-specific code and resources
|-- ios/                          # iOS-specific code and resources
|-- .gitignore                    # Git ignore rules for the project
```

### Technologies Used
- **React Native** for building a cross-platform mobile app.
- **OpenAI's ChatGPT** for natural language processing and generating text-based responses.
- **DALL-E** for generating AI-based images from text prompts.
- **React Native Voice** for speech recognition and voice interaction.
- **Text-to-Speech** (TTS) technology to read out the responses to users.
- **Axios/Fetch** for making API calls to OpenAI and DALL-E.

## Setup Instructions

### Prerequisites
- Node.js (preferably the latest stable version)
- React Native CLI or Expo (if using Expo for simpler setup)
- Android Studio (for Android app development) or Xcode (for iOS app development)
- Access to OpenAI API keys for both **ChatGPT** and **DALL-E**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/voice_assistant_app_reactnative.git
   ```
2. Navigate to the project directory:
   ```bash
   cd voice_assistant_app_reactnative
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables for API keys:
   - Create a `.env` file in the root directory and add your OpenAI API keys for ChatGPT and DALL-E:
     ```
     OPENAI_API_KEY=your_api_key_here
     DALL_E_API_KEY=your_api_key_here
     ```
5. Run the app on a simulator or physical device:
   - For iOS:
     ```bash
     npx react-native run-ios
     ```
   - For Android:
     ```bash
     npx react-native run-android
     ```

### Usage
1. **Voice Interaction:** Users can press a button to activate the voice assistant. The assistant will listen to voice queries and provide real-time spoken responses.
2. **AI Image Generation:** Users can ask for images by describing them (e.g., "Show me a futuristic cityscape"), and DALL-E will generate the image in real-time.
3. **Real-time AI Responses:** The chatbot (powered by ChatGPT) responds to user questions, provides recommendations, or engages in general conversation.

### Future Improvements
- **Enhanced Voice Interaction:** Incorporate more advanced speech recognition capabilities, such as continuous conversation tracking.
- **Personalized Responses:** Use user data to personalize responses (e.g., remember past interactions, user preferences).
- **Offline Functionality:** Implement local storage and caching for responses and images so the app can work offline.
- **Multi-language Support:** Add support for different languages in both voice interaction and text responses.
- **Image Gallery:** Allow users to save and view generated images in a gallery.

### Useful resources

- [React Native Documentation](https://reactnative.dev/docs/getting-started) - The official React Native documentation.
- [OpenAI Documentation](https://beta.openai.com/docs/) - Documentation for OpenAI’s API, including ChatGPT and DALL-E.
- [React Native Voice](https://github.com/react-native-voice/voice) - A library for adding voice recognition to React Native apps.
- [DALL-E API Documentation](https://openai.com/dall-e) - Documentation for integrating DALL-E into your app.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

A special thanks to the teams behind **React Native**, **OpenAI**, and **DALL-E** for their incredible tools and APIs that made this project possible. A huge shout-out to the open-source community for always providing support and insightful contributions.

## Got feedback for me?

Feel free to reach out via email at saarsaach30[at]gmail[dot]com with any feedback or suggestions!

## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License📃
This project is licensed under the MIT License.

Copyright (c) 2024, Sarthak Sachdev

**Happy coding!** 😊🚀
