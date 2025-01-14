class Factorial {
    // Recursive method to calculate factorial
    static int factorial(int n) {
        if (n != 0)
            return n * factorial(n - 1);
        else
            return 1;
    }

    public static void main(String[] args) {
        int number = 3;
        int result = factorial(number);
        System.out.println(number + " factorial = " + result);
    }
}


OUTPUT:
3factorial = 6
 
