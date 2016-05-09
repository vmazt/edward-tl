# Edward Threadlocal #
This is a test project for a java agent inspecting thread local leaks. It's not even an early alpha, so please don't use it =)

[![Build Status](https://travis-ci.org/metacoder/edward-tl.svg?branch=master)](https://travis-ci.org/metacoder/edward-tl)

## Agent run: ##

Compile with mvn clean install. Run the agent test with:
```
mvn clean install; java -javaagent:./agent-impl/target/agent-impl-0.0.1-SNAPSHOT-bin/agent-impl-0.0.1-SNAPSHOT/agent-loader-0.0.1-SNAPSHOT.jar -cp ./agent-test/target/agent-test-0.0.1-SNAPSHOT.jar de.metacoder.edwardthreadlocal.test.Main
```

from the root directory of your project =)

Have fun!
