# RapidCD
Simplify Your Linux Directory Navigation with this simple trick !

## Video Demo
[![Demo Video](https://youtu.be/iJ3ZA8ZRYSg)](https://youtu.be/iJ3ZA8ZRYSg)


Aliases for Easy Directory Navigation
====================================

## Introduction
This bashrc script provides a set of aliases that simplify directory navigation in the command line. By using single-digit numbers, you can quickly move between different levels of parent directories without having to type out the full path.


## Usage
To use these aliases, follow these steps:

1. Open your terminal.
2. Navigate to your home directory by running `cd ~`.
3. Open your bashrc file for editing by running `nano .bashrc` (or use your preferred text editor).
4. Scroll to the end of the file and paste the provided aliases into the file.
5. Save the changes and exit the text editor.
6. To make the aliases take effect, either restart your terminal or run the command `source .bashrc`.
7. You can now use the aliases to navigate directories easily.

## Available Aliases
-----------------
The following aliases are available:

- `0` - Go back to the previous directory you were in. Equivalent to `cd -`
- `1` - Go up one level in the directory hierarchy. Equivalent to `cd ..`
- `2` - Go up two levels in the directory hierarchy. Equivalent to `cd ../..`
- `3` - Go up three levels in the directory hierarchy. Equivalent to `cd ../../..`
- `4` - Go up four levels in the directory hierarchy. Equivalent to `cd ../../../..`
- `5` - Go up five levels in the directory hierarchy. Equivalent to `cd ../../../../..`
- `6` - Go up six levels in the directory hierarchy. Equivalent to `cd ../../../../../..`
- `7` - Go up seven levels in the directory hierarchy. Equivalent to `cd ../../../../../../..`
- `8` - Go up eight levels in the directory hierarchy. Equivalent to `cd ../../../../../../../..`
- `9` - Go up nine levels in the directory hierarchy. Equivalent to `cd ../../../../../../../../../..`
- `10` - Go up ten levels in the directory hierarchy. Equivalent to `cd ../../../../../../../../../../..`

Notes
-----
- These aliases assume you are using the `cd` command. If you have overridden the default behavior of `cd`, the aliases may not work as expected.
- Make sure to edit your bashrc file with caution and ensure you understand the changes you're making.

License
-------
This script is provided under the [MIT License](https://opensource.org/licenses/MIT).


