import java.util.Scanner;
import java.util.Random;

public class Main {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        int numeroSecreto = new Random().nextInt(101);
        int intentos = 5;
        System.out.println(numeroSecreto);
        System.out.println("Tienes " + intentos + " intentos restantes.");

        int num_ingresado = 0;

        do {

            System.out.println("Tienes " + intentos + " intentos restantes.");
            num_ingresado = sc.nextInt();

            if (num_ingresado == numeroSecreto)
            {
                System.out.println("Felicidades, acertaste");
                break;
            }
            else if (num_ingresado < numeroSecreto)
            {
                System.out.println("El numero es mayor");
            }
            else
            {
                System.out.println("El numero es menor");
            }

            intentos--;

        }while (intentos > 0);

    }
}

