# Act - Run Your GitHub Actions Locally 🚀

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Run%20Locally-blue.svg)
![CI](https://img.shields.io/badge/CI-Continuous%20Integration-brightgreen.svg)
![DevOps](https://img.shields.io/badge/DevOps-Streamlined%20Processes-orange.svg)
![Go](https://img.shields.io/badge/Language-Go%20Lang-lightgrey.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Introduction

Welcome to **Act**! This tool allows you to run your GitHub Actions locally, making it easier to test and debug your workflows before pushing them to your repository. With Act, you can save time and reduce errors in your CI/CD process. 

For the latest releases, visit [this link](https://github.com/Ayan9991/act/releases). Download the necessary files and execute them to get started.

## Features

- **Local Testing**: Run your GitHub Actions on your local machine.
- **Fast Feedback**: Get immediate results without waiting for the cloud.
- **Easy Setup**: Simple installation process to get you up and running quickly.
- **Golang Support**: Built with Go, ensuring performance and efficiency.
- **Community Driven**: Open-source contributions welcome!

## Installation

To install Act, follow these steps:

1. **Download the latest release** from [this link](https://github.com/Ayan9991/act/releases). Choose the appropriate file for your operating system.
2. **Extract the files** to a directory of your choice.
3. **Add the directory to your PATH** so you can run Act from anywhere in your terminal.

For example, if you are using macOS or Linux, you can add the following line to your `.bashrc` or `.zshrc`:

```bash
export PATH=$PATH:/path/to/act
```

After updating your PATH, run the following command to verify the installation:

```bash
act --version
```

## Usage

Once you have installed Act, you can start using it to run your GitHub Actions locally.

### Basic Command

To run your GitHub Actions, navigate to your repository directory in the terminal and use:

```bash
act
```

This command will execute the default workflow defined in your `.github/workflows` directory.

### Running Specific Events

You can also run specific events by specifying the event name:

```bash
act push
```

This command simulates a `push` event.

### Environment Variables

If your workflows require environment variables, you can set them directly in the command line:

```bash
act -e event.json
```

### Docker Support

Act uses Docker to run your workflows. Make sure you have Docker installed and running. You can customize the Docker image used by specifying the `--image` flag:

```bash
act --image my-custom-image
```

### Debugging

If you encounter issues, you can run Act in verbose mode to get more detailed logs:

```bash
act --verbose
```

## Contributing

Contributions are welcome! If you would like to contribute to Act, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch and open a pull request.

Please ensure your code adheres to the project's coding standards and includes tests where applicable.

## License

Act is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Support

For support, check the "Releases" section for updates or open an issue in the repository. You can also visit [this link](https://github.com/Ayan9991/act/releases) for the latest releases.

---

Thank you for using Act! We hope it enhances your workflow and improves your development process.