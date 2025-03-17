import java.util.Arrays;

public class LargestThreeNumbers {
    public static void main(String[] args) {
        int[] numbers = {12, 5, 8, 20, 19, 6, 25, 15};

        // Sort the array in descending order
        Arrays.sort(numbers);

        // Print the three largest numbers
        System.out.println("The three largest numbers are:");
        System.out.println("1st Largest: " + numbers[numbers.length - 1]);
        System.out.println("2nd Largest: " + numbers[numbers.length - 2]);
        System.out.println("3rd Largest: " + numbers[numbers.length - 3]);
    }
}
