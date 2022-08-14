# Daire Çevre Ve Alan Hesabı
````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
            double pi=3.14, r,cevre,alan;  
  
  Scanner input = new Scanner(System.in);  
  
  System.out.print("Dairenin yarı çapını girin: ");  
  r = input.nextDouble();  
  
  cevre=2*pi*r;  
  alan=pi*r*r;  
  
  System.out.println("Dairenin alanı: "+ alan);  
  System.out.print("Dairenin çevresi: "+ cevre);  
  

  
  }  
}
````