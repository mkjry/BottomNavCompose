A very simple bottom menu and screen transition using Jetpack Compose, which intentionally implements only basic features.

3 steps of coding from the beginning

1. New Project > Empty Activity Project

   These are automatically generated codes using Android Studio before start coding.
  https://github.com/mkjry/BottomNavCompose/commit/13443a0dcfac5d1017135c4864921f298cc44d82

2. Add Dependency, clean codes
  https://github.com/mkjry/BottomNavCompose/commit/fb04d977f63c963b1db586c61e9b31560f053fdb

   gradle/libs.versions.toml
   
   app/build.gradle.kts
   
        
3. Navigation logic codes
  https://github.com/mkjry/BottomNavCompose/commit/69c374743686d5caddc0ef7cf76633948145aab1

   MainActivity.kt

   Define Screen Routes
   
   <img width="1015" height="171" alt="image" src="https://github.com/user-attachments/assets/b0023595-1cfa-4c1c-b5ba-e2e65ee447cd" />

   Implement the Navigation UI

   <img width="1395" height="1822" alt="image" src="https://github.com/user-attachments/assets/b1a0b4c0-7c4f-43a8-b0ca-744c9e0f1df7" />

Summary of the Workflow
1) Configuration:
   Register navigation-compose and icons in Gradle files.
2) Route Definition:
   Sealed class to hold tab metadata (Home, Page1, Page2).
3) Layout Structure:
   Use a Scaffold to place the NavigationBar at the bottom.
4) Content Mapping:
   NavHost to map each route to its Composable screen.
   
<img width="1440" height="3040" alt="image" src="https://github.com/user-attachments/assets/82419ff0-d9a1-4e53-b878-7f14b69467f0" />
<img width="1440" height="3040" alt="image" src="https://github.com/user-attachments/assets/9e43b273-e561-44a7-a461-94d8ed1ca9e7" />
<img width="1440" height="3040" alt="image" src="https://github.com/user-attachments/assets/7d9b1853-6ba8-48f7-b174-81e1eaff4929" />

Study material of Navigation with Jetpack Compose

Navigation with Compose

https://developer.android.com/develop/ui/compose/navigation


Get started with Jetpack Compose
https://developer.android.com/develop/ui/compose/documentation


