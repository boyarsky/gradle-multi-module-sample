# gradle-multi-module-sample
Sample code for a 694 student learning gradle (shown it works in three releases of gradle)

Key points:
* settings.gradle in the parent project lists the (one) module to be built
* The child project shows running a copy task after build
* running at the command line prints this showing the flow is what you were trying for.

```
gradle-multi-module-sample$ gradle build

> Configure project : 
Building parent

> Configure project :Child 
Building child
copy task


BUILD SUCCESSFUL in 0s
```
