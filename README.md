# Math-Guesser-Game
import java.util.Random;
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Random random = new Random();
        Scanner scanner = new Scanner(System.in);
        int number_generated = random.nextInt(100) + 1; 
        int guess = 0;
        System.out.println("Guess the number 1-100");
        while (guess != number_generated) {
            System.out.print("Enter your guess: ");
            guess = scanner.nextInt();
            if (guess > number_generated) {
                System.out.println("Too high");
            } else if (guess < number_generated) {
                System.out.println("Too low");
            } else {
                System.out.println("yay");
            }
        }
    }
}
