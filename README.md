PrintTriangleInConsole
======================
package rect;

public class PrintTriangle {
	public static void main(String[] args) {

		int a = 3;
		int b = 5;
		int j = 0;
		int k = 0;
		String space = " ";

		System.out.print(" + \n ++");
		System.out.print("\n +");

		while (j != a-2) {
			space = space + " ";
			System.out.print(space);
			j++;
			System.out.print("+ \n +");
		}
		System.out.print(space+space);
		System.out.print("+ \n"+" ");
		
		while(k!=b+3){
			System.out.print("+");
			k++;
		}
	}

}
