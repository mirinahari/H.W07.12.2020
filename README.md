# H.W07.12.2020
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("please enter num1 num2: ");
        int i = s.nextInt();
        int j = s.nextInt();
       // input two int numbers from the user, check if they are both zeros, if so print "both zeroes"
        // otherwise print "not both zeroes"
        //x=00;

        if  (i==0 && j==0) {
            System.out.println("both zeroes ");
        }
       else {
            System.out.println("not both zeroes");
        }

    //input a,b,c (int)
//    check if all numbers are different from each-other, if so print "diff" otherwise print "similar"
    System.out.println("please enter num1 num2 num3: ");
     int a = s.nextInt();
     int b = s.nextInt();
     int c = s.nextInt();

     if (a!=b && a!=c && b!=c){
     System.out.println("diff");
     }
    else {
    System.out.println("similar");
     }
    // input x,y,z (float)
        //    check and print how many of them are positive
        //    for example:
        //    for input of -1, 4 ,2.98 your program should print 2 positive numbers
        //    for input of -4.5, 0, -12 your program should print 0 positive numbers

     System.out.println("please enter num1 num2 num3: ");
     float x = s.nextFloat();
     float y = s.nextFloat();
     float z = s.nextFloat();

     int count = 0;
     if (x>0) {
     count++;
     }
     if (y>0) {
     count++;
     }
     if (z>0) {
     count++;
        }
     System.out.println(count + " " + "positive numbers");

    //input a, b, c.
        //   print the biggest
        //   hint: if a is bigger than b and bigger than c --> a biggest
        //       else if b is bigger than c --> b biggest
        //       else --> c biggest

        System.out.println("please enter 3 numbers: ");
        int d = s.nextInt();
        int e = s.nextInt();
        int f = s.nextInt();

        if (d>e && e>f) {
            System.out.println("a biggest");
        }
        else if (e>f) {
             System.out.println("b biggest");
         }
         else {
         System.out.println("c biggest");
         }


            }


    }


