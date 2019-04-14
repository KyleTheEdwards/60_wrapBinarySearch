A logarithm is simply the inverse of an exponent.

When someone writes log2(64), we are saying "What power can we raise 2 to in order to get 64?"

Logarithms are written in this form:

logb(n) = x

This means:

b ^ x = n

The graph of y=log(x) is just the graph of 10^x translated over the y = x line.

![Graph of y=log2(x)](https://www.varsitytutors.com/assets/vt-hotmath-legacy/hotmath_help/topics/graphing-logarithmic-functions/f-gr-log-fn_1_4_1.gif)


For the recursive solution to findMe:

l. The problem is searching for a specific value in a given list of a certain size
l. The recursive abstraction can represent the comparison between the middle of the given list and the desired output
l. The 6 parts of the solution:
	l. We decide if we are at the base case if the middle of the given list is equal to the desired value
	l. Since this is more of an exercise in tail recursion, there is not any real combination that needs to be done
	l. The result of the recursive abstraction is a list whose starting and/or ending points lead to a middle value whose index is closer to the index of the desired value
	l. We process the result as is, meaning we return the middle of the given list's index since it's the same as the desired value