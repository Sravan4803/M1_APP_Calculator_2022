1.1	Test Plan
ID	Description	Pre-Condition	Expected Input	Expected Output	Actual Output
HL1_L1	Addition of values	Choose addition from all options	Two int operands 	Sum of the two operands	
HL1_L1	Addition of values	Choose addition from all options	Any one int operand >= to 65535	Error as int return value can only give 65535	
HL1_L2	Subtraction of values	Choose subtract from all options	Two int operands 	difference of the two operands	
HL1_L2	Subtraction of values	Choose subtract from all options	Any one int operand >= to 65535	Error as int return value can only give 65535	
HL1_L3	Multiplication of values	Choose multiply from all the options	Two int operands	Product of two operands	
HL1_L4	Division of values	Choose divide from all the options	Two non zero int operands 	division of two operands	
HL1_L4	Division of values	Choose divide from all the options	Two int operands with divisor 0	Divide by 0 error	
HL2_L1	Nth Power	Choose Power from all the options	Two non zero int operands	Operand1 raised to power of operand2	
HL2_L1	Nth Power	Choose Power from all the options	Two int operands with operand2 =0	Return 1	
HL2_L2	Square	Choose Square from all the options	One int operand  	Returns operand raised to power 2	
HL2_L3	Factorial	Choose factorial from all the options	One int operand non zero and non negative	Returns factorial of operand	
HL2_L3	Factorial	Choose factorial from all the options	One int operand equal to 0	Returns 1	
HL2_L3	Factorial	Choose factorial from all the options	One int operand negative	Error and return -1	
HL2_L4	Greater	Choose Greater from all the options	Two int operands	Greater of operand1 and operand 2	
HL2_L5	Smaller	Choose Smaller from all the options	Two int operands	Smaller of operand1 and operand 2	
HL2_L6	Prime	Choose prime from all the options	One int operand non zero and non negative	Returns if prime or not	
HL2_L6	Prime	Choose prime from all the options	One int operand equal to 0 or 1	Error and returns -1	
HL2_L6	Prime	Choose prime from all the options	One int operand negative	Error and return -1	
HL2_L7	Modulus	Choose modulus from all the options	Two int operands 	Returns the remainder	
HL2_L8	Square root	Choose modulus from all the options	One int operand	Returns float value of square root of operand1 	
HL3_L1	Sin Value	Choose sinvalue from all the options	One float operand	Returns sine of operand1 in float 	
HL3_L2	Cos Value	Choose cosvalue from all the options	One float operand	Returns cosine of operand1 in float 	
HL3_L3	Tan Value	Choose tanvalue from all the options	One float operand not 90 degrees	Returns sine of operand1 tangent in float 	
HL3_L3	Tan Value	Choose tanvalue from all the options	One float operand equal 90 degrees	Error as value not defined returns -1 	
HL4_L1	Centimeter to meter	Choose CMTOM from all the options	One float operand  	Returns value in meters in float	
HL4_L2	Meter to centimeter	Choose MTOCM from all the options	One float operand  	Returns value in centimeters in float	
HL4_L3	Meter to kilometer	Choose MTOKM from all the options	One float operand  	Returns value in kilometers in float	
HL4_L4	Kilometer to meter	Choose KMTOM from all the options	One float operand  	Returns value in meters in float	
HL4_L5	Inch to centimeter	Choose INCHTOM from all the options	One float operand  	Returns value in centimeters in float	
HL4_L6	Centimeter to inch	Choose MTOINCH from all the options	One float operand  	Returns value in inches in float	
	
Table 1 Test Plan for multi use calculator

