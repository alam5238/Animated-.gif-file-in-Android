# Animated-.gif-file-in-Android
Run animation gif image in android layout. Easily use animation with library file.


##Now follow these below step::
---

***Step 1 :***
Create a project in Android Studio.

***Step 2 :***
Now add the library script in `build.gradle(project: XXX)` .
```
          allprojects {
                repositories {
                      jcenter()
                      mavenCentral()
        
                }
          }
```
          
```
          buildscript {
              repositories {
                     jcenter()
                      mavenCentral()
               }
          
      
```

***Step 3 :***
Now add the Dependencies in `build.gradle(Module: app)` .

```
dependencies {
compile 'pl.droidsonroids.gif:android-gif-drawable:1.2.8'
{
```

***Step 4 :***
Create layout file in `res/layout/your_layout.xml`

         
