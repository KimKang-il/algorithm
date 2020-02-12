package algorithm;

import java.util.Scanner;

public class Harshad {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		System.out.print("1~10,000까지의 수를 넣으세요...");
		int num = scan.nextInt();

		int x;
		int sum = 0;

		x = num;

		while (x / 10 != 0) {
			sum += x % 10;
			x = x / 10;
		}
		sum = sum + x;

		if (num % sum == 0) {
			System.out.println(num + "은 하쟈드 수 입니다.");
		} else {
			System.out.println(num + "은 하쟈드 수 아닙니다.");
		}

	}
}
