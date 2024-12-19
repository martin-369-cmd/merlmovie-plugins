# MerlMovie Plugin App

MerlMovie Plugin App is a powerful and flexible solution designed to enhance the functionality of your movie streaming or metadata-driven applications. This plugin enables seamless handling of URLs, metadata interpretation, and dynamic content presentation.

---

## Features

- **Metadata-Driven Content Handling:**
  - Analyze and interpret JSON metadata to handle URLs efficiently.
  - Decide dynamically whether to open web content in a web view or play videos in the built-in player.

- **Stream Type Support:**
  - Automatically detect and process URLs based on their `stream_type`.
  - Trigger built-in video player for a streamlined user experience when `stream_type` is set to `api`.

- **Seamless Integration:**
  - Easy to integrate into your existing apps.
  - Customizable to suit various user needs and application requirements.

---

## Installation

1. Add the package to your `pubspec.yaml`:
   ```yaml
   dependencies:
     merlmovie_plugin: latest_version
   ```
2. Run `flutter pub get` to fetch the package.
3. Import the package in your Dart file:
   ```dart
   import 'package:merlmovie_plugin/merlmovie_plugin.dart';
   ```

---

## Usage

### Example Code

```dart
import 'package:merlmovie_plugin/merlmovie_plugin.dart';

void main() {
  final metadata = {
    "stream_type": "api",
    "url": "https://example.com/stream.m3u8"
  };

  MerlMoviePlugin.handleMetadata(metadata);
}
```

For more detailed examples and documentation, visit the [MerlMovie Plugin Documentation](https://github.com/merlmovie/merlmovie-plugin).

---

## Contributing

We welcome contributions! Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Submit a pull request.

For more information, check our [Contributing Guidelines](https://github.com/merlmovie/merlmovie-plugin/blob/main/CONTRIBUTING.md).

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/merlmovie/merlmovie-plugin/blob/main/LICENSE) file for details.

---

## Support

If you encounter any issues or have questions, feel free to:

- Open an issue on our [GitHub repository](https://github.com/merlmovie/merlmovie-plugin/issues).
- Contact us via email at [support@merlmovie.com](mailto:support@merlmovie.com).

---

## Links

- [Documentation](https://github.com/merlmovie/merlmovie-plugin)
- [GitHub Repository](https://github.com/merlmovie/merlmovie-plugin)
- [Report an Issue](https://github.com/merlmovie/merlmovie-plugin/issues)

---

Thank you for using the MerlMovie Plugin App! Your feedback and support make this project better.
