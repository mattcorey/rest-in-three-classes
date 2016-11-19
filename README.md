REST Web Service in only Three Classes
======================================

This demo shows off how you can create a fully functional -- albeit simple -- REST app with only three classes.  For
further info, see [my blog -- Smoke and Ice](https://smokeandice.net/2016/11/16/sweet-simplicity-of-a-rest-app-with-spring-boot/)

Building and Running
--------------------

This project includes a Gradle build script, and the Gradle wrapper -- running it is simple:

```
./gradlew build
```

Running it is also simple:

```
./gradlew bootRun
```

What do I do with it?
---------------------

Well, it's just a demo, so there's not much to do, but once you have it running, you can access the following URL's:

* Site HATEOAS link -- http://localhost:8080
* List Users -- GET to http://localhost:8080/users
* Create a User -- POST to http://localhost:8080/users (JSON format listed below)
* Get a specific User -- GET to http://localhost:8080/users/<user-id>
* Delete a specific User -- DELETE to http://localhost:8080/users/<user-id>
* Edit a user -- PUT or PATCH to http://localhost:8080/users/<user-id>
* ALPS metadata -- http://localhost:8080/profile

The JSON format for creating, editing and retrieving data is simple:

```
{
    "firstName": "Barry",
    "lastName": "White",
    "email": "aaaaaaawww@yeeeeaaah.com"
}
```

What else do I do with it?
--------------------------

There's really nothing else here -- play around, expand it, and use the knowledge you just gained on your next project!