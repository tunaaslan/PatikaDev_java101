# Vücut Kitle Endeksi Hesaplama

````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
  
            double kilo,boy,sonuc;  
  Scanner input = new Scanner(System.in);  
  
  System.out.print("kilonuzu girin(kg): ");  
  kilo=input.nextDouble();  
  
  System.out.print("boyunuzu girin(m): ");  
  boy=input.nextDouble();  
  
  sonuc= kilo / boy * boy;  
  
  System.out.print("Vücut Kitle Endeksi: "+sonuc);  
  
  
  }  
}
````