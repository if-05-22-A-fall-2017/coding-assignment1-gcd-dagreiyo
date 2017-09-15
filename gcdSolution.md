public class GCD {

    /**
     * @author Greul
     */
    public static void main(String[] args) {
        int number1 = 1989;
        int number2 = 867;
        int result1 = gcd1(number1, number2);
        System.out.println(result1);
        int result2 = gcd2(number1, number2);
    }

    private static int gcd1(int number1, int number2) {
        if(number2 == 0){
            return number1;
        }
        return gcd1(number2, number1 % number2);
    }

    private static int gcd2(int number1, int number2) {
        return 0;
    }
    
}
