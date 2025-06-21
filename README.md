# Pre-commit Hooks

A collection of pre-commit hooks to maintain code quality and consistency across your projects.

## What is this?

This repository contains a pre-commit configuration that automatically runs code quality checks and formatting before each commit. It helps ensure that all committed code follows consistent standards and best practices.

## Quick Start

This repository is set up as a template with pre-commit already configured.

### Clone this repository
```shell
git clone git@github.com:Siiir/pre-commit-hooks.git
cd pre-commit-hooks
```

### Create Python3 virtual environment
```bash
python3 -m venv venv/
./venv/bin/pip install -r requirements.txt
```

### Install the git hooks (Linux script)
```bash
./venv/bin/activate
pre-commit install
pre-commit install --hook-type commit-msg
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Ensure all pre-commit hooks pass
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
