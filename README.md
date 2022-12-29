# Java
Java problems and Code
import java.util.*;

public class Table_01 {

  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);

    System.out.println("Enter the num you want table :");
    long num = sc.nextLong();

    for (int i = 1; i <= 10; i++) {
      long table = num * i;
      System.out.println(num + "*" + i + "=" + table);

    }

  }
}

