---
layout: default
---

[silex](https://github.com/willb/silex) is a library of reusable code for Spark applications, factored out of applications we've built at Red Hat.  It will grow in the future but for now we have an application skeleton, some added functionality for data frames, and a histogramming RDD.

### Using silex

Add the following resolver to your project:

```scala
resolvers += "Will's bintray" at "https://dl.bintray.com/willb/maven/"
```

and then add Silex as a dependency:

```scala
libraryDependencies += "com.redhat.et" %% "silex" % "0.0.3"
```

### API Documentation

API docs are [here](/latest/api).