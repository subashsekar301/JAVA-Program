# JAVA-Basic-Program
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner (System.in);
	    
	    int x=sc.nextInt();
	    for(int i=1;i<x;i++){
	        for(int j=1;j<x;j++){
	            if(i==1||i==3||i==5||i==2&&j==1||i==4&&j==5)
	            {
	                  System.out.print("*");
	            }
	            else{
	                System.out.print(" ");
	            }
	        }
	             System.out.println( );
	      }
	}
}

 ----------------------------------------------------------------------
 import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int sum=0;
	    int []arr=new int[n];
	    for(int i=0;i<arr.length;i++){
	        arr[i]=sc.nextInt();
	    System.out.println(arr[i]+" ");
	}
	}
}

-------------------------------------------------------


import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int []arr=new int[n];
	    for(int i=0;i<=arr.length;i++){
	        arr[i]=sc.nextInt();
	    System.out.println(arr[i]);
	}
	}
}

---------------------------------------------------------

import java.util.*;
public class Main
{
	public static void main(String[] args){
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int []arr=new int[n];
	    int temp;
	    for(int i=0;i<=n;i++){
	        arr[i]=sc.nextInt();
	}
	    for(int i=0;i<n-1;i+=2){
	    temp=arr[i];
	    arr[i]=arr[i+1];
	    arr[i+1]=temp;
	}
	    for(int i=0;i<n;i++)
	{
	    System.out.println(arr[i]);
	}
	}
}

-------------------------------------------------------

import java.util.*;
public class Main
{
	public static void main(String[] args){
	    Scanner sc=new Scanner(System.in);
        int r=sc.nextInt();
        int c=sc.nextInt();
        int arr[][]=new int[r][c];
        int i,j;
        for(i=0;i<r;i++){
            for(j=0;j<c;j++){
                arr[i][j]=sc.nextInt();
            }
        }
     
	}
}


	    
