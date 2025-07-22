# Android Interview Questions
 ##Your Cheatsheet For Android Interview

### Hi All,

### Hi, I'm Hitesh Khandelwal, an Android Mobile Application Developer with over a decade of hands-on experience building mobile apps across diverse domains including mobile banking, automotive, telecom, and business applications.

### I'm passionate about sharing knowledge through open-source contributions, technical blogs, and videos.

### This page is created as part of my effort to compile the most commonly asked Android interview questions, aimed at helping fellow Android developers prepare and grow in their careers.



# Contents - Android Interview Questions
- Android Interview Questions and Answers Playlist
- Kotlin Coroutines
- Kotlin Flow API
- Kotlin
- Android
- Android Libraries
- Android Architecture
- Design Pattern
- Android System Design and check Android System Design Interviews
- Android Unit Testing
- Android Tools And Technologies
- Java
- Jetpack Compose
- Other Topics
- Data Structures and Algorithms

## Android Interview Questions and Answers Playlist
1. Android Push Notification Flow using FCM
2. What is an inline function in Kotlin?
3. What is the advantage of using const in Kotlin?
4. What is a reified keyword in Kotlin?
5. Suspending vs Blocking in Kotlin Coroutines
6. Launch vs Async in Kotlin Coroutines
7. Question: Is it possible to force the Garbage Collection in Android?
8. Question: What is a JvmStatic Annotation in Kotlin?
9. Question: init block in Kotlin
10. JvmField Annotation in Kotlin
11. singleTask launchMode in Android
12. Difference between == and === in Kotlin
13. JvmOverloads Annotation in Kotlin
14. Internal visibility modifier in Kotlin
15. open keyword in Kotlin
16. Lateinit vs lazy in Kotlin
17. What is Multidex in Android?
18. How does the Android Push Notification system work?
19. How does the Kotlin Multiplatform work?
20. What is a ViewModel and how is it useful?
21. Why is it recommended to use only the default constructor to create a Fragment?
22. Why do we need to call setContentView() in onCreate() of Activity class?
23. When only onDestroy is called for an activity without onPause() and onStop()?

## Kotlin Coroutines
Topics you should know in Kotlin Coroutines for Android Interview:

- coroutines
- suspend
- launch, async-await, withContext
- dispatchers
- scope, context, job
- lifecycleScope, viewModelScope, GlobalScope
- suspendCoroutine, suspendCancellableCoroutine
- coroutineScope, supervisorScope

## Kotlin Flow API
Topics you should know in Kotlin Flow API for Android Interview:

- Flow Builder, Operator, Collector
- flowOn, dispatchers
- Operators such as filter, map, zip, flatMapConcat, retry, debounce, distinctUntilChanged, flatMapLatest
- Terminal operators
- Cold Flow vs Hot Flow
- StateFlow, SharedFlow, callbackFlow, channelFlow

 ## Kotlin
Android Interview Questions and Answers:

- What is the advantage of using const in Kotlin?
- When to use lateinit keyword used in Kotlin?
- What is inline function in Kotlin?
- What are companion objects in Kotlin?
- Extension functions
- What is a data class in Kotlin?
- Remove duplicates from an array in Kotlin
- What is a JvmStatic Annotation in Kotlin?
- What is a JvmField Annotation in Kotlin?
- What is a JvmOverloads Annotation in Kotlin?
- noinline in Kotlin
- crossinline in Kotlin
- scope functions in Kotlin
- What is a reified keyword in Kotlin?
- lateinit vs lazy in Kotlin
- What is an init block in Kotlin?
- Difference between == and === in Kotlin
- Advantage of using const in Kotlin
- What are higher-order functions in Kotlin?
- Write a function(Higher-Order Function) that returns a function.
- What are Lambdas in Kotlin
- AssociateBy
- Open keyword in Kotlin
- Companion object in Kotlin
- internal visibility modifier in Kotlin
- partition - filtering function in Kotlin
- Infix notation in Kotlin
- How does the Kotlin Multiplatform work?
- Suspending vs Blocking in Kotlin Coroutines
- What is runBlocking in Coroutines?
- What is the meaning of structured concurrency in Kotlin Coroutines?
- String vs StringBuffer vs StringBuilder
- What is the difference between val and var?
- How to check if a lateinit variable has been initialized?
- How to do lazy initialization of variables in Kotlin?
- What are the visibility modifiers in Kotlin?
- What is the equivalent of Java static methods in Kotlin?
- How to create a Singleton class in Kotlin?
- What is the difference between open and public in Kotlin?
- apply scope function and its use cases
- let scope function and its use cases
- Explain the use-case of let, run, with, also, apply in Kotlin
- How to choose between apply and with?
- Difference between List and Array types in Kotlin
- What are Labels in Kotlin?
- What are Coroutines in Kotlin? 
- What is Coroutine Scope?
- Scopes in Kotlin Coroutines Used in Android 
- What is Coroutine Context?
- Launch vs Async in Kotlin Coroutines
- How to Implement Debounce Using Coroutines?
- Kotlin code snippet demonstrating how to run two coroutines in series and parallel
- yield in Kotlin Coroutines
- Delegates in Kotlin
- stateIn vs shareIn in Kotlin Flow
- flatMapConcat, flatMapMerge, and flatMapLatest in Kotlin Flow
- collect vs collectLatest in Kotlin Flow
- Thread.sleep() vs delay() in Kotlin
- Explain inline classes in Kotlin
- Sealed Classes in Kotlin
- Tell about the Collections in Kotlin
- What does ?: do in Kotlin? (Elvis Operator)
- timeouts in Kotlin Coroutines
- How do you combine multiple coroutine results?
- What is a Job in Coroutines?
- Coroutines job.cancel() vs scope.cancel()

## Android 
Android Interview Questions and Answers:

### Base
- Why does an Android App lag?
- What is Context? How is it used? - Context In Android Application
- Tell all the Android application components
- What is the project structure of an Android Application?
- What is AndroidManifest.xml?
- What is the Application class?

### Activity and Fragment
- Why is it recommended to use only the default constructor to create a Fragment?
- What is Activity and its lifecycle?
- What is the difference between onCreate() and onStart()
- When only onDestroy is called for an activity without onPause() and onStop()?
- Why do we need to call setContentView() in onCreate() of Activity class?
- What is onSaveInstanceState() and onRestoreInstanceState() in activity?
- What is Fragment and its lifecycle?
- What are "launchMode"?
- What is the difference between a Fragment and an Activity? Explain the relationship between the two
- When should you use a Fragment rather than an Activity?
- When you have some UI components to be used across various activities
- When multiple views can be displayed side by side just like ViewPager
- What is the difference between FragmentPagerAdapter vs FragmentStatePagerAdapter?
- - FragmentPagerAdapter: Each fragment visited by the user will be stored in the memory but the view will be destroyed. When the page is revisited, then the view will be created not the instance of the fragment.
  - - FragmentStatePagerAdapter: Here, the fragment instance will be destroyed when it is not visible to the user, except the saved state of the fragment.
- What is the difference between adding/replacing fragment in backstack?
- How would you communicate between two Fragments?
- What is retained Fragment?
- What is the purpose of addToBackStack() while commiting fragment transaction?
  By calling addToBackStack(), the replace transaction is saved to the back stack so the user can reverse the transaction and bring back the previous fragment by pressing the Back button.
  
### View
