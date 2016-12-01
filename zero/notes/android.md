##Gradle

### The Project-Level File
    * buildscript: configure the JARs and such that Gradle itself will use for interpreting the rest of the file.
    * repositories closure inside the buildscript indicates where dependencies can com from, typically in the form of Maven-style repositories.
    * allprojects: apply these settings to all modules in the project.


### The Module-Level File
    * dependencies: libraries used by your code in that module.
    * android: contians all of the Android-specific configuration information, what the Android plugin enables


##Dimensios
    * px means hardware pixels, whose size will vary by device, since not all device have the same screen density.
    * in and mm for inches and millimeters, respectively, based on the actual size of the screen
    * pt for points, which in pushlishing terms is 1/72nd of an inch
    * dip(or dp) for density-independent pixels - one dip equals one hardware pixel for a ~160dpi resolution screen, but one dip equals two hardware pixels on a ~320dpi screen
    * sp for scaled pixels, where one sp equals one dip for normal font scale levels, increasing and decreasing as needed based upon the user's chosen font scale level in Settings.
