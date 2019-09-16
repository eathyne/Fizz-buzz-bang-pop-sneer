# Fizz-buzz-bang-pop-sneer
package com.company;

import javax.swing.*;

public class Main {

    public static void main(String[] args) {
        for (int x = 1; x <= 100; x++) {
            System.out.println(x);
            if (x % 3 == 0) {
                System.out.println("fizz");

            }
                else if(x%5==0){
                    System.out.println("buzz");

            }
                else if (x==7){
                    System.out.println("bang");

            }
                else if(x==11)
            {
                System.out.println("pop");

            }
           else if(x==23)
            {
                System.out.println("sneer");
            }
        }
    }
}
