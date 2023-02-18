package giai.thua;
import java.util.Scanner;
/**
 *
 * @author thy12
 */
public class GiaiThua {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int number, temp = 1;
        long giaithua;
        giaithua = 1;
     Scanner scanner = new Scanner(System.in);
     do {
            System.out.println("nhap 1 so: ");
            number = scanner.nextInt();
        } while ((number <= 0) || (number > 10));
     while (temp <= number) {
            giaithua *= temp;
            temp++;
        }
         
        System.out.println(number + "! = " + giaithua);
    }
 
}
         
