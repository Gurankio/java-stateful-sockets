# java-stateful-sockets

This implementation interprets protocols as state machines.

State machines are considerably hard to express in code and are usually implemented with graph like structures
leading to non-clean code that is usually har to maintain.

In this implementation I tried for a hybrid approach, functional and object-oriented,
using functions as the state themselves, building an implicit graph from their subsequent call,
while using common OO patterns to properly express constraints in Java.

I've found this way easier to use, but it still needs some polishing here and there.
