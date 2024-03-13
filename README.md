import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner in = new Scanner(System.in);
	    int n =in.nextInt();
	    int [] arr = new int[n];
	    int temp;
	    int i;
	    for(i=0;i<n-1;i++){
	        arr[i]=in.nextInt();
	    }
	    for(i=0;i<=n;i+=2){
	        temp = arr[i];
	        arr[i] = arr[i+1];
	        arr[i+1] = temp;
	        }
	        for (i=0;i<=n;i++)
	        System.out.println(arr[i] +" ");
	}
}
