import java.util.Scanner;

public class PuntajeExamen {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Número de respuestas correctas: ");
        int correctas = sc.nextInt();
        System.out.print("Número de respuestas incorrectas: ");
        int incorrectas = sc.nextInt();
        System.out.print("Número de respuestas en blanco: ");
        int enBlanco = sc.nextInt();

        int puntaje = (correctas * 4) - incorrectas;
        System.out.println("El puntaje final es: " + puntaje);
    }
}

