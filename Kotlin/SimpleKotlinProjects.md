# Using Android Studio for Kotlin Projects
1. Open Android Studio and choose _New Project_
2. Leave the category selection (left side) set to _Phone and Tablet_
3. Choose the _No Activity_ template
4. Enter a name and save location
5. For the language, choose Kotlin
6. Remember the package name
7. Click _Finish_ and wait for the project to load up.
8. Find your empty source folder:
    1. Open the _Project_ tab (very left edge of the IDE)
    2. Use the _Android_ view (top dropdown of the Project pane)
    3. Look for folder _app_ > _java_ > packageName (the package name you were supposed to remember from step 6)
9. Right-click this folder and choose _New_ > _Kotlin Class/File_
10. Enter a name (ex: _HelloWorld_) and choose _File_ as the type
11. Under the package line, enter this code:

    ```kt
    fun main(args: Array<String>) {
        println(helloWorld())
    }
    
    fun helloWorld(): String {
        return "Hello Kotlin World!"
    }
    ```
    
12. In the file editor, next to the line numbers, a green play button will appear on the `fun main` line.  Click this button (not the play button at the top of the IDE) and your program will run.
13. You are now a professional Kotlin engineer!