# searching-element-in-array
searching an element in array

import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
     
     int classRoll[] = {1,2,4,5,6,3,7,8};
     
     int findRoll = 3;
     
     for(int i=0; i<8; i++){
       if ( classRoll[i] == findRoll){
         System.out.println("CR index is " + i);
       }
       else{
         System.out.println("cr not found");
       }
       
     }
  }
}


2nd process e.g taking user input

import java.util.*;

public class Main {
    public static void main(String[] args) {
     
     int classRoll[] = {1,2,4,5,6,3,7,8};
     
     //int findRoll = 3;
     Scanner sc = new Scanner(System.in);
     int myRoll = sc.nextInt();
     
     for(int i=0; i<8; i++){
       if ( classRoll[i] == myRoll){
         System.out.println("CR index is " + i);
       }
       else{
         System.out.println("cr not found");
       }
       
     }
  }
}
