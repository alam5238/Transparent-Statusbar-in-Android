# Transparent-Statusbar-in-Android
Transparent android individual activity by using this dependency  


## Step 1:
At first goto your android project  `res->style` folder then change the `DarkActionBar` into `NoActionBar`

## Step 2:
Adding or implement dependency in `build.gradle` 

```
com.jaeger.statusbarutil:library:1.4.0
```
## Step 3:
Now go to `MainActivity.java` file in `java->yourPackageName` folder. Then add below command,

```
StatusBarUtil.setTransparent(this);
```

## Step 4:
We are done!!
Now run the app and lets see magics. 

