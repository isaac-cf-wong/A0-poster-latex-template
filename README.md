# A0-size poster LaTeX template

This is a simple A0-size poster template designed for research presentations. It includes sections for the title, authors, institute logos, a QR code for easy access to the paper, and structured content areas for key research findings.

## Required packages

- baposter

For TeX Live (Linux/macOS/Windows)

1. Open a terminal and run:

```console
tlmgr install baposter
```

(If tlmgr is not available, update TeX Live first.)

2. If you’re using Overleaf, baposter is already included, so no installation is needed.

For MiKTeX (Windows)

1. Open the MiKTeX Console.
2. Go to Packages and search for baposter.
3. Select it and click Install.

Alternatively, install via the command line:

```console
miktex-packager install baposter
```

For MacTeX (macOS)

If you’re using MacTeX, baposter should already be included. If not, update MacTeX:

```console
sudo tlmgr update --self
sudo tlmgr install baposter
```

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
