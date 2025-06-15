# DOM License Generator

## Overview

`dom_license.py` is a Python script that generates a custom DOM license file (`LICENSE`) for your software project. The script runs on any device with Python installed, using only standard Python libraries (no external dependencies). It creates a permissive license allowing unrestricted use, modification, and distribution of your software, with no warranties and full responsibility for legal compliance placed on the user.

## Features

- Generates a `LICENSE` file based on the provided GitHub username
- Compatible with both Python 2 and Python 3
- Uses only standard Python libraries, ensuring cross-platform compatibility
- Creates a permissive license with clear terms for usage, disclaimers, and legal responsibilities

## Permissions

- Freely use, copy, modify, distribute, and sell the software for any purpose (commercial or non-commercial) without charge
- Permissions are granted irrevocably and in perpetuity

## Limitations

- Provided "as is" with no warranties (e.g., for merchantability, fitness, or non-infringement)
- The author is not liable for any claims, damages, or losses arising from the software's use
- Users are solely responsible for complying with export control laws (e.g., U.S. EAR, ITAR, EU Dual-Use Regulation) and data protection laws (e.g., GDPR)
- Third-party components may have separate licenses that users must comply with
- Users must defend and indemnify the author against claims arising from their use of the software

## Requirements

- Python installed on your device
- No additional libraries or dependencies needed

## Usage

Run the script from the command line, providing your GitHub username as an argument:

```bash
python dom_license.py your_github_user
```

or, for Python 3 explicitly:

```bash
python3 dom_license.py your_github_user
```

### Example

```bash
python dom_license.py umbx-dot
```

This will generate a `LICENSE` file in the current directory, customized with your GitHub username.

## Output

The script creates a `LICENSE` file containing the DOM license, which includes:

- Permission for unrestricted use, copying, modification, and distribution
- No warranties or liability from the author
- Responsibility for export control and data protection compliance
- Requirement to include the license unchanged in redistributions

## Notes

- Ensure you review the generated `LICENSE` to confirm it meets your project's needs
- The DOM license is perpetual and irrevocable, governed by German law
- For further details or to clarify the meaning of "DOM," contact the script author via GitHub

## Contributing

Feel free to fork this repository and submit pull requests for improvements. Ensure any contributions align with the DOM license terms.

## Contact

For questions or support, open an issue on this repository or contact the author via GitHub.
