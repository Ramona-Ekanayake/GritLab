Files to submit
capitalize.go

Allowed functions
--allow-builtin

Instructions
Write a function that capitalizes the first letter of each word and lowercases the rest.

A word is a sequence of alphanumeric characters.

Expected function
func Capitalize(s string) string {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.Capitalize("Hello! How are you? How+are+things+4you?"))
}
And its output :

$ go run .
Hello! How Are You? How+Are+Things+4you?
$