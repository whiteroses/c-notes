# Functions

* "If the } that terminates a function is reached, and the value of the function call is used by the caller, the behavior is undefined." (N2176 6.9.1 12)
	* This is referring to non-`main()` functions.
	* Warning from `-Wreturn-type` and `-Wall`.
