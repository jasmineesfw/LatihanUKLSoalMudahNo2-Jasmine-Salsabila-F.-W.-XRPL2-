# LatihanUKLSoalMudahNo2-Jasmine-Salsabila-F.-W.-XRPL2-
Fungsi dari program ini adalah untuk mengetahui apakah bilangan tersebut ganjil atau genap. Lalu cara kerjanya adalah dengan cara menginputkan bilangan oleh user.

Berikut adalah kode programnya

    import java.util.Scanner;
    public class SoalMudahNo2 {
    public static void main(String[] args) {
        Scanner inputan = new Scanner(System.in);
        
        System.out.println("Masukkan Bilangan: ");
        int bilangan = inputan.nextInt();

        if(bilangan % 2 == 0) {
            System.out.println("Bilangan Genap");
        }
        else {
            System.out.println("Bilangan Ganjil");
        }

        inputan.close();
        }
    }
    
