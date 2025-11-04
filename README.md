import java.util.Scanner;

public class SoalSedang2 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan jari-jari tabung: ");
        double r = input.nextDouble();

        System.out.print("Masukkan tinggi tabung: ");
        double t = input.nextDouble();

        double volume = hitungVolume(r, t);
        System.out.println("Volume tabung = " + volume);
    }

    public static double hitungVolume(double r, double t) {
        return Math.PI * r * r * t;
    }
}


Program ini menggunakan fungsi (method) dengan parameter jari-jari dan tinggi untuk menghitung volume tabung.
