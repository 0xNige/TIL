# Displaying hex values with printf

Rather than doing:

	printf("0x%X", 0x90);

and getting 0x90

We can just do:

	printf("%#X", 0x90);
	
and get 0x90

The compiler will add the '0x' if we use the '#' symbol after %. :)
