Files to submit
isnegative.go

Allowed functions
github.com/01-edu/z01.PrintRune, --allow-builtin

Instructions
Write a function that prints 'T' (true) on a single line if the int passed as parameter is negative, otherwise it prints 'F' (false).

Expected function
func IsNegative(nb int) {

}
Usage
Here is a possible program to test your function :

package main

import "piscine"

func main() {
	piscine.IsNegative(1)
	piscine.IsNegative(0)
	piscine.IsNegative(-1)
}
And its output :

$ go run .
F
F
T
$
Notions
01-edu/z01
