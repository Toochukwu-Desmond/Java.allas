import java.util.Scanner;

public class ArrayExample {
    public static void main(String[] args) {
        int[] myArray  = {1,3,5,7,9};
        int[] anotherArray = new int[10];
        String[] gender = {"female", "male"};

        Scanner input = new Scanner(System.in);

        myArray[1] = 13;
        myArray[2] = 13;
        myArray[3] = 14;
        anotherArray[5] = 17;

        for (int i = 0; i < anotherArray.length; i++) {
            if (anotherArray[i] ==13){

                System.out.println("Found it");
                break;

            }
            System.out.println("Item at: " +i+ " is " +anotherArray[i]);
            anotherArray[i] = input.nextInt();

        }
    }
}
