# just...
just....um...

	public static int lcm( int a, int b, int gcd  ) {
		return ( a * b / gcd );
	}

	public static int gcd( int a, int b) {
		int temp = a;

		while( b > 0 ) {

			temp = a % b;
			a = b;
			b = temp;
		}

		return a;
	}



