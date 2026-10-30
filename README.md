# Lõik for iPhone

Native SwiftUI video clip editor for iOS 17+. Video import, trim, centered 9:16 crop, editable local speech captions and MP4 export. No paid API, subscription or watermark.

The complete Xcode project and Estonian setup guide are in **Loik-iPhone.zip**. Extract it to open `Loik-iPhone/Loik.xcodeproj` on a Mac. The manual GitHub Actions workflow extracts the same source archive, runs XCTest on an iPhone simulator, then compiles an unsigned device IPA.

This is an early version, not an OpusClip clone. Semantic highlight selection, speaker tracking and persistent projects are not implemented. On-device speech support depends on language and device; Estonian support is not guaranteed. Unsigned IPA requires signing with your own Apple account before installation.

Builds are manual and restricted to public repositories on standard GitHub-hosted runners. No Apple credentials are used in the build.
