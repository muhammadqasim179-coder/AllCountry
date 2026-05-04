📦 AllCountires Library  [![](https://jitpack.io/v/muhammadqasim179-coder/AllCountry.svg)](https://jitpack.io/#muhammadqasim179-coder/AllCountry)

A simple Android library to access country data easily in your app.

🚀 Latest Version
implementation("com.github.muhammadqasim179-coder:AllCountires:1.0.3")
🆕 Version 1.0.3 (Bug Fixes)
🛠️ Fixed Issues:
Fixed country list loading crash in some devices
Improved API response handling
Fixed null pointer exception in data parsing
Optimized performance for large country datasets
Minor UI/data mapping corrections
📥 Installation
Step 1: Add JitPack repository
repositories {
    maven { url = uri("https://jitpack.io") }
}
Step 2: Add dependency
dependencies {
    implementation("com.github.muhammadqasim179-coder:AllCountires:1.0.3")
}
⚡ How to Use
val countries = AllCountires.getAll()
📌 Requirements
Min SDK: 21+
Kotlin supported project
🔄 Version History
Version	Changes
1.0.3	Bug fixes & performance improvements
1.0.2	Initial stable release
👨‍💻 Developer

Made with ❤️ by Muhammad Qasim
