# DaireninAlani
```
[patika.dev]([
](https://app.patika.dev/iremr)
```
import java.util.Scanner;


public class DaireninAlanı {
    public static void main(String[] args) {
        int r,a;
        double pi = 3.14,alan;
        Scanner input = new Scanner(System.in);

        System.out.print("Yarıçapı giriniz: ");
        r = input.nextInt();

        System.out.print("Merkez açısının ölçüsünü giriniz: ");
        a = input.nextInt();

        alan = pi * r * r * a /360;
        System.out.println("Daire diliminin alanı: " + alan);


    }
}
```
[patika.dev](https://app.patika.dev/iremr)
