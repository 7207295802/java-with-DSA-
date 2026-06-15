#H/M
Basic of java
Control statements
operators
String with methods and function
function
oop's
multithrading
array


# java-with-DSA-
1.Array
2.LinkedList
3.Stack
4.Queue
5.Trees
6.Graph
7.Sorting techniques
8.Searching technique
9.Algorithm

#day1 num
import java.util.*;
import java.lang.*;
class Main {
    public static void main(String[] args) {
        Scanner obj=new Scanner(System.in);
        int n=obj.nextInt();
        String Binary=" ";
        while(n>0){
            int rem=n%2;
            Binary =rem +Binary;
            n=n/2;
        }
        System.out.println(Binary);
    }
}



// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.*;
class Main {
    public static void main(String[] args) {
        Scanner obj=new Scanner(System.in);
        int a=obj.nextInt();
        if((a&1)==0){
            System.out.println("even");
        }else{
            System.out.println("odd");
        }
    }
}
