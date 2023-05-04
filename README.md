
# Java Donut
This is a Java implementation of the Spinning Donut program by Andy Sloane, originally written in C. The program uses ASCII art to create a 3D spinning donut that rotates on the screen.

- [Source C Code](https://www.dropbox.com/s/79ga2m7p2bnj1ga/donut_deobfuscated.c?dl=0)
- [Explanatory blog post](https://www.a1k0n.net/2011/07/20/donut-math.html) by Andy Sloane
- [Explanatory video](https://www.youtube.com/watch?v=DEqXNfs_HhY) by [Lex Fridman](https://lexfridman.com/), research scientist at MIT.

## Demo
![Donut ASCII animation demo](./src/images/donut-demo.gif)

## Installation and Usage
To use the program, you need to have the Java Development Kit (JDK) installed on your computer. You can download it from the [Oracle](https://www.oracle.com/java/technologies/downloads/) website.

The Donut class contains a Main method; simply run `Donut.java` to access the program.

1. Clone this repo or download the `Donut.java` file and save it on your computer.
2. Open a terminal or command prompt and navigate to the directory where you saved `Donut.java`.
3. Compile: 
```
javac Donut.java
```
4. Run the program: 
```
java Donut
```

Behold the spinning donut!

Note: The donut may rotate too fast on some computers. If this happens, you can slow it down by changing the values of the A and B constants at the end of the Donut class.

## License
This program is licensed under the MIT License. You can use it for any purpose, as long as you include the original copyright notice:

Original program (C) 2006 by Andy Sloane. Permission to use for any purpose.
