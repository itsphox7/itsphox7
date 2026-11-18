# 👋 Hello there!

![Firefox](https://img.shields.io/badge/Firefox_Browser-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
```kotlin
class AboutMe(
    val name: String = "ItsPhox",
    val role: String = "Tech guy",
    val languageSpoken: List<String> = listOf("de_DE", "en_US")
) {
    fun sayHi() {
        println("Thanks for visiting my profile, hope you find some of my work interesting.")
    }
}

fun main() {
    val me = AboutMe()
    me.sayHi()
}
```
