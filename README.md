# Commit Roulette

Fun program that pulls a random commit message from your commit history and displays it.

## Usage

```bash
# Build the program
go build ./cmd/commit-roulette/main.go -o ./bin/commit-roulette

# Run the program
./bin/commit-roulette --username <github-username>
```

## Options

- `--username`: The GitHub username to pull the commit history from.
- `--repo`: The GitHub repository to pull the commit history from.
- `--branch`: The GitHub branch to pull the commit history from.
