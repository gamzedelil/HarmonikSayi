# HarmonikSayi

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	
		
		Scanner input = new Scanner(System.in);
		
		System.out.println(" n sayisini girin:");
		int n = input.nextInt();

		double sonuc = 0;
		
		
		for(double i=1; i<=n; i++){
		sonuc += (1/i);
		}
		
		System.out.println("Sonuc:" +sonuc);

      }
}
