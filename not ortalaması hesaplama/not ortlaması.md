# Not Ortalaması Hesaplama

````
import java.util.Scanner;  
  
public class main {  
  
public static void main(String[] args){
  
 //değişkenleri tanımladım  
 
  int mat,turkce,tarih,muzik,fizik;  
  //Scanner tanımladım  
  Scanner input = new Scanner(System.in);  
  
  // Kullanıcıdan veri alıyorum  
  
  System.out.print("Matematik notunu giriniz: ");  
  mat = input.nextInt();  
  
  System.out.print("Türkçe notunu giriniz: ");  
  turkce = input.nextInt();  
  
  System.out.print("Tarih notunu giriniz: ");  
  tarih = input.nextInt();  
  
  System.out.print("Müzik notunu giriniz: ");  
  muzik = input.nextInt();  
  
  System.out.print("Fizik notunu giriniz: ");  
  fizik = input.nextInt();  
  
  // alınan verileri topluyorum ve ortalamsını buluyorum
 int toplam=(fizik+muzik+tarih+turkce+mat);  
 double ort=toplam / 5.0;  
 
  // ortalamayı ekrana yazdırıyorum
  
  System.out.println("Ortalamanız: "+ort);  
  
  
  }  
}
````