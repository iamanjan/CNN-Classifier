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

write code for setup.py and run it
```
$python setup.py
```
write code for setup.py,setup.cgg,requiremnts.txt,requirements_dev.txt,pyproject.toml,tox.ini, and init_setup.sh.

run the init_setup.sh file,it will run the all above files
```
$ bash init_setup.sh
it will install the all dependencies libraries in local env.
```
next create ,write code for 4 files and under src/components like 
```
stage_01_data_ingestion.py
stage_02_prepare_base_model.py
stage_03_train.py
stage_04_evaluation.py
```
write code at data_ingestion and then create logger file at utils.py under utils folder for dataingestion.py

create ,write a code at config_entity.py file under entity folder 

write code at trails.py under research folder

create,write code for data_ingestion.file, and run ,check it whether code is working or not before u run data_ingestion file under src/components/data-ingestion.py  and pipeline/data_ingestion.py file

### Workflow
```
1.reserach/trils
2.config.yaml
3.entity
4.component
5.pipeline
6.training
7.predeiction
8.test your package
9.dvc for the reprodcuing the pipeline
```
