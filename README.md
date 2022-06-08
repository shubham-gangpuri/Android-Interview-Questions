## Android-Interview-Questions

Jotting down all the Android / Koltin / Java questions or topics which I have faced recently during interviews to answer for the android application developer profile -

## Java :
```
1. Access modifiers in java
2. Abstract vs Interface in java 8
3. Full vs Partial abstraction 
4. How many ways one can break the singleton design pattern?
5. Internal working of HashMap in java 8
6. Relationship between hashcode and equal methods in Map.
```

## Kotlin :
```
1. When to use and not to use inline functions?
2. Delegation in Koltin
3. Sealed classes with examples
4. Do null check without using operators - ?. or !! or elvish 
5. 'Any' vs 'Nothing' vs 'Unit'
6. Infix and Extension (Examples)
7. val vs const
8. Data class :
  data class A{
  }
  val a = A()
  val b = a
  print a == b
  print b.equal(b)
  print a === b
9. lateinit vs lazy
10. Context switching in coroutines
12. Parallel API calling with coroutines
13. What is coroutines context?
14. Sharedflow vs Stateflow
15. How to cancel a coroutines?
```

## Android :
```
1. Life cycle of activity with example.
2. Life cycle of fragment with example.
3. Launch modes in android with practical examples.
4. ViewModel lifecycle.
5. What Fragment data will survive on view model and on Saved instance state ? 
(https://developer.android.com/topic/libraries/architecture/saving-states)
6. SharedViewModel concept 
7. What is navigation component? How to pass objects between two fragments.
8. FCM notification is not displaying; What might be the possible cases for this problem?
9. What is scoped sortage and how to read/write/delete from it?
10. Internal working of ViewModel.
11. Internal working of recycler view.
12. Possible cases of memory leaks.
13. How to handle runtime permissions in android?
14. New ways to handle a backpress in android fragments.
15. What do you mean by safe-arg in android navigation components?
16. What is ModalBottomSheet in navigation components?
17. JobScheduler vs WorkManager
18. How to build communication between notification bar and service?
19. How surface view renders the livestream?
20. Handler vs HandlerThread vs Threads
21. How to achieve one launch mode via other launch mode?
22. In android build process, proguard is applied at what stage?
23. How to find out which fragment is currently opened?
24. ViewModelStore vs LifeCycleOwner
25. Disadvantages of constraintLayout
26. How to do View Hierarchy testing?
27. MergeAdpater
28. Room migration (Things need to handle)
29. What is the issue with LiveData in case of click event handling (SingleLiveData)
30. How to implement full custom theme in android?
31. Difference between location permissions.
32. DarkTheme implementation.
33. ViewHolder saving State vs Activity saving state
34. How to create your own view and viewgroups (methods and need to take care of)
35. How to create a simple alarm functionality with the help of WorkManager?
```

## Dependency Injection :
```
1. Scopes in Dagger or Hilt
2. Difference between field and method injection. Which is perferred, when and why?
3. Dependency graph.
4. Scope vs Qualifier
```

## RxJava/RxAndroid :
```
1. How to do Async calls in RxJava
2. Error handling in Rxjava
3. RxJava Observable (Fire & Forget)
4. FlatMap vs SwitchMap
5. Map vs FlatMap
6. Dispatcher swtiching in RxJava
7. HotObservables vs ColdObservables
8. Mutlipart request in case of RxJava
9. Debounce operator
10. Compositcomposable vs composable
11. Just vs Defer
```

## Architectural Concepts :
```
1. Difference between MVVM / MVP / MVI (Drawbacks)
2. What are all layers in MVVM?
3. What are solid principles (Examples in your android code)?
4. Test-cases for each MVVM layers (Examples).
5. What is clean architectural? How to implement it in your android App?
```

## 3rd Party Libraries :
```
1. Difference between Glide vs Picasso
2. What are static analysers in android
3. Gson vs Jackson vs Moshi
4. Have you used Memory profiler?
5. Firbase A/B testing
6. Mocking a context through Mockito
7. Write a simple test case to click on a textView.
8. Spy vs Mocking (Testing)
9. Have you done or created or managed any CI/CD pipleline for android app development?
10. Canary leak library internal working
11. What is GIT flow?
12. Git rebase vs merge
```

## Data Structure :
```
1. Find a loop in a linked list and remove it.
2. Write the logic for Quick Sort.
3. Left view of a BST.
4. Print 1,2,3,4,5 without using any loop or conditional statements (Use koltin)
5. Program to convert number to words (Use Koltin)
```

## Design :
```
1. Design a simple list with help of retrofit, recyclerview. Implement onitemclick and open another webview to load imageUrl.
2. Design a analytics library for android app as a stand alone sdk.
3. Design a data structure with search, delete and add with O(1) complexity. You can take my kind of predefined data structure (No space contraints).
4. Create your own map data structure
5. Create a music player app (HLD and LLD)
```
