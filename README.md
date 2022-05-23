# CalificacionesS
Algoritmo de Calificaciones Sencillo

package algoritmo.promedio;
import java.util.Scanner;
public class AlgoritmoPromedio {
    public static void main(String[] args) {
        Scanner S = new Scanner(System.in);
        double cal1,cal2,cal3,p;
        System.out.println("Dame la calificacion 1: ");
        cal1 = S.nextDouble();
        System.out.println("Dame la calificacion 2: ");
        cal2 = S.nextDouble();
        System.out.println("Dame la calificacion 3: ");
        cal3 = S.nextDouble();
        p = (cal1+cal2+cal3)/3;
        if(p >= 6){
            System.out.println("Acreditado"+p);
        }
        else{
            System.out.println(" NO Acreditado"+p);
    }
    }
}
