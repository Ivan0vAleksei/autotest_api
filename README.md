# Массив из 20

import java.util.Random;

public class RandomArrayExample {
public static void main(String[] args) {
int[] randomArray = new int[20];
Random random = new Random();

        
        for (int i = 0; i < randomArray.length; i++) {
            randomArray[i] = random.nextInt(100);
        }

        for (int i = 0; i < randomArray.length; i++) {
            System.out.print(randomArray[i] + " ");
        }
    }
}



