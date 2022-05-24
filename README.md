# burcc
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int month, day;

        Scanner input = new Scanner(System.in);


        System.out.println("Dogdugunuz ay: 1-12 seçiniz  : ");
        month = input.nextInt();

        System.out.println("Dogdugunuz gun : 1-31 arasi sayı seçiniz");
        day = input.nextInt();


        if (month == 1) {
            if (day > 0 && day < 22) {
                System.out.println("oglak BUrcu");
            } else if (day >= 22 && day <= 31) {
                System.out.println("KOva burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 2) {
            if (day > 0 && day <= 19) {
                System.out.println("K0va BUrcu");
            } else if (day > 19 && day <= 31) {
                System.out.println("Balik burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 3) {
            if (day > 0 && day <= 20) {
                System.out.println("Balik BUrcu");
            } else if (day > 21 && day <= 31) {
                System.out.println("Koc burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 4) {
            if (day > 0 && day <= 20) {
                System.out.println("koc BUrcu");
            } else if (day > 21 && day <= 31) {
                System.out.println("Boga burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 5) {
            if (day > 0 && day <= 21) {
                System.out.println("Boga Burcu");
            } else if (day > 21 && day <= 31) {
                System.out.println("ikizler burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 6) {
            if (day > 0 && day <= 22) {
                System.out.println("ikizler Burcu");
            } else if (day > 22 && day <= 31) {
                System.out.println("yengec burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 7) {
            if (day > 0 && day <= 22) {
                System.out.println("yengec Burcu");
            } else if (day > 22 && day <= 31) {
                System.out.println("Basak burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 8) {
            if (day > 0 && day <= 23) {
                System.out.println("basak Burcu");
            } else if (day > 23 && day <= 31) {
                System.out.println("Terazi burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 9) {
            if (day > 0 && day <= 23) {
                System.out.println("terazi Burcu");
            } else if (day > 23 && day <= 31) {
                System.out.println("Akrep burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 10) {
            if (day > 0 && day <= 23) {
                System.out.println("Akrep Burcu");
            } else if (day > 23 && day <= 31) {
                System.out.println("Yay burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 11) {
            if (day > 0 && day <= 21) {
                System.out.println("akrep Burcu");
            } else if (day > 21 && day <= 31) {
                System.out.println("Yay burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }

        if (month == 12) {
            if (day > 0 && day <= 21) {
                System.out.println("yay Burcu");
            } else if (day > 21 && day <= 31) {
                System.out.println("oglak burcu");
            } else {
                System.out.println("Hata ! 1-31 arasında sayi giriniz");
            }
        }
    }
}
