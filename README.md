# Shell Utilities

This repository contains a collection of personal shell utilities that can be used for various purposes.

## Contents

- [scripts/catdir](./scripts/catdir): A utility to display the contents of files in the current directory based on specific patterns.
  - This is useful for collecting data for use with large language models (LLMs).
- [scripts/aliases](./scripts/aliases): A collection of commonly used aliases for the shell

## Usage

To use any of the utilities in this repository, navigate to the appropriate directory and execute the script using the appropriate command.

For example, to use the `catdir` utility:

```bash
./scripts/catdir -e '*.git/*' -i '*.txt'
```

## License

This project is licensed under the terms of the Apache License 2.0. See the [LICENSE](./LICENSE) file for more information.
