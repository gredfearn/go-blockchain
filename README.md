# Go Simple Blochain implementation
This is a simple implementation of a blockchain in GoLang. 

# Setup
Follow official instructions to download and setup GoLang. 
create a .env file in the root directory and add use the .env.sample
- run:
	- `$ go run main.go`
- to write new blocks to the chain, include a BPM variable in a post request:
	- run:
		- `curl --header "Content-Type: application/json" --request POST --data '{"BPM":50}' http://localhost:8080`
- navigate to `http://localhost:8080` to see your blockchain visually in the browser

