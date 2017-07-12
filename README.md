# reversing-array-elements

import java.io.*;
import java.util.*;


public class Solution {

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int n = in.nextInt();
        int[] arr = new int[n];
                                //System.out.print(arr.length);


                
        for(n = 0;n<arr.length;n++){
            arr[n] = in.nextInt();            
        }    
        
        for(n=arr.length-1;n!=-1;n--){
            System.out.print(arr[n]);
            System.out.print(" ");
        }
        in.close();
    }
}
