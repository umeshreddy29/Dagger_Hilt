youtube link :- https://youtu.be/lril-4MjCrA?si=dFXTDpbufJ3K77Y3

// dependency injection
1. add dependency,plugins,classpath
2. create
           @HiltAndroidApp
           class BaseClass : Application() {
           }
3. add in manifest file :- android.name = ".BaseClass"
4. add @AndroidEntryPoint to the activity to which we want to get dependency injection .
5. create ( object class of HiltModules ) with @InstallIn(SingletonComponent::class) @Module
