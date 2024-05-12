# Godot CI/CD Template

This repository contains a simple "Hello World" game built with the Godot Engine. It is set up with continuous integration and continuous deployment (CI/CD) to streamline the development and release process.

## Features

- Basic "Hello World" game example.
- Automatically tests and builds with latest patch of project version.
- Built-in CI/CD pipeline for automated testing and release.
- Integration with GUT for unit testing.

## Getting Started

To get started with this project, clone the repository and open it in Godot Engine.

```bash
git clone https://github.com/mrjsj/godot-cicd-template.git
```

## CI/CD Pipeline

The CI/CD pipeline is configured to automatically export the game for the following platforms upon pushing to the main branch. Both zipped and executables are released.

- Windows
- HTML5 (Web)
- Linux


## Contributing

Contributions to CI/CD pipeline are welcome. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.