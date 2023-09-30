# cnn classifier project
```
$ git init
```
to check directory folder
```
$ pwd
```
create readme file
```
$ touch README.md
```
add files to git through source control at vs code

files will be created at git,then create .gitgnore with template as python , and LICENSE with mit license file at git branch by adding new files.
```
to pull all files from git
$ git pull origin master
it will add files to vscode
```
create template.py file by add new file 
```
to check the path of the python file
use python terminal
```
$ python
>>> from pathlib import Path
>>> Path('x/y/z.txt')
it shows windows path like WindowsPath('x/y/z.txt')
```
to split the path and file at python terminal
```
>>> import os
>>> os.path.split("x/y/z.txt")
('x/y', 'z.txt')
>>> os.path.split("z.txt")
('', 'z.txt')
>>>
```
