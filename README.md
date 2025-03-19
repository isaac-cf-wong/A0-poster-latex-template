# A0-size poster LaTeX template

This is a simple A0-size poster template designed for research presentations. It includes sections for the title, authors, institute logos, a QR code for easy access to the paper, and structured content areas for key research findings.

## Pre-commit hooks

Set up Git hook scripts to automatically check files for issues before each commit.

Install `pre-commit`:

```console
pip install pre-commit
```

Install the git hook scripts:

```console
pre-commit install
```

(Optional) it's usually a good idea to run the hooks against all of the files when adding new hooks (usually pre-commit will only run on the changed files during git hooks)

```console
pre-commit run --all-files
```

## Compile the files

Use the following command to compile the files:

```console
make
```
