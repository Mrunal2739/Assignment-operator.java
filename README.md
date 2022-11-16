# Assignment-operator.java

/*Assignment Operators */

import java.util.*;

class operator{

public static void main(String[] args){

Scanner sc = new Scanner(System.in);

System.out.println("Enter first number:");

int a = sc.nextInt();

System.out.println("Enter second number:");

int b = sc.nextInt();

System.out.println("+= operator:"+(a+=b));

System.out.println("-= operator:"+(a-=b));

System.out.println("= operator:"+(a=b));

System.out.println("/=operator:"+(a/=b));

System.out.println("%= operator:"+(a%=b));

}

}
