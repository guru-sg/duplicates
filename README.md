# duplicates
to find duplicates in a T[] one-dimensional array of integers in O(N) running time 
                      
		          import java.util.*;
			  public class Main
			  {
			    public static void main(String[] args) {
				Scanner sc = new Scanner(System.in);
				int i;
				System.out.println("ENTER THE NO.OF ELEMENTS IN THE ARRAY: ");
				int n = sc.nextInt();
				int arr[] = new int[n];
				System.out.println("ENTER  ELEMENTS OF THE ARRAY: ");
				for(i = 0; i < n; i++)
				{
				    arr[sc.nextInt()]+=1;
			        }
			        for(i = 0; i < n; i++)
				{
				    if(arr[i]>1)
				    {
				       System.out.println(i);
				    }
			        }
			    }
			  }
