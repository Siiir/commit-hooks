# Commit Hooks

A collection of commit hooks to maintain code quality and consistency across your projects.

## Quick Start

### Clone this repository
```shell
git clone git@github.com:Siiir/commit-hooks.git
cd commit-hooks
```

### Create Python3 virtual environment
```bash
python3 -m venv venv/
./venv/bin/pip install -r requirements.txt
```

### Install the git hooks (Linux script)
```bash
source ./venv/bin/activate
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
