# Math-Guesser-Game
import java.util.*;
import java.util.Random;
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Random random = new Random();
        Scanner scanner = new Scanner(System.in);
        int number_generated = random.nextInt(100 - 1);
        System.out.print("What is the number ");
        int guess = scanner.nextInt();
        while (guess != number_generated){
            if (guess > number_generated){
                System.out.print("Too high");
        }
            else{
                System.out.print("Too high"); 
        }
        }
    }
}
