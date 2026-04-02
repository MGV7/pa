[app.java](https://github.com/user-attachments/files/26425048/app.java)
import java.util.Scanner;

public class app {
        public static void main(String[] args) throws Exception {
        Scanner sc = new Scanner(System.in);
        
        System.out.print("qual numero voce deseja multiplicar? "); 
        int numero = sc.nextInt();

        System.out.print("aqui está a tabuada do " + numero + ": ");

        for (int a = 1; a <= 10; a++) {
        System.out.println(a + " X " + numero + " = " + (numero * a) + " " );    
        }
        
        sc.close();


    }
}
