# Simple-richText
Simple richText helps you understand UITextView.
# The first part
![IMG_0045](https://github.com/S-way520/Simple-richText/assets/95877651/64f1dc5f-ca4e-4860-b978-0a383ba192d6)
# The second part
Code file 1
```swift
import SwiftUI
@main
struct MyApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```
Code file 2
```swift
import SwiftUI
struct ContentView: View {
    var body: some View {
        VStack {
            Text("Hello ") 
                .font(.largeTitle)
            + Text(
                Image(systemName: "star")
            ) 
            + Text(" World!")
        }
    }
}
```
