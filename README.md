# Java-HavaS-cakliginaGoreEtkinlikOnerme
Java-HavaSıcakliginaGoreEtkinlikOnerme

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int heat;

        Scanner input = new Scanner(System.in);
        System.out.print("Sıcaklık giriniz : ");
        heat = input.nextInt();

        if (heat < 5){
            System.out.println("Kayak yapabilirsin.");
        }else if (heat >= 10 && heat <= 15){
            System.out.println("Sinemaya veya pikniğe gidebilirsin.");
        }else if (heat >= 25){
            System.out.println("Yüzmeye gidebilirsin.");
        }else if (heat >= 5 && heat < 10) {
            System.out.println("Sinemaya gidebilirsin.");
        }else if (heat > 15 && heat < 25) {
            System.out.println("Pikniğe gidebilirsin.");
        }
    }

}
