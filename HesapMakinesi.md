import java.util.Scanner;

public class CokluDersCalisma {

public static void main(String[] args) {

Scanner bar = new Scanner(System.in);

int sayı1, sayı2, sec;

System.out.print("Birinci sayı girin :");

sayı1 = bar.nextInt();

System.out.print("İkinci sayı girin :");

sayı2 = bar.nextInt();

System.out.println("1-Toplama\n2-Cıkarma\n3-Carpma\n4-Bolme");

System.out.print("Secimin :");

sec = bar.nextInt();

 switch (sec) {

case 1:

System.out.print("Toplam :" + sayı1 + sayı2);

case 2:

System.out.print("Cıkarma Sonucu :" + (sayı1 - sayı2));

break;

case 3:

System.out.print("Carpma Sonuc :" + sayı1 * sayı2);

break;

case 4:

if (sayı2 != 0) {

System.out.println("Bolme Sonuc :" + sayı1 / sayı2);

} 

else {

System.out.println("Bir sayi 0'a bolunemez .");

}
                
break;
            
default:
                
System.out.println("Hatali Giris Yaptiniz !!!");

    }

}