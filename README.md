# Silent Zero Value Return When Accessing Missing Map Keys in Go

This example demonstrates a common, yet potentially subtle, error in Go when working with maps.  Accessing a map key that does not exist returns the zero value for the map's value type. This can lead to unexpected behavior if not properly handled.

The `bug.go` file contains code that illustrates the problem. The `bugSolution.go` file shows how to check for the existence of a key before accessing it to prevent unexpected behavior.

This is a common error that can be easily missed, especially in complex applications. This repo provides a clear example and a solution to prevent this issue.