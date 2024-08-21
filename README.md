# Basic-Voting-machine-using-golang
This project implements a simple voting system in Go using socket programming. Clients connect to a server to cast votes for predefined candidates, and the server tracks and displays the results when terminated. The system announces a winner, a draw, or reports if no votes were cast.

# Go Voting System

This is a simple voting system implemented in Go using socket programming. The server listens for incoming connections from clients and accepts votes for predefined candidates. The server tracks the votes, and when the server is terminated, it prints the results, announces the winner, or declares a draw.

## Features

- Predefined list of candidates.
- Clients can cast votes by connecting to the server.
- Server prints vote totals when terminated and announces the winner or if there is a draw.
- Handles multiple clients concurrently.

## Prerequisites

- Go 1.16 or higher installed on your machine.

## Usage

### 1. Clone the Repository

```bash
git clone <repository-url>
cd go-voting-system
