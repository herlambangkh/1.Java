package com.jawaban;

import java.util.*;

public class Main {

    public static void main(String[] args) {

     String[] stringArray = {"4programmer","6dan","3seorang","5java","2adalah","1aku","9soal","8mengerjakan"};
        System.out.println("UNSORTED STRING AWAY:");
        for (String x : stringArray) {
            System.out.print(x+" ");
        }
        System.out.println();
        Arrays.sort(stringArray);

        System.out.println("\nSORTED STRING ARRAY:");
        for (String x: stringArray) {
            System.out.print(x+" ");
        }


    }

}
