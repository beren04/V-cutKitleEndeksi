package first;

import java.util.Scanner;

public class VucutKitleEndeksi {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Boyunuzu giriniz:");
        double boy = input.nextDouble();
        System.out.print("Kilonuzu giriniz:");
        double kilo = input.nextDouble();
        System.out.print("Vücut kitle Endeksiniz:"+(kilo/(boy*boy)));

    }
}
