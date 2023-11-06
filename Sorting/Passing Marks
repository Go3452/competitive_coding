import java.util.Scanner;

class Codechef
{
	public static void main (String[] args) 
	{
	 Scanner sc = new Scanner(System.in);
	 int t = sc.nextInt();
	 for(int i=0;i<t;i++)
	 {
	  int n = sc.nextInt();
	  int x = sc.nextInt();
	  int a[] = new int[n];
	  for(int j=0;j<n;j++)
	   a[j] = sc.nextInt();
	  for(int j=0;j<n-1;j++)
	  {
	   for(int k=0;k<n-1-j;k++)
	   {
	    if(a[k]>a[k+1])
	    {
	     int temp;
	     temp = a[k];
	     a[k] = a[k+1];
	     a[k+1] = temp;
	    }
	   }
	  }
	    int c = a[n-x] - 1;
	    System.out.println(c);
	 }
	}
}
