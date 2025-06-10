#alias ls='rm *'
A script that creates an alias.

#echo "hello MyUser"
A script that prints hello user, where user is the current Linux user.

#export PATH="$PATH:/action"
A script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

#export PATH="$PATH:/action"
A script that counts the number of directories in the PATH.

#printenv
A script that lists environment variables.

#( set; declare -f 
A script that lists all local variables and environment variables, and functions.

#BEST="School"
A script that creates a new local variable.

#export BEST="School"
A script that creates a new global variable.

#echo $((128 + TRUEKNOWLEDGE))
A script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

#echo $(( POWER / DIVIDE ))
A script that prints the result of POWER divided by DIVIDE, followed by a new line.

#echo $(( BREATH ** LOVE ))
A script that displays the result of BREATH to the power LOVE

#echo "$((2#$BINARY))"
A script that converts a number from base 2 to base 10.

#printf '%s\n' {a..z}{a..z} | grep -v '^oo$'
A script that script that prints all possible combinations of two letters, except oo.

#printf "%.2f\n" "$NUM"
A script that prints a number with two decimal places, followed by a new line.
