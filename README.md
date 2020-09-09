# ReadText
import java.util.Scanner;

public class ReadText {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        String Input = scanner.nextLine();

        int i = 0;
        while (!(Input.equalsIgnoreCase("Stop"))){

             Input = scanner.nextLine();

             i++;
        }

        System.out.println(i);
    }
}
