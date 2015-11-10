# Second
package javaapplication1;  public class JavaApplication1 {      public static void main(String[] args) {          int k,p,l,s;         k = 8902;         p = 0;         s = 0;         while (k > 0){             l = k%10;              p = l%2;              if (p == 0){                 s += l;}              k = k/10;}        System.out.println(s);     }          }
