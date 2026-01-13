# Under Us

A text-based adventure game created in C++ for CPSC 2720. Explore an immersive story-driven experience built with object-oriented programming principles.

## About

Under Us is a text-based adventure game developed as a group project. The game features an interactive narrative where players make choices that affect the storyline and outcome.

## Prerequisites

- g++ compiler with C++11 or higher support
- Make build tool
- Ubuntu/Linux environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/KeaganRieder/UnderUs.git
cd UnderUs
```

2. Build the project:
```bash
make
```

This will compile all source files and create the `UnderUs` executable.

## Usage

After building the project, run the game:

```bash
./UnderUs
```

Follow the on-screen prompts to navigate through the adventure. Make choices by entering the corresponding options when prompted.

## Project Structure

```
UnderUs/
├── include/          # Header files (*.h)
├── src/              # Source files (*.cpp)
├── test/             # Unit testing files
├── docs/             # Documentation
├── obj/              # Object files (generated)
├── main.cpp          # Main entry point
└── Makefile          # Build configuration
```

## Development

### Building

```bash
make              # Build the project
make clean        # Clean build artifacts
```

### Development Tools

The project uses the following tools for quality assurance:

* **Compiler:** g++
* **Standard:** C++14
* **Style Check:** cpplint 1.6.1
* **Static Analysis:** cppcheck 1.90
* **Coverage:** gcov 9.4.0, lcov 1.14
* **Memory Check:** valgrind 3.15.0
* **Unit Testing:** Google Test v.1.12.1
* **Documentation:** Doxygen 1.8.17

## Development Notes

The Makefile and .gitlab-ci.yml files are configured for Ubuntu environments.

### Project Assumptions

* One repository contains files for one project
* All unit testing files are in `test/` including `main.cpp`
* All header files are in `include/` and named `*.h`
* Every class must have a header file
* All project source files are named `*.cpp`
* Source files corresponding to headers are in `src/`
* The main entry point `main.cpp` is in the root directory

## License

This project was created as a group assignment for CPSC 2720.