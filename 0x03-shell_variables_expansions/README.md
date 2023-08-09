alias ls="rm*" : command name ls with value remove all.

echo "hello $USER": to print hello current user name .

export PATH="$PATH:/action": to Add nwmew path to the fle PATH at the end of the file.

echo $PATH | tr ":" "\n" | wc -l: count the number of the directory in thr PATH file.

printenv : print lists environment variables.

ste : print lists all local variables and environment variables, and functions.

varname="value" : create local variable with value.

export varname="value" : create global variable with value.

echo $((128 + $TRUEKNOWLEDGE)): prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE .
	
echo $(($POWER / $DIVIDE)): prints the result of POWER divided by DIVIDE.

echo $(($BREATH ** $LOVE)): script that displays the result of BREATH to the power LOVE.

echo $((2#$BINARY)): converts a number from base 2 to base 10.The number in base 2 is stored in the environment variable BINARY.

