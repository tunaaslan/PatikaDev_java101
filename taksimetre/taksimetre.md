# Taksimetre
````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
            int km;  
 double kmbasina = 2.20, total, baslangic = 10;  
  
  Scanner input = new Scanner(System.in);  
  System.out.print("Mesafeyi giriniz (KM) : ");  
  km=input.nextInt();  
  
  total = km * kmbasina;  
  total += baslangic;  
  
  total = (total < 20) ? 20 : total;  
  System.out.println("toplam tutar : " + total);  
  
  }  
}
````