Files to submit
printnbrinorder.go

Allowed functions
github.com/01-edu/z01.PrintRune, --allow-builtin

Instructions
Write a function which prints the digits of an int passed in parameter in ascending order. All possible values of type int have to go through, excluding negative numbers. Conversion to int64 is not allowed.

Expected function
func PrintNbrInOrder(n int) {

}
Usage
Here is a possible program to test your function :

package main

import "piscine"

func main() {
	piscine.PrintNbrInOrder(321)
	piscine.PrintNbrInOrder(0)
	piscine.PrintNbrInOrder(321)
}
And its output :

$ go run . | cat -e
1230123$
$
Notions
01-edu/z01
rune-literals