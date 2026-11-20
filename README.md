# KNPlayer

A Swift package / SDK for media playback in iOS and macOS applications.

## Requirements

- Swift 6.0+
- Xcode 16.0+
- iOS 13.0+ / macOS 12.0+ (or any platform supported by Swift)

---

## Installation

### Via Xcode (Swift Package Manager)

1. In Xcode, open your project.
2. Navigate to **File > Add Package Dependencies...** (or select your Project > **Package Dependencies** tab).
3. In the search bar at the top right, enter the repository URL:
   ```text
   https://github.com/karanjaiswalOfficial/KNPlayer.git
   ```
4. Under **Dependency Rule**, select **Up to Next Major Version** starting from `1.0.0` (or select the `main` branch).
5. Click **Add Package** and link `KNPlayer` to your app target.

---

### Via `Package.swift`

Add `KNPlayer` to your package dependencies:

```swift
dependencies: [
    .package(url: "https://github.com/karanjaiswalOfficial/KNPlayer.git", from: "1.0.0")
]
```

And add it to your target's dependencies:

```swift
.target(
    name: "MyApp",
    dependencies: [
        .product(name: "KNPlayer", package: "KNPlayer")
    ]
)
```

---

## Usage

```swift
import KNPlayer

// Example usage
hello()
```

---

## License

MIT License.
