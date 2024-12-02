# HeyGen LiveKit React Native Demo

A React Native demo application showcasing real-time avatar streaming using HeyGen's Streaming API and LiveKit. This demo demonstrates how to integrate HeyGen's AI avatars with real-time video streaming capabilities in a mobile application.

![HeyGen LiveKit Demo](screenshot.png)

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
git clone https://github.com/yourusername/heygen-livekit-react-native-demo.git
cd heygen-livekit-react-native-demo
```

2. Install dependencies:

```bash
bun install
```

3. Configure environment variables:
   Create a `.env` file in the project root and add your HeyGen API key:

```env
HEYGEN_API_KEY=your_api_key_here
```

## Development

1. Create development build:

```bash
expo prebuild
```

2. Run on iOS:

```bash
expo run:ios
# For physical device
expo run:ios --device
```

3. Run on Android:

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

For detailed implementation guide, see [GUIDE.md](GUIDE.md).

## Troubleshooting

### Common Issues

1. **Build Errors**

   - Ensure all dependencies are installed
   - Clean build folders and rebuild
   - Verify Expo configuration

2. **Video Not Showing**

   - Check HeyGen API key
   - Verify network connection
   - Ensure proper permissions

3. **Device Compatibility**
   - Use physical device or simulator with WebRTC support
   - Enable camera and microphone permissions
   - Verify device compatibility with WebRTC

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

## Support

For support, please refer to:

- [HeyGen Support](https://support.heygen.com)
- [Project Issues](https://github.com/yourusername/heygen-livekit-react-native-demo/issues)

---

Built with using HeyGen API and LiveKit
