# hooks-playground


Git hooks for various purposes.

## Usage

Copy the hook you want to use to the `.git/hooks/` directory in the repo you want to use them in.

## prepare-commit-message


Finds all unique directories with staged files in them, and adds them to the commit message.

### TODO

- Automate abbreviating directory names in the message - balance of unique, concise & legible.
