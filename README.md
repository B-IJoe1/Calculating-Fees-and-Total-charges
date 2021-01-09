# Calculating-Fees-and-Total-charges
# Calculating fees for a specific amount of hours 


public static void calculateCharges()
{
	//User input 
	Scanner input=new Scanner(System.in);
	System.out.println("Please Enter the number of hours");
	double hours=input.nextDouble();
	
	double fee=2;
	if(hours<=3) {
		
	
fee=2;
System.out.println("Your total fee is = " + fee);

		}
	else if(hours>3 && (hours<24)) {
		double fee2;
		fee2=fee+(hours-3)*0.5;
		System.out.println("Your total fee is = " + fee2);
		
		
	}
		 if(hours==24)
		{
			
			double fee3=10;
			System.out.println("Your toral fees are= "+ fee3);
		}
	}

}


