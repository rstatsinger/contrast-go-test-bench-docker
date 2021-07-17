# Go Test Bench - Demo app for Contrast Security Go agent - Easy setup/run using Docker


This is an intentionally vulnerable Go application. Uses Go's standard library, `net/http`,
for client/server implementations. For more info on this framework, visit
[net/http](https://golang.org/pkg/net/http/).

The go-test-bench application includes vulnerabilities from the OWASP Top
10 and is intended to be used as an educational tool for developers and
security professionals. Any maintainers are welcome to make pull requests.

This setup lets you run the application in a Docker container, isolating it from your host.

## Installation/Requirements

Just git and docker

# How to Run

1. git clone this rep
2. Drop your contrast_security.yaml file into the project root directory
3. Edit the yaml file to set logging to stdout, or set the logging paths to /tmp
4. ./demo.sh reset
5. ./demo.sh
6. Interact with the app at http://localhost:8080

