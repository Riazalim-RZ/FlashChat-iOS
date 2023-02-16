# FlashChat-iOS
# My Testing Chat Application

Flash Chat App for iOS. This App is my testing chat app. written in Swift using Firebase.

# Overview

Flash Chat App allows to send and receieve text messages instantly between two users. The project inteded to cover one of the most fundamental component of modern iOS Applications which is Table View.

Tools used -
Xcode,
Swift,

# Pods for Flash Chat iOS13

 FirebaseAuth'
 FirebaseFirestore'
 IQKeyboardManagerSwift'



# UI View


<img width="567" alt="Screenshot 2023-02-16 at 2 37 23 PM" src="https://user-images.githubusercontent.com/62168289/219327047-b25d1759-c68c-4d8c-a638-aacd135181d4.png">

# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

