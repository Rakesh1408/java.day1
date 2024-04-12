# java.day1
import java.util.Arrays;
import java.util.Scanner;
import java.lang.Math;
public class hai{
  public static void printj(){
    System.out.println("hi");
  }
  public static void main(String[] args){
    
    // System.out.println("Hello World");
    // System.out.println("its ok");
    // String s="aman";
    // int a=12;
    // System.out.println(s);
    // String k=s;
    // s="ji";
    // System.out.println(s);
    // int[] marks=new int[3];
    // int[] k=new int[2];
    // k[0]=1;
    // k[1]=0;
    // System.out.println(k[0]);
    // Arrays.sort(k);
    // System.out.println(k[0]);
    //  double t=11.43;
    //  int i=11;
    //  int k=(int)t+i;
    //  System.out.println(k);
    //  double modulo=t%i;
    //  System.out.println(modulo);
    //  int age=12;
    //  System.out.println(age);
    //  Scanner sc =new Scanner(System.in);
    //  age=sc.nextInt();
    //  System.out.println(age);
    //printj();
    Scanner sc=new Scanner(System.in);
    int j=(int)(Math.random()*100);
    System.out.println(j);
    
    while(true){
      System.out.println("Enter the number");
      int h=sc.nextInt();
      if(h>j){
        System.out.println("to high");

      }
      else if(h==j){
        System.out.println("Correct");
        break;
      }
      else{
        System.out.println("to low");
      }
    }



  }

 
}
