# Introduction

<!-- This is a comment -->

## Tools

### Cookiecutter

Cookiecutter is a command-line utility that creates projects from project templates. The project template is a directory containing project files and directories. The project template may contain variables that are replaced by the user's input when the project is created.

Cookiecutter is a Python package that can be installed using pip:

```bash
pip install cookiecutter
```

To create a project from a project template, run the following command (example):

```bash
cookiecutter https://github.com/khuyentran1401/data-science-template
```

The user will be prompted to enter values for the variables defined in the project template. The following is an example of the user input:

```bash
  [1/4] project_name (Project Name):
  [2/4] author_name (Your Name):
  [3/4] Select dependency_manager
    1 - pip
    2 - poetry
    Choose from [1/2]:
  [4/4] compatible_python_versions (^3.9):
```