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
```unzip -d ./onlyjs-cli cli.zip```

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
Usage: onlyjs package <packageName> [options]

the package name you want to put!

Options:
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```


`orientation` command


Change the orientation of your project.
```
Usage: onlyjs orientation <orientation> [options]

the orientation of the app!

Options:
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```


`icon` command


Change the icon of your project.
```
Usage: onlyjs icon <iconPath> [options]

the icon path for the app!

Options:
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```


`code` command


Change the main code of your project.
```
Usage: index code <codeFile> [options]

the main code of your app!

Options:
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```


`publish` command


Publish you project.
```
Usage: index publish [options]

publish your app!

Options:
  -O, --output <dir>   the path output
  -i, --accessId <id>  the access id of your project
  -h, --help           display help for command
```

# API Docs
This is the documentation for the code API inside the JavaScript file.


The file is pretty much connected to html, so code like your creating an html app only using JavaScript


But I've added some controls from client to Android app, Here's the documentation

- Imports
```js
$import <url>

# this is how you import a file 
# example
$import https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js

# you can now access jQuery on your file!
```
- Variables
```js
# access the android api
let android = $Android
# access the document body
let body = $body
# you can still access document by "document"
```

# API
## $Android.showToast("your text here") 


# License
This project is licensed under the MIT License.
