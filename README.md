# Java_Programs
Previous Asked Questions
//program to calculate total sum of 3 digit number or number contains 3 digit 
public class test1 
{
	public static void main(String[] args) 
	{
		int n=100;
		int count=0;
		for(int i=3;i<=n;i++)
		{
			int x=i;
			if(x%10==3)
			{
				count=count+i;
			}
			else 
			{
				x=x/10;
				if(x%10==3)
				{
					count=count+i;
				}
				else
				{
					x=x/10;
					if(x%10==3)
					{
						count=count+i;
					}
				}		
			}			
		}	
		System.out.println(count);
	}
}
