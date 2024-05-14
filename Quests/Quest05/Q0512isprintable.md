Files to submit
isprintable.go

Allowed functions
--allow-builtin

Instructions
Write a function that returns true if the string passed as a parameter contains only printable characters, otherwise, returns false.

Expected function
func IsPrintable(s string) bool {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.IsPrintable("Hello"))
	fmt.Println(piscine.IsPrintable("Hello\n"))

}
And its output :

$ go run .
true
false
$