# grading
import java.util.Scanner;
public class NotOrtalamasi {


    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int math, phys, chem, turkish, hist, art;

        System.out.println("Matematik notu giriniz: ");
        math = scan.nextInt();

        System.out.println("Fizik notu giriniz: ");
        phys = scan.nextInt();

        System.out.println("Kimya notu giriniz: ");
        chem = scan.nextInt();

        System.out.println("Türkçe notu giriniz: ");
        turkish = scan.nextInt();

        System.out.println("Tarih notu giriniz: ");
        hist = scan.nextInt();

        System.out.println("Müzik notu giriniz: ");
        art = scan.nextInt();

        scan.close();

        int avg = (math + phys + chem + turkish + hist + art) / 6;
        String result = (avg >= 60) ? "Sınıfı geçti" : "Sınıfta kaldı";
        System.out.println("Ortalama: " + ortalama + ".  " + sonuc);

    }
}
