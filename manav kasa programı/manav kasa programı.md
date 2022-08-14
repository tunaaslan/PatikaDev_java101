# Manav Kasa Programı
````
import java.util.Scanner;  
  
public class main {  
  
    public static void main(String[] args) {  
  
        int elma,armut,domates,muz,patlican;  
 double sonuc=0;  
  
  Scanner input= new Scanner(System.in);  
  System.out.print("kaç kg elma aldınız: ");  
  elma=input.nextInt();  
  sonuc += elma*3.67;  
  
  System.out.print("kaç kg armut aldınız: ");  
  armut=input.nextInt();  
  sonuc += armut*2.14;  
  
  System.out.print("kaç kg domates aldınız: ");  
  domates=input.nextInt();  
  sonuc += domates*1.11;  
  
  System.out.print("kaç kg muz aldınız: ");  
  muz=input.nextInt();  
  sonuc += muz*0.95;  
  
  System.out.print("kaç kg patlıcan aldınız: ");  
  patlican=input.nextInt();  
  sonuc += armut*5.00;  
  
  
  System.out.print("tutar TL: "+sonuc);  
  

  }  
}
````