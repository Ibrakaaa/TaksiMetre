# TaksiMetre
### Java-101 Taksimetre Hesaplayıcı
(www.patika.dev)


import java.util.Scanner;

public class TaksiMetre {
    public static void main(String[] args) {

        int acilis = 10;
        double yol;
        double Km = 2.20;
        double toplam;
        double toplam1;


        Scanner mesafe=new Scanner(System.in);

        System.out.print("Lütfen Gitmek İstediğiniz Lokasyonun Uzaklığını Giriniz: ");
        yol = mesafe.nextDouble();

        System.out.println("Seçtiğiniz Mesafe: "+yol+" Km");

        if(yol<5){
            toplam = 20;
            System.out.println("Toplam Ücret"+toplam+" TL");

        }

        else{
            toplam1 = (yol*Km) + acilis;
            System.out.println("Toplam ÜCret: "+toplam1+" TL");
        }

        
    }
    }
