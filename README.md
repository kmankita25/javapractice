import java.util.Scanner;

/**
 * Created by ankita on 03-06-2023.
 * *Example:*
 For instance, if the input string is "Hello, World!",
 the program should output the reversed string as "!dlroW ,olleH".
 */
public class StringProgram {
    public static void main(String[] args) {

    String s="Hello, World!";
        String rev="";
        char ch[]=s.toCharArray();
        for (int i=ch.length-1;i>=0;i--)
        {
            rev=rev+ch[i];
        }
        System.out.println("rev"+rev);
    }

}



