# ObjectBoxExamples
Examples for [ObjectBox](http://objectbox.io), the new superfast object-oriented database.

The basic example is a minimal note taking Android app. There are 3 different variations of this app:

 * objectbox-example: Java based app
 * objectbox-kotlin-example: Kotlin based app
 * daocompat-example: DAO compat is a compatibility layer on top of ObjectBox emulating a greenDAO API

And additionally:

 * objectbox-relation-example: Demonstrating relations (Java based app)

MyObjectBox missing? Build the project!
---------------------------------------
When you open the project in an IDE like Android Studio for the first time, it will complain that it does not find the class `MyObjectBox`.
This is expected because this class is generated during build time.
Thus, once you build the project, everything should be fine.

Links
-----
[ObjectBox Documentation](http://objectbox.io/documentation/)

[ObjectBox Features](http://objectbox.io/features/)

[ObjectBox repo](https://github.com/greenrobot/ObjectBox) (to report issues)
