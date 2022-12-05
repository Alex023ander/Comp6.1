# Comp6.1


public static void main(String[] args) {
		int n; // variable declaration

        Scanner s = new Scanner(System.in);

        System.out.println("Enter an even number which is greater than 2:");

        n= s.nextInt(); // accept the number

        if(n<2) // number is less than 2
{

            System.out.println("The number "+n+" is less than 2:");

            System.exit( 0 );
}

        if (( n % 2 ) != 0 ) // The number is odd
{

            System.out.println("The number "+n+" is not even." );

            System.exit( 0 );
}

        int sum = 0;

        for ( int i = 2; i <= n; i += 2 )

{

            sum += i; // Sum of even numbers from 2 to the number
}

        System.out.println( "The sum of all even numbers from 2 to " + n +" is " + sum );
}


	}
