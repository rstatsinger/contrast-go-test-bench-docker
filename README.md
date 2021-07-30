# Go Test Bench - Demo App for Contrast Security Go Agent - Easy setup/run using Docker Compose


This is an intentionally vulnerable Go application. It uses Go's standard library, `net/http`,
for client/server implementations. For more info on this framework, visit
[net/http](https://golang.org/pkg/net/http/).

The go-test-bench application includes vulnerabilities from the OWASP Top
10 and is intended to be used as an educational tool for developers and
security professionals. Any maintainers are welcome to make pull requests.

This setup deploys the Contrast Security Go instrumentation and then runs the application in a Docker container, isolating it from your environment.

## Prerequisites

A Contrast Security account, git, and docker (with docker compose)

# How to Run

1. git clone this repo
2. Drop your contrast_security.yaml file for the Go agent into the project root directory
3. ./demo.sh reset
4. ./demo.sh
5. Interact with the app at http://localhost:8080
6. View the results in Contrast Security

