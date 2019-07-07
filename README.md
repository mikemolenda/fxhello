# fxhello
Hello world Maven / OpenJFX project.
Intended as a jumping off point for new projects.

See: https://openjfx.io/openjfx-docs/#IDE-Intellij

## Troubleshooting
Running the project in IntelliJ may produce the error:  
```
The Kotlin standard library is not found in the module graph. Please ensure you have the 'requires kotlin.stdlib' clause in your module definition
```  
This can be solved by selecting . Build > Rebuild Project from the menu.
See: https://intellij-support.jetbrains.com/hc/en-us/community/posts/360001806779-Intellij-Community-2018-3-seems-to-change-project-type-from-Java-to-Kotlin-arbitratily
