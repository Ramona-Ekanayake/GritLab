Files to submit
isupper.go

Allowed functions
--allow-builtin

Instructions
Write a function that returns true if the string passed as parameter contains only uppercase characters, otherwise, returns false.

Expected function
func IsUpper(s string) bool {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.IsUpper("HELLO"))
	fmt.Println(piscine.IsUpper("HELLO!"))

}
And its output :

$ go run .
true
false
$
