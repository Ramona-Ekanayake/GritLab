Files to submit
sqrt.go

Allowed functions
--allow-builtin

Instructions
Write a function that returns the square root of the int passed as parameter, if that square root is a whole number. Otherwise it returns 0.

Expected function
func Sqrt(nb int) int {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.Sqrt(4))
	fmt.Println(piscine.Sqrt(3))
}
And its output :

$ go run .
2
0
$