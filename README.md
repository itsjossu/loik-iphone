# Loik 0.2 for iPhone

Native SwiftUI video highlight editor for iOS 17+. English glass interface, persistent projects, batch clips, calculated highlight ratings, local speech captions, optional headlines, 9:16 / 1:1 / 16:9 / 4:5 export, preview and bulk save/share. No paid API, subscription or watermark.

The complete Xcode project and Estonian setup guide are in **Loik-iPhone.zip**. Extract it to open `Loik-iPhone/Loik.xcodeproj` on a Mac. The manual GitHub Actions workflow extracts the same source archive, runs XCTest on an iPhone simulator, then compiles an unsigned device IPA.

Highlights are ranked across the full source using transcript hooks, pace, lexical variety, speech boundaries and audio RMS activity. The rating is an editorial heuristic, not a trained virality prediction. Speech support depends on language and device; audio-only fallback is labeled. Center cropping does not track speakers. Unsigned IPA requires signing with your own Apple account before installation.

The CI screenshot previews use explicitly labeled sample cards for layout inspection. Normal launches start with the user's own local library. Tests include actual AVFoundation MP4 exports with trimming, aspect conversion and burned-in text.

Builds are manual and restricted to public repositories on standard GitHub-hosted runners. No Apple credentials are used in the build.
