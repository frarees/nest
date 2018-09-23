# NEST - Natural Entertainment Software Trunk

NEST allows game code and assets to be bundled for easy distribution with the DOME engine.

## Usage

`./nest [options] -o bundle-file -- [files | directories]`

Options:
* `-z` will create a bundle
* `-x` is reserved to unzip a bundle in the future
* `-v` will print the version of the bundler.

This will create a bundle named "bundle-file" containing the various files and directories specified.
If the only item to bundle is a directory, the bundle will be created as if the directory was the root.

This tool is likely to be sensitive to the current working directory, so make sure you are in the correct directory before running the command.



