# OnlyJS
A command-line interface to create Android apps or games using only one JavaScript file.

# Requirements
This CLI requires Node.js to be installed.

# Installation
1. Download a zip
```wget -O cli.zip https://github.com/FilipinoAkoShaders/onlyjs-cli/blob/main/onlyjs-cli-v0.1.zip?raw=true```

2. Make a folder named "onlyjs-cli"
```mkdir onlyjs-cli```

3. Unzip the zip to the folder
```unzip -d ./onlyjs-cli cli.zip``|

4. Add to the path variable
```export PATH=$PATH:<path-to-onlyjs-cli-folder>```

5. YOUR SET!

# Usage
```
Usage: onlyjs [options] [command]

Options:
  -V, --version        output the version number
  -h, --help           display help for command

Commands:
  init                 create a project
  package <packageName>  the package name you want to put!
  orientation <orientation>  the orientation of the app!
  icon <iconPath>      the icon path for the app!
  code <codeFile>      the main code of your app!
  publish              publish your app!
  help [command]       display help for command
```


`init` command


Create a new project
```
Usage: onlyjs init [options]

create a project

Options:
  -n, --name <string>  your project name
  -h, --help           display help for command
```


`package` command


Change the package name of your project.
```
Usage: index package <packageName> [options]

the package name you want to put!

Options:
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```
