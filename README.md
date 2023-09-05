# Notely

## 	:book: Description :
- Notely is a notes app written in Jetpeck Compose that lets you save your notes on your phone.
- Notes can be saved in different colors.
- Notes can be sorted by title, date and color. They can also be sorted by ascending or descending.

  </br>

## 	:gear: Library Versions : 
| Library | Version |
| ----------------- | ----------------- |
| Dagger - Hilt | 2.43.2 |
| Coroutines | 1.5.1 |
| Coroutine Lifecycle Scopes | 2.3.1 |
| Room | 2.3.0 |

</br>

## :camera_flash: Screens :
| Notes | Note Detail | Sort |  
|:-:|:-:|:-:|
| ![WhatsApp Image 2023-09-05 at 12 33 05 (1)](https://github.com/gultendogan0/Notely/assets/63645518/adefce6c-9761-43df-9034-0f5842eb3c9d) | ![WhatsApp Image 2023-09-05 at 12 33 04](https://github.com/gultendogan0/Notely/assets/63645518/c502dae6-1f09-41fd-a350-fdc701101a32) | ![WhatsApp Image 2023-09-05 at 12 33 05](https://github.com/gultendogan0/Notely/assets/63645518/170126af-c4f2-41ee-9244-146880d44850) |

- This app made %100 with  [Jetpack Compose](https://developer.android.com/jetpack/compose)
- Made with [Android Architecture Components ](https://developer.android.com/topic/architecture)for the Collection of libraries that help you design robust, testable, and maintainable apps.
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel): The ViewModel class acts as a bridge between the user interface and the model. It presents data from the model to the user interface and passes commands from the user interface to the model. ViewModel is independent of the UI, which makes the code more flexible and testable.Some advantages of using ViewModel are:
  
     • The dependency between the user interface and the model is reduced.
  
     • Code becomes more flexible and testable.
  
     • Data is preserved during configuration changes.
  
     • The user interface becomes more consistent.
  
     • The use of ViewModel provides a cleaner and more flexible design between the user interface and the model. This makes the code easier to understand and maintain. It also ensures that data is preserved during configuration changes, making the UI more consistent.
To give an example of the use of a ViewModel, a ViewModel can be used to manage the state of a user interface element. For example, a ViewModel can be used to manage the value of a text box element. When the user enters text in the text box, the ViewModel updates the value in the text box. When the user removes text from the text box, the ViewModel clears the value in the text box.
The use of ViewModel gives more flexibility and control to the user interface. ViewModel provides the UI with a way to present data and process commands from the UI. This helps to make the UI more user-friendly and interactive.
- [Kotlin Coroutine](https://developer.android.com/kotlin/coroutines): Coroutines on Android are a special Kotlin feature that helps improve your app's performance and deliver smoother user experiences. Coroutines allow you to effectively manage long-running processes that might otherwise block the main thread and cause your app to become unresponsive. This ensures that your application is still responsive when performing slow or time-consuming tasks such as network requests, file operations, or database queries.By using coroutines, you can express application logic in a cleaner and more concise way. It also makes asynchronous programming more readable and manageable. Coroutines have less risk of bugs and memory leaks compared to traditional thread management and make your code more maintainable.
- [Dependency Injection with Hilt](https://developer.android.com/training/dependency-injection/hilt-android): Hilt is a dependency injection library used in Android applications. This library allows you to manage dependencies in your project more efficiently. Instead of doing manual dependency injection, with Hilt you can create and manage dependencies automatically. This makes your code more organized and makes the development process easier. By eliminating the need to manually create every class and dependency, it speeds up your development process and increases the likelihood of making fewer mistakes.
- [UseCase](https://developer.android.com/topic/architecture/domain-layer):Located domain layer that sits between the UI layer and the data layer.
- [Room](https://developer.android.com/training/data-storage/room):Apps that handle non-trivial amounts of structured data can benefit greatly from persisting that data locally. The most common use case is to cache relevant pieces of data so that when the device cannot access the network, the user can still browse that content while they are offline.The Room persistence library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite.
