# Week 1 Review — Campus Connect

## Course

Mobile Application Development with Android

## Project

Campus Connect

## Week 1 Topic

Declarative UI and Your First Overlap Bug

---

## 1. What I Learned

In Week 1, I created my first Android application using Kotlin and Jetpack Compose.

I learned that Jetpack Compose uses a declarative approach to building user interfaces. Instead of manually creating and modifying views, I describe what the UI should contain and Compose renders it.

---

## 2. Creating the First UI

I created a `Greeting` composable that displays a greeting message.

The first version displayed:

`Hello, World!`

I then changed the value to:

`Hello, Jacob!`

This demonstrated how changing the data passed to a composable changes what is displayed on the screen.

---

## 3. The Overlap Bug

I created three `Greeting` composables:

* Jacob
* George
* Alex

They appeared on top of each other.

This happened because the three composables were placed in the UI without specifying a layout arrangement.

The problem demonstrated that composables need appropriate layout containers when multiple UI elements need to be positioned relative to one another.

For example, a `Column` could be used to arrange the greetings vertically.

---

## 4. SDK Configuration

I experimented with the Android SDK configuration by changing the minimum SDK and target SDK.

I tested:

* `minSdk = 37`
* `targetSdk = 37`

The project successfully built with this configuration.

I then restored the minimum SDK to:

* `minSdk = 24`
* `targetSdk = 37`

The project successfully built again.

I learned that `minSdk` determines the oldest Android version that the application supports, while `targetSdk` identifies the Android API level the application is targeting.

---

## 5. Testing on a Physical Device

Because the computer did not have enough RAM to run the Android emulator, I configured a physical Tecno Spark 50 for development.

I enabled Developer Options and USB debugging and successfully connected the phone to Android Studio.

The Campus Connect application successfully ran on the physical device.

---

## 6. Git and GitHub

I used Git throughout the lab to track my progress.

The project was connected to the GitHub repository for the Mobile Application Development course.

The major stages were committed and pushed to GitHub after completion.

This provided a history of the development process and made it possible to track each stage of the lab.

---

## 7. Final Reflection

The most important lesson from Week 1 was understanding that Compose describes the UI declaratively.

The overlap problem showed that simply declaring multiple UI elements does not automatically determine how they should be positioned. Layout containers are needed to control their arrangement.

I also gained practical experience creating an Android project, running it on a physical Android device, changing SDK settings, building the application, and using Git and GitHub to track my work.

## Week 1 Status

**Completed successfully.**
