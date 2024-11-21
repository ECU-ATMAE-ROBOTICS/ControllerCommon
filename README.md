# Controller Common

Common Package allowing to easily interface with an XboxController to recieve both raw input and formatted _buttonID:buttonValue_ input for parsing via USB or Bluetooth. 

## Table of Contents

- [Installation](#installation)
- [License](#license)

## Installation
Enter `pip install git+https://github.com/ECU-ATMAE-ROBOTICS/ControllerCommon.git` into the terminal to install ControllerCommon. ControllerCommon uses Pygame to detect the controller and its inputs so Pygame is immediately installed upon the installation of ControllerCommon

## Contributing

Please follow the guidelines below, use the `build.sh` script in the root directory to confirm all requirements are met.

### Code Style

- We use `Black` for Python code formatting.

### Commit Messages

Use the conventional commit format for all your commits. This helps in automating our release process and maintaining a clear history. A conventional commit message should look like this:

```markdown
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Types include:

```markdown
- feat: Introduces a new feature to the project.
- fix: Fixes a bug in the project.
- docs: Changes to documentation only.
- style: Code changes that do not affect the meaning (white-space, formatting, missing semi-colons, etc).
- refactor: Code changes that neither fix a bug nor add a feature.
- perf: Changes that improve performance.
- test: Adding missing tests or correcting existing tests.
- build: Updates to the build process.
- chore: Changes to auxiliary tools and libraries such as documentation generation.
```

For more details, refer to the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details. GPL-3.0 is a free, copyleft license for software and other kinds of works, providing the freedom to run, study, share, and modify the software.

For more details on the GPL-3.0 License, please refer to [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.html).
