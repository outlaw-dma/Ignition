<!--- Badges --->
![GitHub contributors](https://img.shields.io/github/contributors/thecesrom/Ignition)
![GitHub last commit (main)](https://img.shields.io/github/last-commit/thecesrom/Ignition/main)
![GitHub license](https://img.shields.io/github/license/thecesrom/Ignition)

# Ignition

Ignition is a set of packages and modules that allows developers to get code completion in their IDE of choice.

## Branches

This repository consists of the following branches:

### [main](https://github.com/thecesrom/Ignition/tree/main)
This branch will contain all Scripting Functions from the latest Ignition Release requiring only Python

### [7.9](https://github.com/thecesrom/Ignition/tree/7.9)
This branch will contain all Scripting Functions from the latest Ignition Release for the 7.9 version requiring only Python

### [8.0](https://github.com/thecesrom/Ignition/tree/8.0)
This branch will contain all Scripting Functions from the latest Ignition Release for the 8.0 version requiring only Python

### [jython](https://github.com/thecesrom/Ignition/tree/jython)
This branch will contain all Scripting Functions from the latest Ignition Release requiring Jython (see [jython prerequisites](https://github.com/thecesrom/Ignition/tree/jython#prerequisites))

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed Python 2.7.18 ([download here](https://www.python.org/downloads/release/python-2718/))
* You are familiar with [Ignition 8.1 Scripting Functions](https://docs.inductiveautomation.com/display/DOC81/Scripting+Functions)

## Using Ignition

To use Ignition, download the code targeted to your desired version from the [releases page](https://github.com/thecesrom/Ignition/releases) and add it as a dependency to your scripting project.

## Packages

Ignition consists of the following packages:

* java/javax
* system

### java/javax

These are libraries for some Java packages and functions that are imported in `system` packages meant to be used on development environments where no JDK can be installed, and the project interpreter is Python 2.7.

### system

Is a package that includes all Ignition Scripting Functions.

## Contributing to Ignition

To contribute to Ignition, follow these steps:

1. Fork this repository
2. Create a local copy on your machine
3. Create a branch
4. Make your changes and commit them
5. Push to the original branch
6. Create the pull request

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Contributors

Thanks to the everyone who has contributed to this project.

Up-to-date list of contributors can be found [here](https://github.com/thecesrom/Ignition/graphs/contributors).

## License

See the [LICENSE](https://github.com/thecesrom/Ignition/blob/master/LICENSE).


## Code of conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
