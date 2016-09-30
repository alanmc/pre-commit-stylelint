pre-commit-styleline

================

Stylelint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For styleline: see https://github.com/stylelint/stylelint


### Using styleline with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/alanmc/pre-commit-stylelint.git
        sha: '0.0.1'  # Use the sha you want to point at
        hooks:
        -   id: stylelint
