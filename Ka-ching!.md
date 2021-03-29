import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        
        Scanner input = new Scanner(System.in);
        List<String> count = new ArrayList<>();


        while (true) {

            count.add(input.next());

            if (count.size() % 3 == 0 && count.size() % 4 == 0) 
            {
                System.out.println("ka-ching!");
            } 
            else if (count.size() % 4 == 0)
            {
                System.out.println("ching!");
            }

                    }

    }
    }
