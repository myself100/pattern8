# pattern8

import java.util.Scanner;
public class Pattern7 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		int k=1;
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				System.out.print(k + " ");
				k++;
			}
			System.out.println();
		}
	}
}

output :: 
5                               ////when n is 5
1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15 
