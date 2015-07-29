java-thread-sanitizer
=====================

This project hosts java code for ThreadSanitizer.

Build Instructions
-----------

    ant download # To download project dependencies.
    ant # To build the code of the instrumentation agent.

Running Your Code under the Instrumentation Agent
-----------

Take a look into examples/README.txt for instructions on running code under the agent.


----------------说明
java-thread-sanitizer 的作用是为了在 ThreadSanitizer 上进行 Java 编程。

补充：ThreadSanitizer 是一个检测数据竞争的工具（detects data races）。
