# Godot CI/CD Template

This repository contains a simple "Hello World" game built with the Godot Engine. It is set up with continuous integration and continuous deployment (CI/CD) to streamline the development and release process.

## Features

- Basic "Hello World" game example.
- Built-in CI/CD pipeline for automated testing and deployment.
- (Upcoming) Integration with GUT for unit testing.

## Getting Started

To get started with this project, clone the repository and open it in Godot Engine.

```bash
git clone https://github.com/mrjsj/godot-cicd-template.git
```

## CI/CD Pipeline

The CI/CD pipeline is configured to automatically export the game for the following platforms upon pushing to the main branch:

- macOS
- Windows
- HTML5 (Web)
- Linux

## Exported Names

The exported files follow a standard naming convention:

- macOS: `Godot_CICD_Template_vX.X.X-macOS.zip`
- Windows: `Godot_CICD_Template_vX.X.X-Windows.zip`
- HTML5 (Web): `Godot_CICD_Template_vX.X.X-HTML5.zip`
- Linux: `Godot_CICD_Template_vX.X.X-Linux.tar.gz`

Replace `X.X.X` with the actual version of your game.

## Contributing

Contributions to the game or CI/CD pipeline are welcome. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.