# java-test-0001-final-12162-hanumansingh
Final Project Assignment - This repository contains the complete final project code and documentation.
public class Main {
    public static void main(String[] args) {

        int n = 4;

        // upper part
        for(int i = 1; i <= n; i++){
            
            for(int j = 1; j < i; j++){
                System.out.print(" ");
            }

            System.out.print("*");

            for(int k = 1; k <= (2*(n-i)); k++){
                System.out.print(" ");
            }

            if(i != n){
                System.out.print("*");
            }

            System.out.println();
        }
    }
}
