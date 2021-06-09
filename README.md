# curso-go-complete
Go The Complete Developer's Guide (Golang)

## Go commands
- go build: compiles a bunch of go source codes
- go run: compiles and executes files
- go fmt: formats all the code in each file in the current directory
- go install: compiles and installs a package
- go get: downloads the raw source code of someone else´s package
- go test: runs any tests associated with the current project

## Packages
`package main`

The very first line is the declaration of the package we are into

- Executable: generates a file we can run:
    - package `main` -> main is a reserved word (**must have a func called main**)
    - go build
    - main.exe or ./main
- Reusable: code used as 'helpers'. Good place to put reusable logic
     - package `calculator`-> custom name

## Imports
Import give access to some code to our package.
[Standard library packages](golang.org/pkg)

## Organization 
1. package declaration
2. import other packages that we need
3. declare functions, tell go to do things