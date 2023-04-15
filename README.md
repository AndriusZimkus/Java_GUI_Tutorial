# JAVA GUI Tutorial
The lesson content is from [Java GUI: Full Course](https://www.youtube.com/watch?v=Kmgo00avvEw)

Implementation:

All examples can be reached from StartWindow through the list of buttons.

The examples are saved in the ExamplesTreeMapAbstractClass and stored in a TreeMap.
TreeMap is preferred over HashMap for sorted keys.

In the TreeMap human readable names of examples/functions are paired with calls to the respective classes - this is achieved using ExampleInvoker functional interface and lambda expressions.

The buttons are created by looping through the TreeMap keys.
