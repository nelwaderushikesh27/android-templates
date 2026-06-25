# 📱 Android Templates

Reusable Android development templates to kickstart your projects.

## 🎯 Available Templates

| Template | Description | Tech Stack |
|----------|-------------|------------|
| **mvvm-clean** | MVVM + Clean Architecture | Kotlin, Dagger Hilt, Retrofit |
| **compose-starter** | Jetpack Compose starter | Compose, Navigation, Material 3 |
| **room-database** | Room DB template | SQLite, Room, KSP |
| **firebase-auth** | Firebase Auth example | Firebase, Google Sign-In |
| **recyclerview** | RecyclerView patterns | DiffUtil, Paging 3 |

## 🚀 How to Use

```bash
# Using git
git clone https://github.com/nelwaderushikesh27/android-templates.git

# Copy the template you need
cp -r android-templates/mvvm-clean my-new-app/
```

## 📂 MVVM-Clean Template Structure

```
mvvm-clean/
├── app/
│   ├── src/main/java/
│   │   ├── data/
│   │   │   ├── local/
│   │   │   ├── remote/
│   │   │   └── repository/
│   │   ├── domain/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   └── usecase/
│   │   ├── ui/
│   │   │   ├── screens/
│   │   │   └── components/
│   │   └── di/
│   └── build.gradle
└── README.md
```

## 📦 Dependencies

```kotlin
// Always included
implementation "org.jetbrains.kotlin:kotlin-stdlib:1.9.22"
implementation "androidx.core:core-ktx:1.12.0"

// Architecture
implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0"
implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.7.0"

// Networking
implementation "com.squareup.retrofit2:retrofit:2.9.0"
implementation "com.squareup.okhttp3:logging-interceptor:4.12.0"

// DI
implementation "com.google.dagger:hilt-android:2.50"
kapt "com.google.dagger:hilt-compiler:2.50"
```

## 🤝 Contribute

Add your own templates or improve existing ones!

---
*Building faster, building better! 🚀*
