# Template for 1.12.2 Cleanroom or Forge
Everything but the Java Classes are thanks and are credited to SizeableShrimps ForgeTemplates found [Here](https://github.com/SizableShrimp/ForgeTemplate/tree/1.12.x)

## Setting up
* Open up `gradle.properties` and change all the necessary properties
* Rename the main package to be the same as `mod_base_package` in the properties file, e.g. `io.github.examplemod`
* Uncomment codes in `build.gradle` if you are using coremod or mixin
* You need to run gradle with Java 17+ or the blossom refuse to work. You can still compile with whatever version of JDK required.

Finally, import into your IDE of choice.
