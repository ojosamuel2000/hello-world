# hello-world


package practice2;

import java.util.Scanner;

**
 *
 * @author PSALM
 */

public class Practice2 {
  /**
     * @param args the command line arguments
     */
     
public static void main(String[] args) {
        // TODO code application logic here
        
       Scanner kay = new Scanner(System.in);
        double fnumber, snumber, answer;
        System.out.println("Enter The First Number: ");
        fnumber = kay.nextDouble();
        System.out.println("Enter The Second Number: ");
        snumber = kay.nextDouble();
        answer = fnumber + snumber;
        System.out.println("The Answer is: " + answer);
        
        if (answer > 1000){
            System.out.println("Answer is Greater than 1000");
        }else {
            System.out.println("Answer is Less than 1000");
        }
        
    }
    
}
