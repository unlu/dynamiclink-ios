# ``dynamiclink.io iOS SDK``

## SwiftUI
```SwiftUI
.onOpenURL { url in
    Task {
       let deepLink = try await DynamicLink.getDeepLink(url: url)
    }
}
