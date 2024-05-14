Files to submit
swap.go

Allowed functions
--allow-builtin

Instructions
Write a function that takes two pointers to an int (*int) and swaps their contents.
Expected function
func Swap(a *int, b *int) {

}
Usage
Here is a possible program to test your function :

package main

import (
	"fmt"
	"piscine"
)

func main() {
	a := 0
	b := 1
	piscine.Swap(&a, &b)
	fmt.Println(a)
	fmt.Println(b)
}
And its output :

$ go run .
1
0
$
Notions
Pointers
