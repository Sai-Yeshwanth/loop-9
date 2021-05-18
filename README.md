public class Jala {

	public static void main(String[] args) {
		int n=7,a=0;
		int sum=0;
		int temp;
		temp=n;
		for(int i=2;i<n/2;i++)
		{
			if(n%i==0)
			{
				System.out.println("Given Number is not prime");
				a=1;
				break;
			}
		}
		if(a==0)
		{
			System.out.println("number is prime");
		}
		
	}
}
