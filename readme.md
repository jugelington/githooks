# hooks-playground


Git hooks for various purposes.

## Usage

Copy the hook you want to use to the `.git/hooks/` directory in the repo you want to use them in.

## prepare-commit-message


Finds all unique directories with staged files in them, and adds them to the commit message, in a formatted manner.


For examples, if files in directories called `Foo`, `Bar`, and `FooBar` have been changed, the commit message will start `[F|B|FB]`

