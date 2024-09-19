# java-quiz
/******************************************************************************

                            Online Java Compiler.
                Code, Compile, Run and Debug java program online.
Write your code in this editor and press "Run" button to execute it.

*******************************************************************************/
import java.util.Scanner;  // Import the Scanner class
public class Main {

    public static void main(String[] args) {
        Scanner myObj = new Scanner(System.in);  // Create a Scanner object


        //String input = myObj.nextLine();  // Read user input


        int siamesecat = 0;
        int ragdoll = 0;
        int tabby = 0;
        int maincoon = 0;
        String input;
        //-------------------------
        System.out.println("pick a color : (b)rown, (t)an,(w)hite,(g)ray");
        input = myObj.nextLine();  // Read user input

        if (input.equals( "b"))
            maincoon += 1;
        else if (input.equals( "t"))
            siamesecat += 1;
        else if (input.equals( "w"))
            ragdoll += 1;
        else if (input.equals( "g"))
            tabby += 1;
        else
            System.out.println("thats not an option duhhh");
        //-----------------------------------------------
        System.out.println("if you were to have a cat what length would the hair be : (m)eduim,(l)ong,(s)hort, (v)ery short");
        input = myObj.nextLine();
        if (input.equals( "m"))
            maincoon += 1;
        else if (input.equals( "l"))
            ragdoll += 1;
        else if (input.equals( "s"))
            siamesecat += 1;
        else if (input.equals( "v"))
            tabby += 1;
        //---------------------------------------------
        System.out.println("are you a furry????? : (y)es, (n)o, (m)aybe, (e)wwwwwww");
        input = myObj.nextLine();
        if (input.equals( "y"))
            siamesecat += 1;
        else if (input.equals( "n"))
            ragdoll += 1;
        else if (input .equals( "m"))
            maincoon += 1;
        else if (input .equals( "e"))
            tabby += 1;
        else
            System.out.println("stupiddddd thats not a option");
        //------------------------------------------------

        System.out.println("how often do climb stuff?: (o)ften, (r)are, (w)ho climbs stuff??? (n)ever");
        input = myObj.nextLine();
        if (input.equals( "o"))
            siamesecat += 1;
        else if (input.equals( "r"))
            maincoon += 1;
        else if (input.equals( "w"))
            tabby += 1;
        else if (input.equals( "n"))
            ragdoll += 1;
        else
            System.out.println("nah bro thats not an answer");
        //--------------------------------------------------
        System.out.println("in 3rd grade did u hiss at people?: (y)es, (n)ah bro werid ass mf, (p)lease save me im traped, (m)eh");
        input = myObj.nextLine();
        if (input.equals( "y"))
            siamesecat += 1;
        else if (input.equals( "n"))
            maincoon += 1;
        else if (input.equals( "p"))
            tabby += 1;
        else if (input.equals( "m"))
            ragdoll += 1;
        else
            System.out.println("nah bro thats not an answer");
        //---------------------------------------------------------------------- 
        System.out.println("if you had a tail what tail would it be?: (m)onkey tail, (d)og tail, (c)at tail, (e)www tails ");
        input = myObj.nextLine();
        if (input.equals( "d"))
            siamesecat += 1;
        else if (input.equals("c"))
            maincoon += 1;
        else if (input.equals( "e"))
            tabby += 1;
        else if (input.equals( "m"))
            ragdoll += 1;
        else
            System.out.println("nah bro thats not an answer");
        //------------------------------------------------------------------------ 
        System.out.println("if you were a cat girl what cat girl would you be: (d)og girl, (c)at girl, (f)ox girl, (B)EARRRR ");
        input = myObj.nextLine();
        if (input.equals( "c"))
            siamesecat += 1;
        else if (input.equals( "d"))
            maincoon += 1;
        else if (input.equals( "B"))
            tabby += 1;
        else if (input.equals( "f"))
            ragdoll += 1;
        else
            System.out.println("nah bro thats not an answer");
        //----------------------------------------------------------------------- 
        System.out.println(" are cats ears made out of bones: (y)es of course, (n)o wtf, (i)dek why would i know that, (I) love cats ");
        input = myObj.nextLine();
        if (input.equals( "y"))
            siamesecat += 1;
        else if (input.equals( "i"))
            maincoon += 1;
        else if (input.equals( "n"))
            tabby += 1;
        else if (input.equals( "I"))
            ragdoll += 1;
        else
            System.out.println("nah bro thats not an answer");
        //----------------------------------------------------------------------- 
        if (siamesecat >= maincoon && siamesecat >= tabby && siamesecat >= ragdoll) {
            System.out.println("ewwww your a furry and your a siamese cat but still ewwwww furry");

        }
        else if (maincoon >= tabby && maincoon >= ragdoll) {
            System.out.println("ur almsot a furry you just need a push ur a maincoon!!");

        }
        else if (tabby >= ragdoll && tabby >= maincoon) {
            System.out.println("ur the best cat tabby and best of all ur not a furry");

        }
        else if (ragdoll >= maincoon && ragdoll >= siamesecat) {
            System.out.println(" ur a ragdoll cat they are cute and have long hair good luck and ur a lowkey furry");

        }

    }

}
