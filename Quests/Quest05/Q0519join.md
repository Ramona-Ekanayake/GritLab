Files to submit
join.go

Allowed functions
--allow-builtin

Instructions
Write a function that returns the concatenation of all the strings of a slice of strings separated by the separator passed as the argument sep.

Expected function
func Join(strs []string, sep string) string {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	toConcat := []string{"Hello!", " How", " are", " you?"}
	fmt.Println(piscine.Join(toConcat, ":"))
}
And its output :

$ go run .
Hello!: How: are: you?
$
Notions
strings/Join