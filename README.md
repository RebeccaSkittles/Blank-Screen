# Blank Screen

## Overview
Blank Screen is a versatile and user-friendly desktop application designed to cover all monitors with a specific background color. This tool is ideal for various scenarios, including privacy, testing, or presentations. Developed by XR Development, Blank Screen stands out for its simplicity and effectiveness. This document aims to provide a comprehensive guide on how to use and customize the application according to your needs.

## Version
1.0

## Features
- **Multi-Monitor Support:** Blank Screen seamlessly covers all connected monitors.
- **Customizable Background Color:** Change the background color through command-line arguments.
- **Easy Activation/Deactivation:** Show or hide the screen overlay using the ALT key.

## Installation
To install Blank Screen, follow these simple steps:
1. Download the latest release from the GitHub repository.
2. Extract the contents to a desired location on your computer.
3. Run `Blank Screen.exe` to launch the application.

## Usage
Blank Screen can be launched in various ways, though it is typically started using a Batch script for convenience and additional functionality.

### Launching via Batch Script
To use Blank Screen with a Batch script, create a `.bat` file with the following contents:
```batch
@echo off
SET AppPath=Blank Screen.exe
SET Color=YourColorChoice
"%AppPath%" "%Color%"
```

### Keyboard Shortcuts
- **Show/Hide Screen Overlay:** Hold down the ALT key to show the exit panel. Release the ALT key to hide it.
- **Exit Application:** Use ALT + F4 to close the application.

## Customization
Blank Screen allows customization through command-line arguments. You can specify the color of the screen overlay when launching the application.

Example:
``` batch
Blank Screen.exe Red
```
## Building from Source
If you wish to build Blank Screen from the source code:
1. Clone the repository from GitHub.
2. Open the project in Visual Studio.
3. Build the solution.

## Contributing
Contributions to Blank Screen are welcome. Please read the contributing guidelines before submitting your changes.

## License
Blank Screen is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About XR Development
XR Development is dedicated to creating innovative and practical software solutions. For more information, visit our [website](#) or follow us on [Twitter](#).

## Acknowledgments
- A special thanks to everyone who contributed to this project.
- The open-source community for continuous support and inspiration.

---

Copyright (c) 2024 XR Development

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
