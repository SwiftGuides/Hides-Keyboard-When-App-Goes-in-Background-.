# Hides-Keyboard-When-App-Goes-in-Background-.
When we are typing somthing and in between we have to swtich app then again when we come back to our app to continue typing . It should hide the keyboard for fixing the scrolling issue.

* Call this in AppDelegate Class

```swift
    func applicationWillResignActive(_ application: UIApplication) {

        self.window?.endEditing(true) //Hides the Keyboard when app goes in background
    }

```
