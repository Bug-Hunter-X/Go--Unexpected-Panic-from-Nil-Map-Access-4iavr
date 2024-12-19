# Go: Unexpected Panic from Nil Map Access

This repository demonstrates a common error in Go: accessing a map without first checking if it's nil.  This can lead to unexpected panics in your application.

## The Bug

The `bug.go` file contains code that attempts to assign a value to a map without first checking if the map has been initialized. This results in a runtime panic.

## The Solution

The `bugSolution.go` file shows the corrected code.  Before accessing or assigning to the map, it checks if the map is nil and initializes it if necessary.