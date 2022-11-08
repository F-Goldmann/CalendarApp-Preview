# CalendarApp Preview
### This preview showcases some of the apps features and the main tech, which is used to develope it.
If you are interested in seeing more feel free to reach out to me.

## Main objectives
The main objectives of the app are to collect the appointments and tasks of all family members. The data shall be synchronized via a lamp-server in a local network.
## Technical background
The following tools are used to develope the android-application:
   - Kotlin
   - UI → Jetpack Compose
   - Dependency Injection → Hilt
   - Data storage
     - Room Database for lists (e.g. appointments, tasks ...)
     - Proto DataStore for single data classes (e.g. settings)
   - Unit Tests → JUnit4
   - API-Calls → Ktor client
   
In order to follow the principles of *MVVM* the app is seperated in data-, domain- and presentation-layer where each screen has a viewmodel to handle its data.
   
## Examples
<img src="https://github.com/F-Goldmann/CalendarApp-Preview/blob/main/graphics/Calendar.gif" alt="Calendar screen" height="480">
<img src="https://github.com/F-Goldmann/CalendarApp-Preview/blob/main/graphics/Tasks.gif" alt="Tasks screen" height="480">
