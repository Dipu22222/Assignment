# Print JAVA Pattern

**Name:** Dipu Mondol  
**ID:** IT-24040

## Description

This Java program prints a pattern that displays the word "JAVA" using ASCII art. The program uses `System.out.println()` statements to create a visual representation of the letters J, A, V, A with proper spacing and alignment. This is a simple demonstration of text output formatting in Java.

## Code

```java
public class PatternDisplay {
    public static void main(String[] args) {
        System.out.println("    J     A     V     V     A");
        System.out.println("    J    A A     V   V     A A");
        System.out.println("J   J   AAAAA     V V     AAAAA");
        System.out.println(" J J   A     A     V     A     A");
    }
}
```

## How to Run

1. Save the code as `PatternDisplay.java`
2. Compile: `javac PatternDisplay.java`
3. Run: `java PatternDisplay`

## Output

```
    J     A     V     V     A
    J    A A     V   V     A A
J   J   AAAAA     V V     AAAAA
 J J   A     A     V     A     A
```

## Pattern Explanation

The pattern displays the word **"JAVA"** in ASCII art form:

- **J**: Formed using 'J' characters in a curved shape
- **A**: Created using 'A' characters in a triangular shape
- **V**: Made with 'V' characters forming an inverted triangle
- **A**: Another 'A' character in triangular form

Each letter is carefully spaced to create a visually appealing pattern.

## Concepts Demonstrated

- `System.out.println()` - Printing text with new line
- String literals and spacing
- Pattern printing using ASCII characters
- Basic text formatting in console
- Multiple print statements for visual output

## Key Learning Points

1. **Spacing matters** - Each space is carefully placed to align the pattern
2. **Console output** - Understanding how text appears in the terminal
3. **String printing** - Using println() for text output
4. **Pattern design** - Creating visual patterns with text characters
