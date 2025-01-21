Operators
public class Operators {
    public static void main(String[] args) {
        
        // Arithmetic Operators
        int a = 10, b = 3;
        int sum = a + b;
        int difference = a - b;
        int product = a * b;
        int quotient = a / b;
        int remainder = a % b;

        System.out.println("Arithmetic Operators:");
        System.out.println("a + b = " + sum);
        System.out.println("a - b = " + difference);
        System.out.println("a * b = " + product);
        System.out.println("a / b = " + quotient);
        System.out.println("a % b = " + remainder);

        // Relational Operators
        boolean isEqual = a == b;
        boolean isNotEqual = a != b;
        boolean isGreaterThan = a > b;
        boolean isLessThan = a < b;
        boolean isGreaterThanOrEqual = a >= b;
        boolean isLessThanOrEqual = a <= b;

        System.out.println("\nRelational Operators:");
        System.out.println("a == b: " + isEqual);
        System.out.println("a != b: " + isNotEqual);
        System.out.println("a > b: " + isGreaterThan);
        System.out.println("a < b: " + isLessThan);
        System.out.println("a >= b: " + isGreaterThanOrEqual);
        System.out.println("a <= b: " + isLessThanOrEqual);

        // Logical Operators
        boolean x = true, y = false;
        System.out.println("\nLogical Operators:");
        System.out.println("x && y: " + (x && y));
        System.out.println("x || y: " + (x || y));
        System.out.println("!x: " + !x);

        // Unary Operators
        int count = 5;
        System.out.println("\nUnary Operators:");
        System.out.println("++count = " + (++count)); // Pre-increment
        System.out.println("count++ = " + (count++)); // Post-increment
        System.out.println("count = " + count);

        // Ternary Operator
        int max = (a > b) ? a : b;
        System.out.println("\nTernary Operator:");
        System.out.println("Max value between a and b: " + max);

        // Bitwise Operators
        int p = 5, q = 3;
        System.out.println("\nBitwise Operators:");
        System.out.println("p & q = " + (p & q)); // Bitwise AND
        System.out.println("p | q = " + (p | q)); // Bitwise OR
        System.out.println("p ^ q = " + (p ^ q)); // Bitwise XOR
        System.out.println("~p = " + (~p)); // Bitwise NOT
        System.out.println("p << 1 = " + (p << 1)); 
        System.out.println("p >> 1 = " + (p >> 1)); 

        // Assignment Operators
        a += 5; // a = a + 5
        b *= 2; // b = b * 2
        System.out.println("\nAssignment Operators:");
        System.out.println("a += 5: " + a);
        System.out.println("b *= 2: " + b);
    }
}

Output 

Arithmetic Operators:
a + b = 13
a - b = 7
a * b = 30
a / b = 3
a % b = 1

Relational Operators:
a == b: false
a != b: true
a > b: true
a < b: false
a >= b: true
a <= b: false

Logical Operators:
x && y: false
x || y: true
!x: false

Unary Operators:
++count = 6
count++ = 6
count = 7

Ternary Operator:
Max value between a and b: 10

Bitwise Operators:
p & q = 1
p | q = 7
p ^ q = 6
~p = -6
p << 1 = 10
p >> 1 = 2

Assignment Operators:
a += 5: 15
b *= 2:
