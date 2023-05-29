# go-example-bank-web-api

## Online bank project (example) in Go with Web API

## Tests
- Go to `cd src/bankcore` and run `go test -v`

## Execute the program
- Go to `cd src/bankapi` and run `go run main.go`
- Open in the browser and make a deposit of 100 to the bank account 1001: 
`http://localhost:8000/deposit?number=1001&amount=100`
- Check the statement of the bank account 1001: 
`http://localhost:8000/statement?number=1001`
- Make a withdraw of 10: 
`http://localhost:8000/widthraw?number=1001&amount=10`
- Transfer money from 1001 to 1002 account: 
`http://localhost:8000/widthraw?number=1001&amount=10&dest=1002`
