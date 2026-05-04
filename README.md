📦 AllCountires Library [![](https://jitpack.io/v/muhammadqasim179-coder/AllCountry.svg)](https://jitpack.io/#muhammadqasim179-coder/AllCountry)


A simple Android library to access country data easily in your app.

🚀 Latest Version

 implementation("com.github.muhammadqasim179-coder:AllCountry:1.0.5")
	
🆕 Version 1.0.5 (Bug Fixes)
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
    implementation("com.github.muhammadqasim179-coder:AllCountry:1.0.5")
}

⚡ How to Use
val countries = AllCountires.getAll()

⚡ Get Flag by Country Code
You can easily get a country flag using its ISO code:
get UNiCODE flag that occupied less space.

val flag = CountrySDK
    .getAllCountries()
    .find { it.code.equals("PK", ignoreCase = true) }
    ?.flag

println(flag) // 🇵🇰

⚡ Model class
data class Country(
    val name: String,
    val code: String,
    val flag: String
)
 AllCountires.getAll() list directly pass in Country type model .
 
229 Country Flags

📌 Requirements
Min SDK: 21+
Kotlin supported project
🔄 Version History
Version	Changes
1.0.5	Bug fixes & performance improvements

👨‍💻 Developer

Made with ❤️ by Muhammad Qasim
