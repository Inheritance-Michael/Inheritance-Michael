<div align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,android,git,github&theme=dark" alt="Kotlin Developer" />
  <br/>
  <h1>Hi, I'm Inheritance👋</h1>
  <h3>Native Android || Kotlin || Building cross-platform ecosystems with Kotlin & Jetpack Compose</h3>
</div>


### 👨‍💻 `About.kt`

```kotlin
package dev.profile

import dev.skills.*
import dev.projects.Blink

data class SoftwareEngineer(
    val name: String = "inheritance michael",
    val education: String = "NIIT Nigeria",
    val primaryLanguages: List<String> = listOf("Kotlin", "Java", "JavaScript", "TypeScript","etc.."),
    val specialties: List<String> = listOf("Jetpack Compose", "Compose Multiplatform", "MVVM"),
    val currentFocus: String = "Building robust, local-first application architectures"
) {
    fun getDailyRoutine(): String {
        return "Write Code -> Sync Room DB -> Push to GitHub -> Repeat"
    }
}
