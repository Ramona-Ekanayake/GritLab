Files to submit
strrev.go

Allowed functions
--allow-builtin

Instructions
Write a function that reverses a string.

This function will return the reversed string.

Expected function
func StrRev(s string) string {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	s := "Hello World!"
	s = piscine.StrRev(s)
	fmt.Println(s)
}
And its output :

$ go run .
!dlroW olleH
$