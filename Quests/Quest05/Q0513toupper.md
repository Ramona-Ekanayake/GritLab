Files to submit
toupper.go

Allowed functions
--allow-builtin

Instructions
Write a function that capitalizes each letter in a string.

Expected function
func ToUpper(s string) string {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.ToUpper("Hello! How are you?"))
}
And its output :

$ go run .
HELLO! HOW ARE YOU?
$
Notions
strings/ToUpper