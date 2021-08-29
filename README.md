# ejercicio11
actividad
package ejercicio11;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercicio11 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner numero = new Scanner (System.in);
        int num;
        int cen;
        int dec;
        int uni;
        int res;
         
       System.out.print("Ingrese numero");
       num = numero.nextInt();
       
       cen = num/100;
       res = num -(cen*100);
       dec = res/10;
       uni = res - (dec*10);
       
       System.out.println("centena es:"+cen);
       System.out.println("decena es:"+dec);
       System.out.println("unidad es:"+uni);
       
        
        // TODO code application logic here
    }
    
}
