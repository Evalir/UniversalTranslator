# UniversalTranslator

Final individual project for the "Tendencias en desarrollo de aplicaciones" class.

## App objective

This CLI (Command Line App) can be used to convert from one longitude unit from the International Unit System to another one.

## App installation

First, you need to have pip installed; it's the python package manager that you'll use to then install the application. You can get it [here](https://www.liquidweb.com/kb/install-pip-windows/), however, it should be preinstalled on your system; still, I recommend upgrading to the latest version to avoid conflicts.

After installing pip, you can just run this command: `pip install unitrans-evalir`

When you install it with pip (beware, this will also install all of the CLI dependencies), you can then use it by running `UniversalTranslator --help`: this will display the help file with all the command options.

Example:

```
pip install unitrans-evalir
UniversalTranslator --pathname input.txt --writepath output.txt
```

This example will take the input.txt file that you have created on the folder you're in, process the contents, and write to the `output.txt` file the converted units.

### Note for windows users

For using the command line app, you MUST have installed these 3 things:

- The latest version of Python 3.
- The latest version of PyPI.
- Git Bash.
  Using the normal windows prompt and powershell will not work. You MUST use the linux subsystem command line or the Git bash to use the application.

### Input Format example:

`1 m cm`: 1 meter to centimeters.
`2 dm km`: 2 decimeters to kilometers.
For further info about usage, please refer to [this table on wikipedia.](https://en.wikipedia.org/wiki/Metre)

## Contributing:

Please take a look at the CONTRIBUTING.MD file.

## Miscellaneous

- [CRC Cards](https://www.dropbox.com/s/ziuwpm2cyhquio0/CRC%20responsiblity.png?dl=0)
- [UML Diagram](https://www.dropbox.com/s/634thy9jduy5mgd/UML%20Diagram.png?dl=0)
- [PyPI package index for 10% extra points on the project](https://pypi.org/project/unitrans-evalir/)
