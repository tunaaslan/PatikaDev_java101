
````java
import java.util.Scanner;
public class main {

    public static void main(String[] args) {
            Scanner input = new Scanner(System.in);
            int n=10;

            for (int i = 0; i < n; i++) {
                for (int j = 0; j <= i; j++) {
                    System.out.print(" ");
                }
                for (int k = 2 * n - 1; k >= (2 * i + 1); k--) {
                    System.out.print("*");

                }
                System.out.println();

            }


        }

    }


````