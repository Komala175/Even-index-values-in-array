# Even-index-values-in-array
import java.util.*;
class Main{
	public static void main(String[] args) {
      Scanner sc=new Scanner(System.in);
      System.out.println("Elements size  of array:");
      int a=sc.nextInt();
      int arr[]=new int[a];
      for(int i=0;i<a;i++) {
    	  System.out.println("index values:"+i);
      
       arr[i]=sc.nextInt();
	}
      for(int i=0;i<a;i++) {
    	  if(i%2!=0) {
    		  System.out.println("the even index is:"+arr[i]);
    	  }
      }
      
}
