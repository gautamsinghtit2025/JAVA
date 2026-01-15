# JAVA
Java Lambda Expressions -:  anonymous functions , 
-> Lambda expressions implement a functional interface (An interface with only one abstract function)
-> Enable passing code as data (method arguments).
-> Allow defining behavior without creating separate classes.

code -:
-----------------------------------------------------------------------------------------
interface Add{
    
    int addition(int a, int b);
}

public class GFG{
    
    public static void main(String[] args){
        
        // Lambda expression to add two numbers
        Add add = (a, b) -> a + b;
        
        int result = add.addition(10, 20);
        System.out.println("Sum: " + result);
    }
}
