# KDV Tutarı hesaplama

````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
            //değişkenleri tanımladım  
  double tutar,kdvOrani=0.18,kdvTutar,kdvliTutar;  
  Scanner input = new Scanner(System.in);  
  
  System.out.print("Ücret Giriniz: ");  
  tutar = input.nextDouble();  
  
  kdvTutar=tutar * kdvOrani;  
  kdvliTutar= tutar + kdvTutar;  
  
  System.out.println("KDV'siz Tutar : "+ tutar);  
  System.out.println("KDV Oranı : "+ kdvOrani);  
  System.out.println("KDV Tutarı : "+ kdvTutar);  
  System.out.println("KDV'li Tutar : "+ kdvliTutar);  
  
  
  
  }  
}
````