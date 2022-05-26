# 3-ve-4-e-bolunen-sayilar

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int number, count=0;
        int total =0;
        double average;

        Scanner input = new Scanner(System.in);
        System.out.println("Bir sayı giriniz: ");

        number = input.nextInt();

        for (int i=1; i<=number;i++){
            if (i%3==0 && i%4==0){
                total = total + i;
                count++;

            }
        }
            average = total/count;
            System.out.println(average);
    }
}
