# go-blockchain

Simple blockchain system with proof of work etc.

To run this:
1. Download code
2. Run "go run main.go" in cmd to execute PoW etc.
   - You can add block by running "go run main.go add -block "put data here" " after the main command
   - You can print all the blocks by running "go run main.go print"
3. See the attempts of pow to validate the hash

All the blocks will be stored in tmp/blocks directory by BadgerDB
