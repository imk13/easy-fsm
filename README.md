# easy-fsm [![Travis build status](https://travis-ci.org/koushikr/easy-fsm.svg?branch=master)](https://travis-ci.org/koushikr/easy-fsm)

A small java state machine which would let you define events, states and their appropriate bindings.

> We are not saying that Evolution can't exist, only that it is guided by His Noodly Appendage.
>  - by Bobby Henderson, The Gospel of the Flying Spaghetti Monster

### Maven Dependency
Use the following repository:
```xml
<repository>
    <id>clojars</id>
    <name>Clojars repository</name>
    <url>https://clojars.org/repo</url>
</repository>
```
Use the following maven dependency for java8: (Shall be deprecated henceforth!)
```xml
<dependency>
    <groupId>io.github.fsm</groupId>
    <artifactId>fsm</artifactId>
    <version>0.0.2-1</version>
</dependency>
```

Use the following maven dependency for java11:
```xml
<dependency>
    <groupId>io.github.fsm</groupId>
    <artifactId>fsm</artifactId>
    <version>1.0.1</version>
</dependency>
```

### Build instructions
  - Clone the source:

        git clone github.com/koushikr/easy-fsm

  - Build

        mvn install


LICENSE
-------

Copyright 2015 Koushik R <rkoushik.14@gmail.com>.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
