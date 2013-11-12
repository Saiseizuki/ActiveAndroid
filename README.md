# ActiveAndroid-Secure

ActiveAndroid-Secure is meant to be a working example of using ActiveAndroid with SQLCipher v2.2.2

For more info on ActiveAndorid please click [here](https://github.com/pardom/ActiveAndroid)

In order to use the library you should first set a password in the ```Cache.java``` file.

```java
public static synchronized SQLiteDatabase openDatabase() {
	return sDatabaseHelper.getWritableDatabase("PASSWORD-GOES-HERE");
}
```

then type ```ant``` to build your .jar file
