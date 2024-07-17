# multiplication-table-upto-number-10
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Input a number: ");
        int a= sc.nextInt();
        for(int i=0;i<10;i++){
            System.out.println(a + " x " + (i + 1) + " = " + (a * (i + 1)));
        }
    }
}
