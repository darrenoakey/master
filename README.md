# Clean Workspace Script

![Banner Image](banner.jpg)

## Purpose

This script helps you clean your local Git workspace by discarding all local changes and untracked files, and resetting your current branch to the latest version from the remote repository. It's useful for starting with a clean slate when you want to discard local experiments or ensure you have the most up-to-date version of your project.

## Usage

1.  Navigate to the root directory of your Git repository in the terminal.
2.  Run the script.
3.  If the script detects local changes, it will prompt you for confirmation before proceeding. Type `y` or `Y` to proceed with discarding changes, or `n` to abort.

## Installation (If Required)

No installation is necessary. Simply save the script to a file (e.g., `clean_workspace.sh`) and make it executable using `chmod +x clean_workspace.sh`.

## Examples

To run the script:

```bash
./clean_workspace.sh
```

If you have local changes:

```
Warning: You have local changes (including new/untracked files).
These will be deleted. Proceed? (y/n): y
Workspace cleaned and moved to up-to-date 'main'. All local changes and untracked files (excluding ignored files) have been deleted.
```

If you abort the script due to local changes:

```
Warning: You have local changes (including new/untracked files).
These will be deleted. Proceed? (y/n): n
Aborted.
```

## License

This project is licensed under [CC BY-NC 4.0](https://darren-static.waft.dev) - free to use and modify, but no commercial use without permission.
