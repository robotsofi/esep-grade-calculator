# ESEP Grade Calculator

This library is a simple utility to calculate your grades. The main program (grade_calculator.g) properly manages the types of grades and determines final letter grade using these components. A test file(grade_calculator_test.go) is provided that checks if the grades are correctly determined.

Tech Used: Golang

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```