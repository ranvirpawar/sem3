# Android Development Exam Topics

## 1. Mobile Application Development Architectures

### 1.1 Introduction to Mobile Application Technologies
- Mobile application development involves creating software applications specifically designed to run on mobile devices.
- Key mobile platforms include Android, iOS, Windows, and hybrid solutions.
- Mobile apps have become essential for businesses and individuals due to the widespread use of smartphones and tablets.

### 1.2 Android Architecture
- Android is an open-source operating system primarily designed for smartphones and tablets.
- Key components of Android architecture include the Linux Kernel, Libraries, Android Runtime, Application Framework, and Applications.
- Android applications are written in Java or Kotlin and run within a sandboxed environment.

### 1.3 iOS Architecture
- iOS is Apple's mobile operating system for iPhones, iPads, and iPods.
- iOS architecture consists of four layers: Cocoa Touch, Media, Core Services, and Core OS.
- iOS apps are primarily developed using Swift or Objective-C.

### 1.4 Windows Architecture
- Windows Mobile is a mobile operating system by Microsoft.
- Its architecture includes the Kernel, Core OS, Libraries, and Applications.
- Development for Windows Mobile is typically done using C# and the Universal Windows Platform (UWP).

### 1.5 Hybrid Architecture
- Hybrid apps combine elements of both native and web applications.
- These apps are typically developed using web technologies (HTML, CSS, JavaScript) and run within a native container.
- They provide cross-platform compatibility but may sacrifice some native performance.

## 2. Creating Android Applications

### 2.1 Creating Android Project
- To create an Android project, use Android Studio, the official IDE for Android development.
- You'll choose project settings like package name, language (Java or Kotlin), and minimum SDK version.

### 2.2 Project Structure
- Android projects have a specific folder structure, including directories for source code, resources, assets, and more.
- Understanding the project structure is crucial for organizing your code and resources efficiently.

### 2.3 Activity and Activity Life Cycle
- Activities are the fundamental building blocks of Android apps.
- The activity lifecycle includes methods like `onCreate()`, `onStart()`, `onResume()`, `onPause()`, `onStop()`, `onDestroy()`, which help manage app state and UI updates.

### 2.4 Fragment and Fragment Life Cycle
- Fragments allow you to build flexible UIs for different screen sizes and orientations.
- Fragment lifecycle methods are similar to activity lifecycle methods and include `onCreateView()`, `onPause()`, `onResume()`, etc.

### 2.5 Views and View Groups
- Android UI is built using views (UI elements) and view groups (containers).
- Common views include TextView, EditText, Button, ImageView, etc.
- View groups like LinearLayout, RelativeLayout, and ConstraintLayout help arrange views on the screen.

## 3. Interactivity Tools

### 3.1 Intents and Filters
- Intents are used for inter-component communication in Android.
- They can be explicit (targeting a specific component) or implicit (requesting an action like opening a web page).
- Intent filters specify which components can respond to implicit intents.

### 3.2 Adapters
- Adapters are used to connect data sources (e.g., arrays or databases) to UI components like ListView or RecyclerView.
- They manage the data and populate the UI with dynamic content.

### 3.3 Dialogs
- Dialogs are pop-up windows used to display messages, input forms, or other interactions to the user.
- Android provides various types of dialogs, including AlertDialog, ProgressDialog, and DatePickerDialog.

### 3.4 Menus
- Menus provide options and actions for the user within the app.
- There are two types of menus: options menu (appears in the app bar) and context menu (appears when long-pressing an item).

### 3.5 Notifications
- Notifications are used to alert users about events or updates, even when the app is not in the foreground.
- You can create and display notifications using the NotificationManager and NotificationCompat classes.
