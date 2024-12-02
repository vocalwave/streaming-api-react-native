# HeyGen LiveKit React Native Demo

A React Native demo application showcasing real-time avatar streaming using HeyGen's Streaming API and LiveKit. This demo demonstrates how to integrate HeyGen's AI avatars with real-time video streaming capabilities in a mobile application.

[React Native Integration Guide with Streaming API + LiveKit - HeyGen Documentation](https://docs.heygen.com/docs/react-native-integration-guide-with-streaming-api-livekit)

https://github.com/user-attachments/assets/64f57ece-8229-4d02-b9a7-68fafafbf27b

## Features

- Real-time AI avatar streaming
- Text-to-speech functionality
- WebRTC video streaming using LiveKit
- React Native/Expo implementation
- iOS and Android support

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Bun](https://bun.sh/) package manager
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- iOS Simulator/Android Emulator or physical device
- [HeyGen API Key](https://app.heygen.com/settings)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/agmmnn/streaming-api-react-native
cd streaming-api-react-native

bun i
```

2. Configure API token variable:

Make sure to replace `API_CONFIG.apiKey` with your actual API key.

```ts
const API_CONFIG = {
  apiKey: "apikey",
  serverUrl: "https://api.heygen.com",
};
```

## Development

1. Create development build:

```bash
expo prebuild
```

Run on iOS:

```bash
expo run:ios
# For physical device
expo run:ios --device
```

Run on Android:

```bash
expo run:android
```

Note: This app requires a development build and cannot run in Expo Go due to native dependencies.

## Project Structure

```
├── App.tsx              # Main application component
├── app.json            # Expo configuration
├── babel.config.js     # Babel configuration
├── tsconfig.json       # TypeScript configuration
└── package.json        # Project dependencies
```

## Implementation Details

The app demonstrates:

- HeyGen Streaming API integration
- LiveKit WebRTC setup
- Real-time video streaming
- Text-to-speech functionality
- Session management
- Error handling

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Resources

- [HeyGen API Documentation](https://docs.heygen.com/)
- [LiveKit React Native Client SDK](https://github.com/livekit/client-sdk-react-native)
- [Expo Documentation](https://docs.expo.dev)

---

Built with using HeyGen API and LiveKit
