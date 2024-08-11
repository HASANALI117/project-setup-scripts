# Project Setup Scripts

This repository contains setup scripts for different programming languages.

## Go Project Setup

To quickly create a standard Go project layout without cloning this repository, you can run the following command in your terminal:

```sh
curl -sSL https://raw.githubusercontent.com/HASANALI117/project-setup-scripts/main/go_project_setup.sh | bash
```

This command will download and execute the `go_project_setup.sh` script, which will prompt you for a project name and create the necessary directories and files for a Go project.

### Script Details

The `go_project_setup.sh` script performs the following actions:

1. Prompts the user for a project name.
2. Creates the project directory structure:
   - `cmd/<projectName>`
   - `pkg`
   - `api`
   - `web`
   - `scripts`
   - `build`
   - `deployments`
   - `test`
   - `docs`
3. Creates a `main.go` file in the `cmd/<projectName>` directory with a simple "Hello, world!" program.
4. Creates a basic `README.md` file.
5. Creates a `.gitignore` file with common Go exclusions.

### Example Usage

```sh
Enter the project name:
my-go-project
Standard Go Project Layout for my-go-project created.
```
