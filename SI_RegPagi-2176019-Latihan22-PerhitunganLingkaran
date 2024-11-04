/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package pertemuan6;

/**
 *
 * @author Afra Syavina
 */
import java.util.Scanner;

public class PerhitunganLingkaran {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double diameter = 0;
        boolean valid = false;
        
        System.out.println("=====Perhitungan Lingkaran=====");
        
        // Validasi input
        while (!valid) {
            System.out.print("Masukkan nilai diameter lingkaran: ");
            if (scanner.hasNextDouble()) {
                diameter = scanner.nextDouble();
                if (diameter > 0) {
                    valid = true;
                } else {
                    System.out.println("Nilai diameter harus lebih besar dari 0");
                }
            } else {
                System.out.println("Nilai diameter tidak sesuai");
                scanner.next(); // Membersihkan input yang salah
            }
        }
        
        // Perhitungan jari-jari, luas, dan keliling
        double radius = diameter / 2;
        double luas = Math.PI * radius * radius;
        double keliling = Math.PI * diameter;
        
        // Output hasil perhitungan
        System.out.println("=====Hasil Perhitungan Lingkaran=====");
        System.out.printf("Jari-jari Lingkaran = %.2f cm%n", radius);
        System.out.printf("Luas Lingkaran = %.2f cm%n", luas);
        System.out.printf("Keliling Lingkaran = %.2f cm%n", keliling);
        System.out.println("(Developed by: [Nama Anda])");
    }
}

