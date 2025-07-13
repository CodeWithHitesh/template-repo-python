# Template Python Repository

This repository provides a minimal Python project structure with
a GitHub Actions workflow for automated testing. It can be used as a
starting point for new Python projects.

## Project Layout

- `src/` - application source code
- `tests/` - unit tests
- `.github/workflows/` - CI configuration

## Branch Protection

Branch protection rules should require pull request reviews and passing
status checks before merging to the `main` branch. Admins may be
allowed to bypass these requirements where needed.

## Getting Started

1. Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies (if any) and run tests:

   ```bash
   pip install -r requirements.txt  # optional
   pytest
   ```

## License

This project is provided as-is under the MIT License.
