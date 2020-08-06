# pre-commit-hooks

Config files for pre-commit hooks that I regularly use.

## Using the hooks

1. Copy all of the from the config folder into the root directory of your project.
1. Install `pre-commit` in your environment.

    ```bash
    pip install pre-commit

    poetry add pre-commit

    conda install pre-commit
    ```

1. Install the hooks

    ```bash
    pre-commit install
    ```

1. Modify files

    ```bash
    pre-commit run --all-files
    ```

1. Or try committing files and they will be modified then.
