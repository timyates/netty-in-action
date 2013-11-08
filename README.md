Added gradle building to the original repo

I'll add extra bits I need as I work through the book.

To build the echo server/client instead of:

    mvn clean package

You can run:

    ./gradlew clean assemble

Then, when invoking java, change the classpath entry for `target/netty-in-action-0.1-SNAPSHOT.jar` to `build/libs/netty-in-action-0.1-SNAPSHOT.jar`
