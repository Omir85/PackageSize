# PackageSize
Allows to determine how big a maven artifact is after install

## Usage

Here is the way I use this tool in eclipse.

After importing the project, create a new Run configuration, with the following parameters:
- Base directory is this project.
- Goal is package.

The maven job it will then scan the content of your pom.xml and create the designated artifact in the local target directory (no need to install it in the repository).
You can then check in the target directory about the size of your artifact.
