# Harmonik-Say-lar-Bulan-Program
Java ile girilen sayının harmonik serisini bulan program yazacağız.
    import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("N sayısını giriniz : ");
        int n = inp.nextInt();
        double result = 0;

        for (double i = 1; i <= n; i++) {
            result +=(1/i);

        }
        System.out.println(result);


      }
    }
![image](https://user-images.githubusercontent.com/107626332/181189545-720bb3d9-b049-4915-9f69-fde1c0e2c70b.png)

https://app.patika.dev/ahmetfurkan
