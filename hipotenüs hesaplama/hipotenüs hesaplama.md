#  Hipotenüs hesaplama

````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
            int a ,b ,c;  
  
  Scanner input = new Scanner(System.in);  
  
  System.out.print("Üçgenin a kenarını giriniz: ");  
  a = input.nextInt();  
  
  System.out.print("Üçgenin b kenarını giriniz: ");  
  b = input.nextInt();  
  
  c = a*a + b*b;  
  c *= c;  
  System.out.print("Üçgenin hipotenüsü: "+ c);  
  
  
  
  
  }  
}
````