Files to submit
trimatoi.go

Allowed functions
github.com/01-edu/z01.PrintRune, --allow-builtin

Instructions
Write a function that transforms numbers within a string, into an int.

If the - sign is encountered before any number it should determine the sign of the returned int.

This function should only return an int. In the case of an invalid input, the function should return 0.

Note: There will never be more than one sign in a string in the tests.

Expected function
func TrimAtoi(s string) int {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.TrimAtoi("12345"))
	fmt.Println(piscine.TrimAtoi("str123ing45"))
	fmt.Println(piscine.TrimAtoi("012 345"))
	fmt.Println(piscine.TrimAtoi("Hello World!"))
	fmt.Println(piscine.TrimAtoi("sd+x1fa2W3s4"))
	fmt.Println(piscine.TrimAtoi("sd-x1fa2W3s4"))
	fmt.Println(piscine.TrimAtoi("sdx1-fa2W3s4"))
	fmt.Println(piscine.TrimAtoi("sdx1+fa2W3s4"))
}
And its output :

$ go run .
12345
12345
12345
0
1234
-1234
1234
1234
$