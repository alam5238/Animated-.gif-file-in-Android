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

***Step 5 :***
Copy your `.gif` file and past in `res/drawable` directory. 

***Step 2 :***
Now add this code to your `your_layout.xml` file .

```
        <pl.droidsonroids.gif.GifImageView
            android:id="@+id/gifImageView"
            android:layout_width="match_parent"
            android:layout_height="200dp"
            android:layout_above="@+id/textView"
            android:layout_alignParentLeft="true"
            android:layout_alignParentStart="true"
            android:layout_marginTop="170dp"
            android:src="@drawable/banana"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintRight_toRightOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.421" />
```

***Here `android:src="@drawable/banana"` banana is your animated gif file name.***        



