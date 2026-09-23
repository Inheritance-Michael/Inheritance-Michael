<div align="center">
  <!-- Main Skillicons Line -->
<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,git,github&theme=dark" alt="Tech Stack" />
<br />
<!-- Additional Framework Badges -->
<img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
<img src="https://img.shields.io/badge/Ktor-087CFA?style=for-the-badge&logo=ktor&logoColor=white" alt="Ktor" />
<img src="https://img.shields.io/badge/Koin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Koin" />
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
