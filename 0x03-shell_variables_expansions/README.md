alias ls="rm *" creates an alias
echo hello $user  prints hello user where user is current user
export PATH=$PATH:/action looks into this when looking for a programme
echo $PATH | tr -s ':' '\n' | wc -l scipt that count number of directories
printenv list environment variables
set list all local variables and environmental 
BEST=School creates new local variable
export BEST=School creates a new global variable
echo $(( 128+TRUEKNOWLEDGE)) prints results of the additiona of 128 with the value stored in environment variable
echo $((POWER / DIVIDE)) prints results of POWER divided by DIVIDE
echo $((BREATH ** LOVE)) displays the result of BREATH to the power LOVE
echo $(( 2#$BINARY)) converts a number from base 2 to base 10
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" prints all possible combination
printf "%.2f\n" $NUM prints a number with two decimal places.
