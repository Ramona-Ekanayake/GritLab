Files to submit
iterativepower.go
Allowed functions
--allow-builtin

Instructions
Write an iterative function that returns the value of nb to the power of power.

Negative powers will return 0. Overflows do not have to be dealt with.

Expected function
func IterativePower(nb int, power int) int {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)


func main() {
	fmt.Println(piscine.IterativePower(4, 3))
}
And its output :

$ go run .
64
$